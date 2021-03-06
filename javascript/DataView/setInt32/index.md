---
title: 'setInt32'
attributions:
  - 'Microsoft Developer Network: [Article](http://msdn.microsoft.com/en-us/library/ie/br212460(v=vs.94).aspx)'
compatibility:
  feature: setInt32
  topic: javascript
readiness: 'Ready to Use'
summary: 'Sets the Int32 value at the specified byte offset from the start of the view. There is no alignment constraint; multi-byte values may be set at any offset.'
tags:
  - JS_Basic
uri: javascript/DataView/setInt32

---
## Summary

Sets the Int32 value at the specified byte offset from the start of the view. There is no alignment constraint; multi-byte values may be set at any offset.

## Syntax

    dataView.setInt32 (byteOffset, value, littleEndian);

**byteOffset**
:   The place in the buffer at which the value should be retrieved.

**value**
:   The value to set.

**littleEndian**
:   Optional. If false or undefined, a big-endian value should be written, otherwise a little-endian value should be written.

## Examples

The following example shows how to set the first Int32 in the DataView.

``` js
var req = new XMLHttpRequest();
     req.open('GET', "http://www.example.com");
     req.responseType = "arraybuffer";
     req.send();

     req.onreadystatechange = function () {
         if (req.readyState === 4) {
             var buffer = req.response;
             var dataView = new DataView(buffer);
             dataView.setInt32(0, 9);
         }
     }
```

## Remarks

These methods raise an exception if they would write beyond the end of the view.


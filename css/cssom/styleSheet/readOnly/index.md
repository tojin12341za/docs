---
title: 'readOnly'
attributions:
  - 'Microsoft Developer Network: [[Windows Internet Explorer API reference](http://msdn.microsoft.com/en-us/library/ie/hh828809%28v=vs.85%29.aspx) Article]'
notes:
  - 'Non-standard; deletion candidate.'
readiness: 'Not Ready'
relationships:
  applies_to:
    predicate: 'Property of '
    value: css/cssom/styleSheet
    href: /css/cssom/styleSheet
  return:
    predicate: 'Returns an object of type '
    value: Boolean
    href: /css/cssom/styleSheet
summary: 'Non standard. Indicates if the style sheet is currently in read only mode.'
tags:
  - API_Object_Properties
  - DOM
  - Needs_Examples
uri: css/cssom/styleSheet/readOnly

---
## Summary

Non standard. Indicates if the style sheet is currently in read only mode.

Property of [css/cssom/styleSheet](/css/cssom/styleSheet)[css/cssom/styleSheet](/css/cssom/styleSheet)

## Syntax

**Note**: This property is read-only.

``` js
var isReadOnly = stylesheet.readOnly;
```

## Return Value

Returns an object of type BooleanBoolean

Returns whether the style sheet is currently in read only mode.

## Notes

You cannot modify style sheets obtained through a **link** object or the [**@import**](/css/atrules/@import) rule while the [**designMode**](/dom/Document/designMode) property is enabled. For more information, see Introduction to MSHTML Editing.

## See also

### Related pages

-   styleSheet[styleSheet](/css/cssom/styleSheet)
-   rule[rule](/css/cssom/rule)

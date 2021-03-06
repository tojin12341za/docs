---
title: 'inputBuffer'
notes:
  - 'Deprecated; deletion candidate. See http://webaudio.github.io/web-audio-api/.'
readiness: 'Out of Date'
relationships:
  applies_to:
    predicate: 'Property of '
    value: apis/webaudio/AudioProcessingEvent
    href: /apis/webaudio/AudioProcessingEvent
standardization_status: 'W3C Editor''s Draft'
summary: "An AudioBuffer containing the input audio data. It will have a number of channels equal to the numberOfInputChannels parameter of the createScriptProcessor() method. This AudioBuffer is only valid while in the scope of the onaudioprocess function. Its values will be meaningless outside of this scope.\n"
tags:
  - API_Object_Properties
  - API
  - WebAudio
  - Needs_Examples
uri: apis/webaudio/AudioProcessingEvent/inputBuffer

---
## Summary

An AudioBuffer containing the input audio data. It will have a number of channels equal to the numberOfInputChannels parameter of the createScriptProcessor() method. This AudioBuffer is only valid while in the scope of the onaudioprocess function. Its values will be meaningless outside of this scope.

**Deprecated; deletion candidate. See <http://webaudio.github.io/web-audio-api/>.**

Property of [apis/webaudio/AudioProcessingEvent](/apis/webaudio/AudioProcessingEvent)[apis/webaudio/AudioProcessingEvent](/apis/webaudio/AudioProcessingEvent)

## Syntax

**Note**: This property is read-only.

``` js
var result = AudioProcessingEvent.inputBuffer;
```

## Related specifications

[W3C Web Audio API](http://webaudio.github.io/web-audio-api/)
:   W3C Editor's Draft

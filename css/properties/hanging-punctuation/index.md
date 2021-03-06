---
title: 'hanging-punctuation'
compatibility:
  feature: hanging-punctuation
  topic: css
notes:
  - 'Add example, description, compatibility.'
overview_table:
  '[Initial value](/css/concepts/initial_value)': '`none`'
  'Applies to': 'inline elements'
  '[Inherited](/css/concepts/inherited)': 'Yes'
  Media: visual
  '[Computed value](/css/concepts/computed_value)': 'as specified'
  Animatable: 'No'
  '[CSS Object Model Property](/css/concepts/cssom)': ''
  Percentages: 'Not available'
readiness: 'In Progress'
standardization_status: 'W3C Working Draft'
summary: 'If a punctuation mark is present, this property determines if the punctuation mark hangs and whether it can be placed outside the line box and the start or at the end of a line of text.'
tags:
  - CSS_Properties
  - CSS
  - Needs_Examples
uri: css/properties/hanging-punctuation

---
## Summary

If a punctuation mark is present, this property determines if the punctuation mark hangs and whether it can be placed outside the line box and the start or at the end of a line of text.

## Overview table

[Initial value](/css/concepts/initial_value)
:   `none`

Applies to
:   inline elements

[Inherited](/css/concepts/inherited)
:   Yes

Media
:   visual

[Computed value](/css/concepts/computed_value)
:   as specified

Animatable
:   No

[CSS Object Model Property](/css/concepts/cssom)
:

Percentages
:   Not available

## Syntax

## Values

none
:   No character hangs

first
:   This is an opening bracket or quote that is at the start of the first formatted line of an element that hangs. Any characters in the Unicode categories Ps, Pf, Pi are applied.

last
:   This is a closing bracket or quote of an element at the end of the last formatted line. The element hangs and this applies to any characters in the Unicode categories Pe, Pf, and Pi.

force-end
:   A stop or comma at the end of a line hangs

allow-end
:   A stop or comma at the end of a line hangs if it does not otherwise fit prior to justification.

## Notes

When measuring the line's contents for fit, alignment, or justification, the punctuation mark is not considered when it hangs. The mark may be placed outside the line box depending on the line's alignment.

## Related specifications

[CSS Text Module Level 3](http://www.w3.org/TR/css3-text/#hanging-punctuation0)
:   Working Draft

## See also

### Related articles

#### Text

-   [block-progression](/css/properties/block-progression)

-   [font-language-override](/css/properties/font-language-override)

-   [font-size](/css/properties/font-size)

-   [hyphenate-limit-chars](/css/properties/hyphenate-limit-chars)

-   [hyphenate-limit-lines](/css/properties/hyphenate-limit-lines)

-   [hyphenate-limit-zone](/css/properties/hyphenate-limit-zone)

-   [hyphens](/css/properties/hyphens)

-   [ime-mode](/css/properties/ime-mode)

-   [layout-grid](/css/properties/layout-grid)

-   [layout-grid-char](/css/properties/layout-grid-char)

-   [layout-grid-line](/css/properties/layout-grid-line)

-   [layout-grid-mode](/css/properties/layout-grid-mode)

-   [layout-grid-type](/css/properties/layout-grid-type)

-   [letter-spacing](/css/properties/letter-spacing)

-   [text-overflow-ellipsis](/css/properties/text-overflow-ellipsis)

-   [text-overflow-mode](/css/properties/text-overflow-mode)

-   [text-rendering](/css/properties/text-rendering)

-   [user-modify](/css/properties/user-modify)

-   [Text](/css/text)

-   [size](/html/attributes/size)

-   [b](/html/elements/b)

-   [b](/html/elements/b/ja)

-   [br](/html/elements/br)

-   [br](/html/elements/br/ja)

-   [caption](/html/elements/caption)

-   [cite](/html/elements/cite)

-   [code](/html/elements/code)

-   [del](/html/elements/del)

-   [dfn](/html/elements/dfn)

-   [em](/html/elements/em)

-   [font](/html/elements/font)

-   [hr](/html/elements/hr)

-   [i](/html/elements/i)

-   [ins](/html/elements/ins)

-   [kbd](/html/elements/kbd)

-   [mark](/html/elements/mark)

-   [samp](/html/elements/samp)

-   [strong](/html/elements/strong)

-   [Achieving typographic effects with the canvas tag](/tutorials/canvas_texteffects)

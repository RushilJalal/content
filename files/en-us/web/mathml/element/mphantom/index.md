---
title: <mphantom>
slug: Web/MathML/Element/mphantom
tags:
  - MathML
  - MathML Reference
  - MathML:Element
  - MathML:General Layout Schemata
browser-compat: mathml.elements.mphantom
---

{{MathMLRef}}

The MathML `<mphantom>` element is rendered invisibly, but dimensions (such as height, width, and baseline position) are still kept.

## Attributes

This element accepts the [global MathML attributes](/en-US/docs/Web/MathML/Global_attributes).

## Examples

```html
<math display="block">
  <mrow>
    <mi>x</mi>
    <mo>+</mo>
    <mphantom>
      <mi>y</mi>
      <mo>+</mo>
    </mphantom>
    <mi>z</mi>
  </mrow>
</math>
```

{{ EmbedLiveSample('mphantom_example', 700, 200, "", "") }}

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{ MathMLElement("mspace") }}
- {{ MathMLElement("mpadded") }}

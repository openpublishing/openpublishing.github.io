---
layout: page
title: "Presentation"
category: cards
date: 2015-05-04 20:27:54
order: 200
---

This card provides tools for customizing the look and feel of your content. Custom styles are applied to all cards of a particular type or to cards having a certain name (using the [`name`][2] field).

Styles will be automatically adapted to the platform displaying your content.

### Example

````json
{
  "type": "Presentation",
  "version": 1,
  "styles": {
    "Paragraph": {
      "FONT_SIZE": "normal"
    },
    "welcome": {
      "FONT_SIZE": "large"
    }
  }
}
````

### Fields

| Field | Type | Default | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- | ------- |
| `styles` | map of `string` &rarr; [`Style`][1] | `{}` | The styles to apply. | String is a name (always lowercase) or a type (always capitalized). | 1 |

[1]: /cards/styles.html
[2]: /cards/common-fields.html

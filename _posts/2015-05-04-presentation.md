---
layout: page
title: "Presentation"
category: cards
date: 2015-05-04 20:27:54
order: 8
---

### Overview

Every card has a type (like `Section`, `Author`, or `List`) and, optionally, a name. You can associate a card or a name with a collection of styles to control your content's presentation.

### Example

````json
{
  "type": "presentation",
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

| Field | Type | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- |
| styles | map of string to [Style](#) | The styles to apply. | String is a name (always lowercase) or a type (always capitalized). | 1 |

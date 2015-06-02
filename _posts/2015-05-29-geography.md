---
layout: page
title: "Geography"
category: cards
date: 2015-05-29 19:59:04
order: 301
class: nested
---

This card provides a comprehensive structure for describing geographic data.

### Example

````json
{
  "type": "Geography",
  "geojson": {...}
}
````

### Fields

| Field | Type | Default | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- | ------- |
| `geojson` | [`GeoJSON`][1] | --- |  Geographic data serialized in the `GeoJSON` format. | Some [extensions][2] are supported. | 1 |

[1]: http://geojson.org/
[2]: /geojson

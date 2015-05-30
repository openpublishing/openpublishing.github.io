---
layout: page
title: "Geography"
category: cards
date: 2015-05-29 19:59:04
order: 301
class: nested
---

The `Geography` card provides a reasonable and simple format for describing geographic data and annotations.

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
| `geojson` | [`GeoJSON`][1] | --- |  Geographic data serialized in the `GeoJSON` format. | Some extensions are supported. | 1 |

[1]: http://geojson.org/

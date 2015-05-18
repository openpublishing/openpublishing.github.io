---
layout: page
title: "Publisher"
category: cards
date: 2015-05-04 19:48:35
order: 2
---

The identity (and reputation) of a content publisher is extremely important. This card captures essential information about a story's publisher.

### Example

````json
{
  "type": "publisher",
  "version": 1,
  "help": "http://format.example.com/openpub/version/1",
}
````

### Fields

| Field | Type | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- |
| home | string | The unique URL associated with this publisher. | Must be a valid URL. | 1 |
| name | string | The publisher's name. | Optional. | 1 |
| about | string | A brief note about the publication. | Optional. | 1 |

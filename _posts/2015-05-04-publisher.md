---
layout: page
title: "Publisher"
category: cards
date: 2015-05-04 19:48:35
order: 2
---

### Summary

The identity (and reputation) of a content publisher is extremely important. This card captures essential information about a story's publisher.

### Helpers

 - All helpers can import and export this card

### Platforms

 - Facebook

### Example

````json
{
  "type": "publisher",
  "version": 1,
  "help": "http://format.example.com/openpub/version/1",
}
````

### The Nitty Gritty

##### Version 1

| Field | Type | Purpose | Caveats |
| ----- | ---- | ------- | ------- |
| home | string | The unique URL associated with this publisher. | Must be a valid URL. |
| name | string | The publisher's name. | Optional. |
| about | string | A brief note about the publication. | Optional. |

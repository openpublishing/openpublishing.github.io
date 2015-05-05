---
layout: page
title: "Common Fields"
category: cards
date: 2015-05-04 22:53:35
order: 0
---

### Summary

Everything in `OpenPub` is a card -- even the top-level `Story`. While we've intentionally left things quite flexible, there are certain traits that all cards share.

### Helpers

 - All helpers support this card

### Platforms

 - All platforms support this card

### Example

````json
{
  "type": "example",
  "help": "http://format.example.com/openpub/version/1",
  "version": 1,
  "revision": 1
}
````

### The Nitty Gritty

##### Version 1

| Field | Type | Purpose | Caveats |
| ----- | ---- | ------- | ------- |
| type  | string | The type of this card. | Must always be lowercase and alphanumeric. |
| version | int | The version number of the card's format. ||
| help | string | A link to an explanation of this card. | Optional. Must be a valid URL. |
| revision | int | The revision number of the card's content. | Optional. Default is 1. |

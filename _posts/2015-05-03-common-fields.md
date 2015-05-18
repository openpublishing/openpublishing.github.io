---
layout: page
title: "Global"
category: cards
date: 2015-05-04 22:53:35
order: 0
---

Everything in `OpenPub` is a card -- even the top-level `Story`. While we've intentionally left things quite flexible, there are certain traits that all cards share.

### Example

````json
{
  "type": "example",
  "help": "http://format.example.com/openpub/version/1",
  "version": 1,
  "revision": 1
}
````

### Fields

| Field | Type | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- |
| type  | string | The type of this card. | Must always be lowercase and alphanumeric. | 1 |
| version | int | The version number of the card's format. || 1 |
| help | string | A link to an explanation of this card. | Optional. Must be a valid URL. | 1 |
| revision | int | The revision number of the card's content. | Optional. Default is 1. | 1 |
| parent | string | The name of the parent card, if any. | Optional. Default is none. | 1 |
| name | string | A name to associate with this card's content. | Optional. Doesn't have to be unique. | 1 |

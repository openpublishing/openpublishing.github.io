---
layout: page
title: "Cards"
category: cards
date: 2015-05-04 22:53:35
order: 0
---

Everything in `OpenPub` is a card -- even the top-level `Story`. While we've intentionally left things quite flexible, there are certain traits that all cards share.

**Note that a default value of `null` implies that the default is platform dependent.**

### Example

````json
{
  "type": "Example",
  "help": "http://format.example.com/openpub/version/1",
  "version": 1,
  "revision": 1
}
````

### Fields

| Field | Type | Default | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- | ------- |
| `type`  | `string` | --- | The type of this card. | Must always be camel-case and alphanumeric. | 1 |
| `version` | `number` | --- | The version of the format used for this card. || 1 |
| `help` | `string` | `null` | A link to an explanation of this card. | Must be a valid URL. | 1 |
| `revision` | `number` | `null` | The revision number of the card's content. || 1 |
| `name` | `string` | `null` | A name to associate with this card's content. | Doesn't have to be unique. Case insensitive. | 1 |

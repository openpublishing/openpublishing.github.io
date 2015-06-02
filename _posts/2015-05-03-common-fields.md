---
layout: page
title: "Cards"
category: cards
date: 2015-05-04 22:53:35
order: 0
---

Everything in `OpenPub` is represented as a card. Cards define their own arbitrary structure and can be combined and composed.

Each type of card is comprised of several fields which can store certain ranges of values (see below).

A value of `null` implies that the network is free to select a default value if one isn't specified.

### Example

````json
{
  "type": "Example",
  "help": "http://format.example.com/openpub/version/1",
  "version": 1,
  "revision": 1
}
````
### Field Types

| Type | Meaning | Example |
| ---- | ------- | ------- |
| `boolean` | A true or false value | `true` |
| `string` | Arbitrary text content | `"Hello, World!"` |
| `number` | A numeric value | `3.14` |
| `array` | An array of mixed types | `[1, "Test String", ["Another, "Array", { "A": "Map" }]]` |
| `map` | a mapping between keys and mixed values | `{ "name": "Brandon", "friends": [{ "name": "Sally" }]}`|
| `card` | an embedded `Card` of a certain type | `{ "type": "Profile", "service": "http://facebook.com" }` |

### Fields

| Field | Type | Default | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- | ------- |
| `type`  | `string` | --- | The type of this card. | Must always be camel-case and alphanumeric. | 1 |
| `version` | `number` | --- | The version number of the card's structure. || 1 |
| `revision` | `number` | `null` | The revision number of the card's content. || 1 |
| `help` | `string` | `null` | A link to an explanation of this card's structure. | Must be a valid URL. | 1 |
| `name` | `string` | `null` | A name to associate with this card's content. | Doesn't have to be unique. Case insensitive. | 1 |

[1]: /

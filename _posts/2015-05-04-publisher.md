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
  "type": "Publisher",
  "label": "Fluffington Post",
  "version": 1,
  "help": "http://format.example.com/openpub/version/1",
}
````

### Fields

| Field | Type | Default | Purpose | Caveats | Version |
| ----- | ---- | ------- | ------- | ------- | ------- |
| `home` | `string` | `null` | The unique URL associated with this publisher. | Must be a valid URL. | 1 |
| `label` | `string` | `null` | The publisher's display name. || 1 |
| `profile` | [`Profile`][1] | `{}` |  The publisher's online profile. | | 1 |
| `about` | `string` | `null` |  A brief note about the publication. | [Markdown][2] enabled. | 1 |

[1]: /cards/mention.html
[2]: /

---
layout: default
title: "Open Publishing"
---

<span style="font-weight: bold; color: red">NOTE: work in progress</span>

## **Open Publishing** is a set of principles,
### &nbsp;&nbsp;&nbsp;designed to help your content reach more people.

---

Web publishing has become *decentralized* --- our aim is to make decentralized publishing easier.

---

### Benefits

- Write once, publish everywhere
- Reach more people
- Load faster
- Increase engagement
- Easy to use

### Example

The following is how you would represent a story using `OpenPub` + `JSON`:

```json
{
  "type": "Story",
  "cards": [
    {
      "type": "Contributor",
      "label": "Brandon Diamond"
    },

    {
      "type": "Content",
      "title": "Hello World",
      "body": [
        {
          "type": "Section",
          "body": [{ "type": "Paragraph", "text": "**Hello, world!**" }]
        }
      ]
    }
  ]
}
```

Open Publishing is a way of specifying content and its metadata so that it can reach more people.

You can use as many or as few of its features as you like. Adding more information about your content allows you to better control how it flows across the web.


The community works together to build tools designed to make Open Publishing content more portable. You'll find a suite of tools available to help you work with `OpenPub`.

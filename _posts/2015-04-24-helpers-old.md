---
layout: page
title: "Helpers"
category: intro
order: 3
date: 2015-04-24 16:02:45
---

### How do Helpers Help?

With loads of formats and platforms and all their "endearing" quirks -- it can be tricky to build software that plays nicely with other people's content.

As a result, to truly **write once, read everywhere**, we must provide a bridge between the messy realities of actual content and our predictable, friendly `OpenPub` container. We need to transform stuff like `HTML`, `RSS`, `ATOM`, and `PDF` into `OpenPub` -- and back again. 

Rather than wrangling code to "scrape" all of these formats, we've joined forces to build a rich library of `helpers` that speak a common, intermediate tongue: `OpenPub`. The part we've defined is the interface -- how all the pieces fit together.

The rest is up to the community.

````html

In:		"<html><article><h1>This is an HTML document</h1></article></html>"
Out:	{ "type": "story", "cards": [ ... ]}

````

### True Portability

Many `helpers` also include the ability to _generate_ content from `OpenPub`. For instance, the `Markdown` helper can create `OpenPub` from `Markdown`... and `Markdown` from `OpenPub`.

````html

In:		{ "type": "story", "cards": [ ... ]}
Out:	"# This is a _Markdown_ document"

````

That's why we consider `OpenPub` an *intermediate format*: we can translate one format into `OpenPub` and then translate the resulting `OpenPub` into any other format. Even a bad one.

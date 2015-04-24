---
layout: page
title: "Import Content"
category: intro
order: 3
date: 2015-04-24 16:02:45
---

### The Web is Messy

With tons of formats and variations -- plus errors and stuff that doesn't make sense -- it can be tricky to build software that plays nicely with other people's content.

As a result, to achieve our goal of **write once, read everywhere**, we must build a bridge between the messy reality of real content and our predictable, friendly `openpub` container.

In other words, we need to transform stuff like `HTML5`, `RSS`, `ATOM`, `Markdown`, and so on into `openpub`. That's what an `importer` does.

````html

In:		"<html><article><h1>Arbitrary HTML</h1></article></html>"
Out:	{ "type": "story", "cards": [ "beautiful", "elegant", "metadata", "huzzah" ]}

````

### Your Life, Only Easier

Rather than writing -- or tracking down -- code to scrape these formats, we've joined forces to build a rich library of `importer`s that speak a common language, `OpenPub`.

As great as it is to have a consistently, reliable format to use in your own projects, most of the web doesn't speak `OpenPub` natively (... *yet*).

That's why we consider `OpenPub` an *intermediate format*: we can translate content into `OpenPub` and then translate the resulting `OpenPub` into yet a different format. To achive this, we use [Exporter][1].

[1]: /intro/exporters.html

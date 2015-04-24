---
layout: page
title: "Export Content"
category: intro
order: 4
date: 2015-04-24 16:02:50
---

### What Comes In, Must Come Out

What's the best thing about having a clean, reliable, and super charismatic intermediate format like `OpenPub`?  *Everything!*

But also: you can transform `OpenPub` into whatever format you like. This lets you use `OpenPub` content with services that speak a different format. Or language. Or whatever.

For instance, an `OpenPub` container with a `twitter` card and a `facebook` card can be used to automatically translate Twitter tags and OpenGraph tags.

````html
In:		{ "type": "story", "cards": [ { "type": "twitter", "username": "BillG" } ]}
Out:	<meta name="twitter:card" content="summary" /> <meta name="twitter:site" content="@BillG" />
````

By using `importer`s and `exporter`s, `OpenPub` becomes a canonical, simple representation of your content that can be **written once, and read everywhere**.

However, some services can speak `OpenPub` [natively][1].

[1]: /intro/supporters.html

---
layout: page
title: "Being Practical"
category: intro
order: 3
date: 2015-04-24 16:02:45
---

The web is home to many different formats adhearing to many different standards. In order to make content more accessible, we must integrate with existing tools and workflows.

### Importing and Exporting

`HTML` is used to organize much of the content on the web. Importing this content -- as well as content in other popular formats -- allows us to integrate with the web as it is _today_.

The community has assembled a toolbox of helpers that can transform between formats and assist with existing publishing flows. These helpers use `OpenPub` as a common tongue.

For instance, one helper might transform `HTML5` into `OpenPub`:

````html

In:		"<html><article><h1>This is an HTML document</h1></article></html>"
Out:	{ "type": "story", "cards": [ ... ]}

````

Whereas another might transform `OpenPub` into `Markdown`: 

````html

In:		{ "type": "story", "cards": [ ... ]}
Out:	"# This is a _Markdown_ document"

````

Taken together, you can use these tools to tune and optimize your content and prepare it to be published on the open web.

### Moving Forward

The list of helpers, libraries, and tools that support Open Publishing is always growing--- thanks largely to our wonderful community.

If you're a developer and would like to get involved, please visit the **Tools** section to learn more.

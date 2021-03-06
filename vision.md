---
layout: page
title: Vision
permalink: /vision/
---

# So, uh, why?

The future of publishing is open.

It's not tied to a specific format -- or a single organization. It belongs to the people.

The news must flow to the people and through the people. Publishers are no longer able to dictate where, how, and when content may be consumed. Those that try will fail.

Our mission is to advance the state of publishing -- to better inform the world through excavated knowledge and dynamic content. This mission hinges on our ability to embrace openness and transparency.

Control is not the solution. It is a temptation that masks the real opportunity before us: to liberate content. To elevate choice. To honor the generous and shun the stingy.

Indeed, the future is open and not limited to blobs of HTML or short snippets of text or images pinned to a virtual wall. One size does not fit all. Content should respond, evolve, change. Creators should create content once and that content should reach every corner of the open web.

## Philosophy

OpenPub is a collection of guidelines and best practices -- leveraging existing technologies -- that are designed to empower content creators on the open web. In so doing, OpenPub aims to facilitate collaboration between journalists, readers, commentators, and networks to promote the free flow of information.

OpenPub seeks to capture journalistic intent in such a way as can be translated to underlying networks. As such, OpenPub must be easy to evolve as the web grows and changes. A framework will be established for extending and modifying OpenPub with the goal of building an effective bridge between journalists and technologists

## Strategy

1. We collect content from any number of sources via harvesters (RSS, scraping, API calls, ...)
2. We plug said content into an OpenPub library
3. The library generates a consistent structure with as much data as could be gleaned from (1)
4. Each attribute is associated with a "quality" score to indicate confidence
5. There are no errors; only warnings. The common structure is annotated with these as well.

## The OpenPub Library

The library is the interesting part. It implements the current OpenPub guidelines and best practices:

We provide a versioned definition of a common structure. For each field, we specify a list of strategies for extracting the needed information. Each strategy has an associated quality score and is attempted in order of confidence.

The library applies each strategy sequentially to populate the common structure.

Strategies may depend on other strategies. As a result, we must ensure that dependent attributes are processed following the attributes that they depend on.

## Defining the Common Structure

The common structure is defined in a repository managed by a number of volunteers -- both technical and editorial. Changes must be proposed as pull requests. Data must not be removed; however, strategies can be re-arranged and scores re-evaluated.

All changes to the structure must be documented in the tutorial, in the spec, and in the code (which itself must be tested). The tutorial must reference the spec and the spec must reference the code.

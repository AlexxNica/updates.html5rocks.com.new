---
layout: post
title: "WebSockets updated to latest version in Chrome Canary"
description: ""
article:
  written_on: 2011-10-14
  updated_on: 2011-10-14
authors:
  - ericbidelman
tags:
  - announcement
  - websockets
permalink: /2011/10/WebSockets-updated-to-latest-version-in-Chrome-Canary
---
The WebSocket API has been rev'd to the latest version (13) in Chrome Canary. The developer-facing changes are very small, but are incompatible with the older version.

Here's the scoop:

* Change the origin header name: `Sec-WebSocket-Origin` -> `Origin`
* `Sec-WebSocket-Version` header value: 8 -> 13
---
title: "Analytics Token API returns HTTP 403 – request account/API activation check"
url: "https://community.upstox.com/t/analytics-token-api-returns-http-403-request-account-api-activation-check/17542#post_16"
date: "2026-09-18"
author: "@Anand_Sajankar Anand Sajankar"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @KULVINDER_55702715 this might be handy Market Data Feed V3 WebSocket returns 403 Forbidden on upgrade despite successful authorize Developer API Hi @SATYAM_2286284 Some common causes for 403 Forbidden during the WebSocket handshake are: Using the authorized_redirect_uri more than once. The URL returned by the authorize endpoint is single-use and a fresh one must be generated for every new WebSocket connection. Reusing an existing WebSocket connection without closing it properly before establishing a new one.

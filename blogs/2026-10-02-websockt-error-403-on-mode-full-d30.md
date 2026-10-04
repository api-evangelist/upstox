---
title: "Websockt error 403 on mode full_d30"
url: "https://community.upstox.com/t/websockt-error-403-on-mode-full-d30/17734#post_2"
date: "2026-10-02"
author: "@Anand_Sajankar Anand Sajankar"
feed_url: "https://community.upstox.com/posts.rss"
---
@MD_NIFAZ_56088338 Market Data Feed V3 WebSocket returns 403 Forbidden on upgrade despite successful authorize Developer API Hi @SATYAM_2286284 Some common causes for 403 Forbidden during the WebSocket handshake are: Using the authorized_redirect_uri more than once. The URL returned by the authorize endpoint is single-use and a fresh one must be generated for every new WebSocket connection. Reusing an existing WebSocket connection without closing it properly before establishing a new one.

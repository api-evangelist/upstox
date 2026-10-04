---
title: "Clarification required on Market Data Feed V3 for observation-only NIFTY options research"
url: "https://community.upstox.com/t/clarification-required-on-market-data-feed-v3-for-observation-only-nifty-options-research/17517#post_8"
date: "2026-09-24"
author: "@Hareesh_39024399 Hareesh"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi Upstox API Team, While testing our observation-only collector, a public GET request to the documented instrument URL returned HTTP 403 Forbidden : https://assets.upstox.com/market-quote/instruments/exchange/NSE.json.gz Attempt: 24 September 2026, approximately 11:49 AM IST . Our request configuration was: GET /market-quote/instruments/exchange/NSE.json.gz HTTP/1.1 Host: assets.upstox.com Connection: close Accept: application/json Accept-Encoding: gzip No User-Agent, authentication header, cookies or proxy was used. TLS certificate and hostname verification were enabled.

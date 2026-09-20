---
title: "Websocket 403 error"
url: "https://community.upstox.com/t/websocket-403-error/17576#post_1"
date: "2026-09-18"
author: "@VIJAY_33439908 VIJAY"
feed_url: "https://community.upstox.com/posts.rss"
---
I am an Upstox Plus user and am unable to establish a Market Data Feed V3 WebSocket connection. REST API authentication and other REST market-data APIs are working correctly. I tested the WebSocket independently of my application using the official Upstox Python SDK: upstox-python-sdk: 2.30.0 MarketDataStreamerV3 Only one instrument: NSE_INDEX|Nifty 50 Mode: full Only one WebSocket connection The connection fails during the WebSocket handshake: Handshake status 403 Forbidden I also tested the V3 market-data authorization endpoint separately.

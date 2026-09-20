---
title: "Market data feed via websocket: How many price updates per second?"
url: "https://community.upstox.com/t/market-data-feed-via-websocket-how-many-price-updates-per-second/17571#post_4"
date: "2026-09-18"
author: "@Ushnota Ushnota Paul"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @Kislay , The Market Data Feed V3 does not currently specify a fixed maximum updates-per-second limit for an individual instrument. Updates are streamed in real time as market data changes, so the frequency can vary depending on market activity. The feed is event-driven rather than based on a fixed updates-per-second interval.

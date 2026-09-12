---
title: "Nifty_50,Banknifty,Sensex, Live option Chain Data and Historical Data need"
url: "https://community.upstox.com/t/nifty-50-banknifty-sensex-live-option-chain-data-and-historical-data-need/17340#post_2"
date: "2026-09-04"
author: "@Ushnota Ushnota Paul"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @NAINIT_29217312 , For a beginner, you can build this in steps: first use the Option Chain API to get Nifty 50/Bank Nifty/Sensex option contracts and their LTP, OI, bid/ask and Greeks. For live spot and option updates, use Market Data Feed V3 WebSocket; it supports real-time streaming and requires Protobuf decoding in Node.js. For historical analysis/backtesting, use Historical Candle Data V3, which supports minute, hour, day, week and month intervals.

---
title: "Subject: Upstox Modify Order V3 – SL-L to MARKET Conversion, Partial Fills and Order-State Confirmation"
url: "https://community.upstox.com/t/subject-upstox-modify-order-v3-sl-l-to-market-conversion-partial-fills-and-order-state-confirmation/17835#post_1"
date: "2026-10-09"
author: "@VIKAS_BALK_4404078 VIKAS BALKRISHNA"
feed_url: "https://community.upstox.com/posts.rss"
---
Hello Upstox Developer Team, We are finalizing the design of a safety-critical intraday NIFTY options trading system. Our system places a protective SELL Stop Loss Limit (SL-L) order after a confirmed BUY fill. At a defined profit target or mandatory intraday exit cutoff, we intend to modify the SAME existing protective SELL order from SL-L to MARKET using Modify Order V3, without placing a separate SELL order.

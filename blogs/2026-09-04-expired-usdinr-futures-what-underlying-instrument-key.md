---
title: "Expired USDINR futures — what underlying instrument_key should be used?"
url: "https://community.upstox.com/t/expired-usdinr-futures-what-underlying-instrument-key-should-be-used/17334#post_1"
date: "2026-09-04"
author: "@V_55256993 V"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi Upstox API team, I am using Upstox Plus Expired Instruments APIs for historical futures research. Current USDINR futures are resolved successfully by Instrument Search: segment: NCD_FO trading_symbol: USDINR FUT 28 SEP 26 instrument_key: NCD_FO|1769 However, the Instrument Search response does not provide a usable underlying_key for USDINR. I need the correct underlying instrument_key for: /v2/expired-instruments/future/contract I tested: instrument_key=NCD_FO|USDINR and received: UDAPI100011 — Invalid Instrument key Could you please confirm: What exact underlying instrument_key should be u

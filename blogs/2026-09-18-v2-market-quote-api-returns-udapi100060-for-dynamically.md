---
title: "V2 Market Quote API Returns UDAPI100060 for Dynamically Resolved NIFTY Instrument"
url: "https://community.upstox.com/t/v2-market-quote-api-returns-udapi100060-for-dynamically-resolved-nifty-instrument/17580#post_1"
date: "2026-09-18"
author: "@VIJAY_4485871 VIJAY"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi Upstox Team, Thank you for looking into my V3 WebSocket market-data issue. During our separate paper-trading execution integration test, we identified another issue that may require your verification. Instrument dynamically resolved from the Upstox BOD master: Underlying: NIFTY Expiry: 22 September 2026 Strike: 23250 Option type: CE Trading symbol: NIFTY 23250 CE 22 SEP 26 Instrument key: NSE_FO|56983 Lot size: 65 Our execution adapter attempted to retrieve the reference price using: GET /v2/market-quote/ohlc/NSE_FO%7C56983 The API returned: { "status": "error", "errors": [ { "errorCode": "

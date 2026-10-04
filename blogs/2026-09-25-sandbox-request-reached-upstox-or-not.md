---
title: "Sandbox request reached Upstox or not?"
url: "https://community.upstox.com/t/sandbox-request-reached-upstox-or-not/17656#post_1"
date: "2026-09-25"
author: "@SANKET_57566704 SANKET"
feed_url: "https://community.upstox.com/posts.rss"
---
I made one Sandbox request using upstox-python-sdk 2.30.0 with OrderApiV3.place_order(). The request was for NSE_EQ|INE669E01016, BUY 1, LIMIT at ₹9.12, DAY, tag “string.” The client reported the outcome as unknown and returned no order ID or HTTP status. A subsequent Sandbox order-book lookup failed locally because the installed SDK’s Sandbox allowlist does not include GET /v2/order/retrieve-all.

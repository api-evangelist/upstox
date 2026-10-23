---
title: "Historical expired-options API returning 401 despite token update"
url: "https://community.upstox.com/t/historical-expired-options-api-returning-401-despite-token-update/17955#post_1"
date: "2026-10-16"
author: "@VIJAY_4485871 VIJAY"
feed_url: "https://community.upstox.com/posts.rss"
---
Hello Upstox Support, I am validating historical options-market data access for a research and paper-trading application. Our read-only requests to the /v2/expired-instruments/* API endpoints consistently return HTTP 401 with the response: “Invalid token used to access API” We have updated the access token and repeated the test, but the issue persists. Live option-chain access does not establish historical expired-contract access.

---
title: "App scope issue: LTP/market-quote returns 401 UDAPI100050"
url: "https://community.upstox.com/t/app-scope-issue-ltp-market-quote-returns-401-udapi100050/17027#post_2"
date: "2026-10-09"
author: "@Ketan Ketan Gupta"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @SAYYED_FAR_1352845 , There are no app scopes to enable. Market Quote and LTP are available to every app without any extra permission. The Historical Candle API doesn’t validate the token, so it working with your token doesn’t mean the token is valid.

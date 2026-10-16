---
title: "Error while fetching 1 min data"
url: "https://community.upstox.com/t/error-while-fetching-1-min-data/16997#post_2"
date: "2026-10-08"
author: "@Ketan Ketan Gupta"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @Manju_48285748 , UDAPI100060 means the URL path is wrong. The Historical Candle V3 API takes its parameters in the path , not as query parameters, in the order /{instrument_key}/{unit}/{interval}/{to_date}/{from_date} . Also URL-encode the | as %7C : curl --location 'https://api.upstox.com/v3/historical-candle/BSE_EQ%7CINE016A01026/minutes/1/2026-08-06/2026-07-06' \ --header 'Accept: application/json' \ --header 'Authorization: Bearer ' For 1-minute data, keep each request to a maximum range of one month.

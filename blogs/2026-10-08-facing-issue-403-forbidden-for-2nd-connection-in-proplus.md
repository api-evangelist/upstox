---
title: "Facing Issue 403 Forbidden For 2ND Connection In ProPlus Plan"
url: "https://community.upstox.com/t/facing-issue-403-forbidden-for-2nd-connection-in-proplus-plan/17634#post_2"
date: "2026-10-08"
author: "@Ketan Ketan Gupta"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @AARYAN_48934173 , Sorry for the delayed response. With Upstox Plus you can have up to 5 concurrent connections , and the Analytics Token supports WebSocket connections, so your test of two connections with one token is valid. When a second connection gets 403 within the limit, it’s usually because sockets from earlier runs are still counted.

---
title: "Api token error"
url: "https://community.upstox.com/t/api-token-error/17245#post_2"
date: "2026-10-08"
author: "@Ketan Ketan Gupta"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @AYUSH_SING_12934825 , There’s no account-level restriction or separate enablement for the Market Data Feed, and static IP doesn’t apply to it. A 403 during the WebSocket handshake usually means one of these: The authorized_redirect_uri was reused. It’s single-use, so call the authorize API again before every connection and reconnect.

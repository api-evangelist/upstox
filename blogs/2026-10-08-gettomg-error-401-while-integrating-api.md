---
title: "Gettomg Error 401 while integrating API"
url: "https://community.upstox.com/t/gettomg-error-401-while-integrating-api/17064#post_2"
date: "2026-10-08"
author: "@Ketan Ketan Gupta"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @VIKAS_KUMA_1103191 , A 401 means the token sent with the request isn’t valid. The usual causes: Header format: it must be exactly Authorization: Bearer . Don’t send the auth code or API key in its place.

---
title: "Add Support for X-Forwarded-For header in API"
url: "https://community.upstox.com/t/add-support-for-x-forwarded-for-header-in-api/17767#post_2"
date: "2026-10-08"
author: "@Ketan Ketan Gupta"
feed_url: "https://community.upstox.com/posts.rss"
---
Hi @hirak X-Forwarded-For: We don’t consider the X-Forwarded-For header. The request origin IP is taken at our CDN level, so API users can’t forge it. Trusting a client-supplied header would let anyone pass the registered IP and defeat the purpose of the static IP requirement.

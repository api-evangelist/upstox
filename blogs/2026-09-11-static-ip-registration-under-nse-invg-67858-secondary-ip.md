---
title: "Static IP registration under NSE/INVG/67858: secondary IP, weekly change limit, and IPv6 support"
url: "https://community.upstox.com/t/static-ip-registration-under-nse-invg-67858-secondary-ip-weekly-change-limit-and-ipv6-support/17453#post_2"
date: "2026-09-11"
author: "@Stretus stretus"
feed_url: "https://community.upstox.com/posts.rss"
---
A few specifics that trip people up on this, all of them from NSE/INVG/67858 (5 May 2025): You register a static IP with the broker, and you can register a secondary for redundancy. That second part is the one people miss and it is the intended answer to failover. Mapped addresses can be updated at most once per calendar week.

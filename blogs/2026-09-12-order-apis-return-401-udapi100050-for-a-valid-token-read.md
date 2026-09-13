---
title: "Order APIs return 401 UDAPI100050 for a valid token — read/margin APIs work, static IP registered + matching, sandbox orders work"
url: "https://community.upstox.com/t/order-apis-return-401-udapi100050-for-a-valid-token-read-margin-apis-work-static-ip-registered-matching-sandbox-orders-work/17290#post_7"
date: "2026-09-12"
author: "@SAMPAT_55142206 SAMPAT"
feed_url: "https://community.upstox.com/posts.rss"
---
@Anand_Sajankar Confirmed it is not an old/revoked token. For reqid 063468b3-c4c7-4dae-a161-83793d783060 (12-Sep-2026 08:29:01 UTC), the token we sent is the one minted 74s earlier at login (08:27:47 UTC): JWT iat=1789201667 (= that login time), exp=1789250400 , and its fingerprint matches the access_token from that login’s token-exchange response. Decoded JWT claims: {"sub":"5QC7BH","isMultiClient":false,"isPlusPlan":true,"iat":1789201667,"iss":"udapi-gateway-service","exp":1789250400} .

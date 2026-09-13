---
title: "ConnectTimeoutError on api-hft.upstox.com over IPv6 network despite IP Whitelisting"
url: "https://community.upstox.com/t/connecttimeouterror-on-api-hft-upstox-com-over-ipv6-network-despite-ip-whitelisting/17392#post_5"
date: "2026-09-10"
author: "@KBS KAMLESH"
feed_url: "https://community.upstox.com/posts.rss"
---
Dear @Anand_Sajankar nslookup on IPv4 resolve but IPv6 not Resolve , That reason AF_INET6 desable code as below for that def allowed_gai_family(): return socket.AF_INET6 connection.allowed_gai_family = allowed_gai_family Log Below kb@kb-Desktop:~$ nslookup assets.upstox.com Server: 127.0.0.53 Address: 127.0.0.53#53 Non-authoritative answer: Name: assets.upstox.com Address: 18.67.195.40 Name: assets.upstox.com Address: 18.67.195.53 Name: assets.upstox.com Address: 18.67.195.118 Name: assets.upstox.com Address: 18.67.195.9 kb@kb-Desktop:~$ nslookup -type=AAAA assets.upstox.com 2405:201:2005:58ec

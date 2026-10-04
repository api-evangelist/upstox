---
title: "UDAPI1161 \"MCX API orders are temporarily disabled\" — order placement via API"
url: "https://community.upstox.com/t/udapi1161-mcx-api-orders-are-temporarily-disabled-order-placement-via-api/17637#post_1"
date: "2026-09-23"
author: "@Prajakta_50775820 Prajakta"
feed_url: "https://community.upstox.com/posts.rss"
---
Every MCX order placed through the API on 23 Sep 2026, whatever the order type, price, contract or API version. All were refused with HTTP 400: {“status”:“error”,“errors”:[{“errorCode”:“UDAPI1161”, “message”:“MCX API orders are temporarily disabled. Meanwhile, place commodity orders on NSE (NSCOM).”, “propertyPath”:“instrument_key”,“invalidValue”:“MCX_FO|580776”}]} Request body for the order: {“quantity”:1,“product”:“I”,“validity”:“DAY”,“price”:479.8,“tag”:“nearmktlimit”, “instrument_token”:“MCX_FO|580776”,“order_type”:“LIMIT”,“transaction_type”:“BUY”, “disclosed_quantity”:0,“trigger_price”:0,

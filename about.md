---
layout: post
title: About
---

# scoop

A simple clean newsletter delivery service in rust.

Public Endpoints:

- /
- /health_check
- /login
- /subscriptions
- /admin/dashboard
- /admin/logout
- /admin/newsletters
- /admin/password

# Features

- Fault Tolerant: Best effort email delivery
- Concurrent Proof: Retries will not trigger duplicate newsletter entries
- Redis Store for fast session interface
- Salient Tracing and Logging 

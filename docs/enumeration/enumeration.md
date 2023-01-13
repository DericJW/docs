---
layout: default
title: Enumeration
nav_order: 3
has_children: false
permalink: /enumeration
---

# Ping Sweep

## Linux

```
for i in $(seq 1 254); do (ping -c 1 172.16.1.${i} | grep "bytes from" &); done;
```
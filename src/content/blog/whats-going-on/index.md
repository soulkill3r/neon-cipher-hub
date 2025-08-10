---
title: "What's is going on ?"
publishDate: 2025-08-10
updatedDate: 2025-08-10
description: 'I had no choice'
tags:
  - tech
  - homelab
language: 'English'
heroImage: { src: './thumbnail.jpg', color: '#D58388' }
---

# What is going on? 🏠→🏠

Hey everyone! 

It's been a while since my last post (the hello world post 🤣), I've just moved to a new place, and with it comes the perfect opportunity (read: necessity) to completely rethink my homelab architecture. 

You know that feeling when you unpack boxes and find cables you forgot existed? Yeah, that's been my life for the past few weeks.

## The Plot Twist: CGNAT 😱

The new place came with a surprise: Carrier-Grade NAT. For those unfamiliar, CGNAT basically means my ISP put me behind *another* NAT layer, making port forwarding impossible. No more simple `192.168.1.x:8096` access from outside. 

This forced me to get creative, and honestly? It might be the best thing that happened to my homelab.

## The Current State of Chaos

Right now, half my servers are in boxes, the other half are running on a temporary setup that would make r/homelab cry. But here's what I'm building towards:

### The Stack Evolution

**Before (The "It Works" Era):**
- Nginx Proxy Manager (clicking through UI like a caveman)
- Static IPs everywhere
- No documentation
- "I'll backup next week" syndrome

**After (The GitOps Awakening):**
- Everything as Code with Komodo
- NetBird for secure remote access (bye bye, port forwarding!)
- Traefik with automatic service discovery
- GitHub as the single source of truth
- A new VPS

### And.. when ?

Well.. I'm working on it, I will share you more of my journey during the following weeks.

See you next time !
_Reho_
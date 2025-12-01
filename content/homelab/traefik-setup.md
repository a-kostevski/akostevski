---
title: "Traefik Setup"
date: 2024-01-20
description: "Setting up Traefik as a reverse proxy"
tags: ["traefik", "reverse-proxy", "homelab"]
---

Traefik is a modern reverse proxy that integrates well with Docker.

## Prerequisites

Familiarity with {{< wikilink "docker-basics" "Docker fundamentals" >}} is recommended.

## Configuration

```yaml
# docker-compose.yml
version: "3"
services:
  traefik:
    image: traefik:v3
    ports:
      - "80:80"
      - "443:443"
```

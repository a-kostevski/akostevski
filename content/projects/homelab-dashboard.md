---
title: "Homelab Dashboard"
description: "A unified dashboard for monitoring and managing self-hosted services"
date: 2024-11-15
featured: true
tech:
  - Go
  - React
  - Docker
  - Prometheus
category: "Infrastructure"
github: "https://github.com/a-kostevski/homelab-dashboard"
status: "active"
---

## Overview

A comprehensive dashboard for monitoring and managing homelab infrastructure. Built to provide real-time insights into service health, resource usage, and system metrics.

## Features

- **Real-time Monitoring**: Live updates on service status and resource utilization
- **Docker Integration**: Direct container management and log viewing
- **Alerting System**: Configurable alerts via Discord, Slack, or email
- **Clean UI**: Modern, responsive interface with dark mode support

## Architecture

The dashboard consists of three main components:

1. **Backend API** (Go): Handles data collection and serves the REST API
2. **Frontend** (React): Provides the user interface
3. **Prometheus**: Metrics collection and storage

## Getting Started

```bash
docker-compose up -d
```

Visit `http://localhost:3000` to access the dashboard.

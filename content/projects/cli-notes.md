---
title: "CLI Notes"
description: "A fast, terminal-based note-taking app with fuzzy search"
date: 2024-09-20
featured: true
tech:
  - Rust
  - SQLite
  - TUI
category: "Tools"
github: "https://github.com/a-kostevski/cli-notes"
status: "completed"
---

## Overview

A blazing-fast terminal note-taking application designed for developers who live in the command line. Features instant fuzzy search across thousands of notes.

## Features

- **Instant Search**: Fuzzy search across all notes in milliseconds
- **Markdown Support**: Full markdown rendering in the terminal
- **Tags & Categories**: Organize notes with tags
- **Sync**: Optional sync with Git repositories
- **Vim Keybindings**: Navigate efficiently with familiar shortcuts

## Installation

```bash
cargo install cli-notes
```

## Usage

```bash
# Create a new note
notes new "Meeting notes"

# Search notes
notes search "docker"

# List all notes
notes list
```

## Performance

Benchmarks on a collection of 10,000 notes:

| Operation | Time |
|-----------|------|
| Search | 12ms |
| Open note | 3ms |
| Create note | 8ms |

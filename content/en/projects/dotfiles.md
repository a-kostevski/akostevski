---
title: "Dotfiles"
description: "My personal development environment configuration"
date: 2024-06-10
tech:
  - Neovim
  - Zsh
  - Tmux
  - Ansible
category: "Configuration"
github: "https://github.com/a-kostevski/dotfiles"
status: "active"
draft: true
---

## Overview

A carefully crafted collection of dotfiles and configurations for a productive development environment. Automated setup with Ansible for quick deployment on new machines.

## Included Configurations

- **Neovim**: LSP-powered IDE experience with custom keybindings
- **Zsh**: Fast prompt with syntax highlighting and autosuggestions
- **Tmux**: Session management with intuitive keybindings
- **Git**: Aliases and configuration for efficient workflows
- **Alacritty**: GPU-accelerated terminal configuration

## Quick Start

```bash
git clone https://github.com/a-kostevski/dotfiles ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## Structure

```
~/.dotfiles/
├── ansible/          # Automated setup playbooks
├── nvim/            # Neovim configuration
├── zsh/             # Zsh configuration
├── tmux/            # Tmux configuration
└── install.sh       # Main installation script
```

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a hackathon starter template with a universal devcontainer configuration supporting multiple languages and frameworks.

## Development Environment

The project uses VS Code Dev Containers with the Microsoft Universal image (`mcr.microsoft.com/devcontainers/universal:2`).

### Supported Languages/Frameworks

- **TypeScript/JavaScript**: TypeScript, ts-node, yarn, pnpm available globally
- **Ruby**: Ruby with Bundler
- **Python**: pip (upgraded)
- **Go**: Go toolchain
- **Java**: JDK available

### Pre-configured Ports

- 3000: Rails/Node/Next.js
- 5000: Python Flask
- 8000: Python Django/FastAPI
- 8080: Java/Go

## Quick Start Commands

```bash
# TypeScript - run directly without compilation
ts-node <filename>.ts

# Ruby
bundle install
bundle exec ruby <filename>.rb

# Python
pip install -r requirements.txt
python <filename>.py

# Node.js package managers
yarn install  # or pnpm install
```

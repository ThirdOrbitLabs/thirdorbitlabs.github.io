# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Important Workflow Rules

**Never commit without explicit user request.** The user always wants to test and review code changes before committing.

## Repository Overview

This is the Third Orbit Labs website repository (thirdorbitlabs.com), hosted via GitHub Pages. It's a static site with no build process or dependencies.

**Company**: Third Orbit Labs - Indie studio building mobile apps, micro-SaaS tools, and immersive Roblox experiences.

## Repository Structure

- `index.html` - Main landing page
- `CNAME` - Custom domain configuration for GitHub Pages
- Image assets (PNG, JPG)

## Development Workflow

### Viewing Changes Locally

Since this is a static site with no build step, you can:
1. Open HTML files directly in a browser
2. Use a simple HTTP server: `python3 -m http.server 8000`

### Deployment

This repository uses GitHub Pages. Changes pushed to the `main` branch are automatically deployed to thirdorbitlabs.com.

## Design System

The landing page uses a custom dark theme with:
- **Primary accent**: Teal (`#2dd4bf`) with glow effects
- **Typography**: DM Sans (body), JetBrains Mono (code)
- **Background**: Deep dark blue-black palette (`#050a0e`, `#070d12`)
- **Glass morphism**: Card components with semi-transparent backgrounds and subtle borders

When making changes to the HTML, maintain consistency with the existing CSS custom properties defined in `:root`.

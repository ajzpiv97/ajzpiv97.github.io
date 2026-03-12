# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages personal website hosted at `https://ajzpiv97.github.io`. The site is served directly from the `master` branch root by GitHub Pages.

## Deployment

Pushing to the `master` branch automatically deploys to GitHub Pages. No build step is required for static HTML/CSS/JS. If a static site generator is added (e.g., Jekyll, Hugo, Eleventy), update this file with the relevant build commands.

## GitHub Pages Conventions

- `index.html` (or `index.md` for Jekyll) at the root is the homepage.
- Jekyll is supported natively by GitHub Pages — any `_config.yml` at the root activates it. If Jekyll is not desired, add a `.nojekyll` file at the root.
- Custom domain configuration goes in a `CNAME` file at the root.

## Pages

| URL | File | Description |
|-----|------|-------------|
| `/shoulder-rehab/` | `shoulder-rehab/index.html` | Bilateral Shoulder Rehab interactive protocol app (self-contained HTML, dark theme, Google Fonts CDN) |

The root (`/`) has no homepage yet — add `index.html` at the repo root when ready.

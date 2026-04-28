# upanddown-web

Public-facing website for **Up & Down: Golf Bets** — hosted via GitHub Pages on the custom domain `playupanddown.com`.

## What this repo contains

- `index.html` — landing page (renders at `https://playupanddown.com/`)
- `privacy/index.html` — Privacy Policy (renders at `https://playupanddown.com/privacy`)
- `terms/index.html` — Terms of Service (renders at `https://playupanddown.com/terms`)
- `style.css` — shared stylesheet for all pages
- `CNAME` — tells GitHub Pages which custom domain to use

## How it's hosted

This repository is published via **GitHub Pages** (free tier, public repo).

- Branch: `main`
- Folder: root (`/`)
- Custom domain: `playupanddown.com` (configured in repo Settings → Pages and via DNS records on Cloudflare)
- HTTPS: enforced (auto-issued SSL certificate via Let's Encrypt)

## Editing the legal docs

The HTML files are the canonical source. If the source Word docs are ever updated, regenerate the corresponding `index.html` files in the `privacy/` and `terms/` folders, commit, and push — GitHub Pages will redeploy automatically within 1–2 minutes.

## Contact

Hadyn Renfort — `hadyn.upanddown@gmail.com`

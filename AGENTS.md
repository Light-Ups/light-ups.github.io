# LightUps landing page — agent guidelines

## What this repo is

A single-page marketing site for the [LightUps](https://light-ups.github.io) UPS monitoring ecosystem.  
No frameworks, no build step, no package manager, no CI.

## Structure

- `index.html` — the only page (all sections inline)
- `css/style.css` — single stylesheet (Inter font via Google Fonts)
- `README.md` — short description, keep in sync with the site tagline
- `googlea022fb39277bbf56.html` — Google Search Console verification, do not delete

## How to publish

Push to `main` — GitHub Pages serves the root automatically.  
No build or deploy command needed. There is no CNAME; the site uses the default `<org>.github.io` domain.

## Style conventions

- Dark theme (`#0d0d12` background), amber accent (`#f59e0b`)
- CSS uses `@import` for fonts (no JS font loading)
- No class-based CSS framework; all styles are hand-written in `style.css`
- No `<script>` tags — zero JavaScript

## What not to do

- Do not add a package manager, build tool, or JS framework
- Do not add JavaScript unless explicitly asked — the site is intentionally JS-free
- Do not add `<link rel="icon">` pointing to an external path; the inline SVG data-URI favicon is intentional
- Do not remove or alter `googlea022fb39277bbf56.html`

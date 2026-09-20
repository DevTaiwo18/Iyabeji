# Iyabeji Groundnut & Egusi Ventures — Website

A single-page, mobile-responsive business website for Iyabeji Groundnut and Egusi Ventures (Block 550, Bodija Market, Ibadan, Oyo State).

## Files

- `index.html` — the entire site (self-contained: HTML + CSS, no build step)
- `images/` — drop the two product photos here (see below)

## Adding the photos

The page is already wired to load these two files. Drop them into the `images/` folder using these exact names, and the site will pick them up automatically — no code changes needed:

| File | Used for |
|---|---|
| `images/groundnut-bags.jpg` | Hero photo + the Groundnut product card (stacked bags photo) |
| `images/egusi-tray.jpg` | About section photo + the Egusi product card (seed tray photo) |

Until those files exist, the page shows a warm placeholder in their place, so it's safe to open right now.

## Viewing the site

No server or build step required — just open `index.html` in a browser:

```bash
open index.html
```

Or, for local development with a live server:

```bash
npx serve .
```

## Deploying

This is a static site — it can be hosted as-is on any static host (Netlify, Vercel, GitHub Pages, etc.) by pointing it at this folder. No `VITE_` env vars or build config needed.

## Content reference

- **Business:** Iyabeji Groundnut and Egusi Ventures — wholesale & retail trader, est. 1999 (26 years)
- **Address:** Block 550, Bodija Market, Ibadan, Oyo State, Nigeria
- **Phone:** 0805 452 4427
- **Email:** selimotikeowo@gmail.com

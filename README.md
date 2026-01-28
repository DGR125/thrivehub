# ThriveHub (V5) — Blended List

This version merges **Categories** and **Additional Resources** into **one searchable list**.

## Publish in 3 steps
1. Upload **all files in this folder** to the **root** of your `thrivehub` repo (top level). Do not nest in a subfolder.
2. Go to **Settings → Pages** → Source: `main` / Folder: `/root`. Save.
3. Wait ~60s → open `https://DGR125.github.io/thrivehub/` (try a private window).

## What’s inside
- `index.html` — the blended UI (search + tag chips)
- `assets/data.json` — the items; edit this to add or remove entries
- `one-pagers/` — quick printable HTML one‑pagers
- `.nojekyll`, `404.html`, `health-check.html` — stability helpers for GitHub Pages

## Edit content (so easy!)
- To **add a new link or strategy**, open `assets/data.json` and add a new object with:
{
  "title": "Name of thing",
  "type": "resource" or "strategy",
  "desc": "What it is / how to use",
  "href": "https://...",  
  "tags": ["autism", "adhd", "trauma", "eal-d", "assistive", "wellbeing", "online-safety", "evidence", "universal"]
}
- Save and commit — the page updates itself.

Happy teaching! ✨

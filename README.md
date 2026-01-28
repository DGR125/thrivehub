# ThriveHub (V5.1) — Resources + Useful Links (no categories)

**What changed?**
- Removed category tiles entirely. The home page now shows:
  - **About our team** (Wave One)
  - **Useful Links** (YouTube playlist, Blog, and Teams links)
  - **Resources**: one searchable list with tag chips (Autism, ADHD, EAL/D, etc.)
  - **One‑pagers** (printable)

## Publish in 3 steps
1. Upload all files to the **root** of your `thrivehub` repo (do not nest in a folder).
2. **Settings → Pages** → Source: `main` / Folder: `/root` → Save.
3. Wait ~60s, open `https://DGR125.github.io/thrivehub/` (try a private window).

## Edit content
- **Useful Links**: edit `/assets/useful-links.json`. Replace the three `#REPLACE_WITH_TEAMS_...` placeholders with your actual Microsoft Teams invite URLs.
- **Resources**: edit `/assets/resources.json`. Each item needs `title`, `desc`, `href`, and `tags`.
- Save & commit — the page updates automatically.

Happy teaching! ✨

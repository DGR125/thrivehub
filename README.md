# ThriveHub (V4) — Quick Start & Troubleshooting

**Public URL:** `https://DGR125.github.io/thrivehub/`

## New in V4
- Additional Resources **embedded on home** with live filter (kept legacy /resources/)
- **Accessibility:** skip link, ARIA roles/labels, focus outlines, higher contrast
- **Print buttons** for each category → opens one‑pager
- **Blog panel** tries to auto‑list latest 3 posts from WordPress (with graceful fallback)
- Added **404.html** to redirect back to the home page if users hit a bad path

## Publish (GitHub Pages)
1. Repo name must be **`thrivehub`** under `DGR125`.
2. Upload all files to the **repo root** (top level). `index.html` must be in the root.
3. Go to **Settings → Pages**:
   - **Source:** `main`
   - **Folder:** `/root`
4. Wait 30–60 seconds, then open `https://DGR125.github.io/thrivehub/` (try a private/incognito window).

## If it "isn’t loading"
- Ensure the repo is **Public** (unless your plan supports private Pages).
- Confirm `index.html` is at **root** (not inside a folder like `/thrivehub_site_v4/`).
- Check **Settings → Pages** really shows a green banner with your site URL.
- If you used a custom domain previously, clear it under Pages.
- Case matters in file names/paths; keep the URL path as `/thrivehub/` exactly.
- Give it a minute after changes; then **hard refresh** (`Ctrl/Cmd+Shift+R`).

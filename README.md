
# ThriveHub – V5.9h (Branch Deploy)

This build is configured for **GitHub Pages → Deploy from a branch** (no Actions).

## How to publish (branch mode)
1. Go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. **Branch:** `main`  •  **Folder:** `/root`  → **Save`**.
4. Upload the **contents** of this folder to the **repo root** (not the ZIP).
5. Open the site in a **private/incognito** window: `https://<username>.github.io/thrivehub/`.

## Why branch mode?
- For static sites, GitHub recommends publishing from a **branch/folder** when no build step is needed. It removes the dependency on Actions runners and avoids concurrency cancellations. (See GitHub Docs: *Configuring a publishing source for your GitHub Pages site*.)

## Verify Cloudflare Web Analytics
- View source and search for `static.cloudflareinsights.com/beacon.min.js`. The snippet is injected just before `</body>`.



# ThriveHub — quick publish (branch deploy)

1. Go to **Settings → Pages**
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
   - Click **Save**.

2. In the repo root, ensure these files exist:
```
index.html
library.html
404.html
.nojekyll
assets/
  thrivehub-logo.png
  favicon.png
```

3. Open the site in a private/incognito window:
   - `https://dgr125.github.io/thrivehub/`
   - `https://dgr125.github.io/thrivehub/library.html`

Cloudflare Web Analytics is embedded just before `</body>` on both pages using your token `4be9740951c64b459e4609a0c51af0b1`.

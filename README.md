
it commit --allow-empty -m "chore: retrigger pages"
git push

# ThriveHub – V5.9g (Full library fixed + last updated + analytics)

- Restores the **full library** content on `library.html` (no trimming).
- Adds **last updated** badge (Home hero): 29 January 2026.
- Cloudflare Web Analytics beacon (your token) is embedded **before </body>** on both pages.

## Publish
1) Upload the **contents** of this folder to the **repo root**.
2) Settings → Pages → Source: Deploy from a branch; Branch: main; Folder: /root → Save.
3) Open the site in a private/incognito window to bypass cache.

## Verify analytics locally in the page source
- View source of the deployed page and search for `static.cloudflareinsights.com/beacon.min.js`.

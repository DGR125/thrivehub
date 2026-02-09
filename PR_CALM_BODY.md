
### ThriveHub: Calm Space — fix buttons, reliable audio, and fullscreen

**Summary**
- Replaces `resources.html` with a dependency‑free page:
  - **Buttons** use data‑attributes + delegated JS listeners (no null refs / timing issues).
  - **Brown noise** generated with **WebAudio** only after a **user click** (complies with modern autoplay policies).
  - **Fullscreen Calm** panel with Esc/click to exit; includes webkit/ms fallbacks.
- Nav uses **relative links** and marks Calm Space as active.

**Files changed**
- `resources.html` only.

**Post‑merge**
- Confirm via cache‑bust: `…/thrivehub/resources.html?v=v40`
- If Pages is publishing via **Deploy from a branch**, it updates automatically; if via **Actions**, re‑run the latest Pages job.

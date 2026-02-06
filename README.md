index.html
library.html
resources.html
suggest.html
/assets/   (logo.svg, hero-classroom.svg, icon-*.svg, chime.mp3)<!-- Place where your 10-minute focus lives -->
<div class="card" style="display:grid; place-items:center; text-align:center;">
  <h3>10‑minute focus</h3>
  <svg width="180" height="180" viewBox="0 0 120 120" aria-hidden="true">
    <circle id="focusRingBg" cx="60" cy="60" r="54" fill="none"/>
    <defs>
      <linearGradient id="grad" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#0066FF"/>
        <stop offset="100%" stop-color="#FF4D6D"/>
      </linearGradient>
    </defs>
    <circle id="focusRing" cx="60" cy="60" r="54" fill="none"
            stroke-dasharray="339.292" stroke-dashoffset="339.292"/>
  </svg>
  <div style="margin-top:.75rem;">
    <button id="startFocus" class="btn">Start</button>
    <button id="stopFocus" class="btn" style="background:#1F2937">Stop</button>
  </div>
  <p id="focusMsg" style="margin:.5rem 0 0;">Ready</p>
</div>

<button id="toTop" aria-label="Back to top" onclick="window.scrollTo({top:0,behavior:'smooth'})">↑</button>

<script>
(()=> {
  const ring = document.getElementById('focusRing');
  const msg = document.getElementById('focusMsg');
  const start = document.getElementById('startFocus');
  const stop = document.getElementById('stopFocus');
  const len = 339.292, DURATION = 10*60*1000;
  let raf, t0;
  const chime = new Audio('assets/chime.mp3');

  function step(ts){
    if(!t0) t0 = ts;
    const p = Math.min((ts - t0)/DURATION, 1);
    ring.style.strokeDashoffset = String(len * (1 - p));
    msg.textContent = p<1 ? `Focusing… ${Math.ceil((DURATION - (ts - t0))/1000)}s` : 'Done!';
    if(p<1) raf = requestAnimationFrame(step);
    else { chime.play().catch(()=>{}); alert('Focus complete ✨'); }
  }
  start?.addEventListener('click', ()=>{ cancelAnimationFrame(raf); t0=null; ring.style.strokeDashoffset = len; raf=requestAnimationFrame(step); });
  stop?.addEventListener('click', ()=>{ cancelAnimationFrame(raf); t0=null; msg.textContent='Paused'; });
})();
</script>
git commit --allow-empty -m "Trigger GitHub Pages rebuild"
git push
git commit --allow-empty -m "Trigger GitHub Pages rebuild"
git push
# ThriveHub V6.1b — Icons + Tags + Expanded Professional Learning

**Publish (branch deploy)**
1) Settings → Pages → **Source: Deploy from a branch** → **Branch: main** → **Folder: /(root)** → Save.
2) Upload the **contents of this ZIP** to the repo **root** (not the ZIP itself).
3) Open in Incognito/Private and hard‑refresh:
   - dgr125.github.io/thrivehub/
   - dgr125.github.io/thrivehub/library.html

**What’s new vs V6.1a**
- Micro‑icons on Home gateway buttons
- Small topic **tags** under Highlights items (e.g., PD, Toolkit, Video)
- Library: **Professional learning** card expanded (PLINK, RRHAN‑EC, AISSA, CESA)
- Refined **About** section

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>ThriveHub — Calm Space (V7.7)</title>
<style>
:root{--bg1:#0b3a3f;--bg2:#0b5a7a;--ink:#E6F2F4;--muted:#9CC7D1;--dark:#0a1a22}
*{box-sizing:border-box}html,body{margin:0}
body{font:16px/1.6 system-ui,Segoe UI,Arial,sans-serif;background:var(--dark);color:var(--ink)}
.container{max-width:1100px;margin:0 auto;padding:22px}
.header{display:flex;align-items:center;justify-content:space-between;color:var(--muted)}
.brand{display:inline-flex;align-items:center;gap:.6rem;font-weight:800}
.brand .logo{background:linear-gradient(135deg,#1f9bd1,#2bd6b2);color:#051418;padding:.4rem .8rem;border-radius:12px}
.card{background:radial-gradient(1200px 500px at 10% 10%, rgba(58,169,255,.15), transparent),linear-gradient(140deg,var(--bg1),var(--bg2));border-radius:26px;padding:24px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px;margin-top:10px}
.cardLite{background:#0f2631;border:1px solid #103141;border-radius:18px;padding:16px}
.link{color:#72c8ff;font-weight:800;text-decoration:none}
</style>
</head>
<body>
<div class="container">
  <div class="header">
    <div class="brand"><span class="logo">ThriveHub</span><span>V7.7</span></div>
    <div></div>
  </div>

  <section class="card">
    <h2 style="margin:.35rem 0 8px">Calm Space / Wellbeing playlist</h2>
    <p style="color:#9CC7D1">Short, classroom‑ready calming tools.</p>

    <div class="grid">
      <div class="cardLite">
        <h3>Breathing exercises</h3>
        <p>
          <a class="link" href="https://youtu.be/8VwY4ptQkLU" target="_blank" rel="noopener">Box breathing</a><br>
          <a class="link" href="https://www.smilingmind.com.au/schools" target="_blank" rel="noopener">Smiling Mind — Schools</a>
        </p>
      </div>
      <div class="cardLite">
        <h3>Grounding & regulation</h3>
        <p>
          <a class="link" href="https://youtu.be/7bK7i3Oe6nY" target="_blank" rel="noopener">5‑4‑3‑2‑1 grounding</a><br>
          <a class="link" href="https://studentwellbeinghub.edu.au/educators" target="_blank" rel="noopener">Student Wellbeing Hub — Regulation</a>
        </p>
      </div>
      <div class="cardLite">
        <h3>Digital wellbeing</h3>
        <p><a class="link" href="https://www.esafety.gov.au/educators/classroom-resources" target="_blank" rel="noopener">eSafety — Classroom resources</a></p>
      </div>
    </div>

    <div class="cardLite" style="margin-top:14px">
      <h3>Coming next…</h3>
      <ul>
        <li>Micro‑breaks</li><li>Calming animations</li><li>Breathing prompts</li><li>Mindfulness grounding tools</li>
      </ul>
    </div>

    <p style="margin-top:12px"><a class="link" href="index.html">Back to Home</a></p>
  </section>
  <footer>Created by Teresa Bruno • © Teresa Bruno</footer>
</div>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>ThriveHub — Library (V7.7)</title>
<style>
:root{--bg1:#0b3a3f;--bg2:#0b5a7a;--ink:#E6F2F4;--muted:#9CC7D1;--green:#23d160;--blue:#3aa9ff;--pill:#fff;--dark:#0a1a22}
*{box-sizing:border-box}html,body{margin:0}
body{font:16px/1.6 system-ui,Segoe UI,Arial,sans-serif;background:var(--dark);color:var(--ink)}
.container{max-width:1100px;margin:0 auto;padding:22px}
.header{display:flex;align-items:center;justify-content:space-between;color:var(--muted)}
.brand{display:inline-flex;align-items:center;gap:.6rem;font-weight:800}
.brand .logo{background:linear-gradient(135deg,#1f9bd1,#2bd6b2);color:#051418;padding:.4rem .8rem;border-radius:12px}
.badge{display:inline-block;background:rgba(255,255,255,.12);color:var(--pill);border:1px solid rgba(255,255,255,.25);padding:.25rem .6rem;border-radius:999px;font-weight:800}
.card{background:radial-gradient(1200px 500px at 10% 10%, rgba(58,169,255,.15), transparent),linear-gradient(140deg,var(--bg1),var(--bg2));border-radius:26px;padding:24px}
.searchbar{position:sticky;top:0;background:#0f2631;border:1px solid #103141;padding:10px;border-radius:14px;box-shadow:0 4px 14px rgba(0,0,0,.25);display:flex;flex-wrap:wrap;gap:.6rem;margin:22px 0}
.searchbar input{flex:1;min-width:240px;padding:.6rem .75rem;background:#0d2029;color:var(--ink);border:1px solid #123a4a;border-radius:12px}
.searchbar button{padding:.6rem .85rem;border-radius:999px;border:1px solid #123a4a;background:#0d2029;color:#9CC7D1;cursor:pointer}
.item{background:#0f2631;border:1px solid #123a4a;border-left:6px solid #12c55a;border-radius:12px;padding:12px;margin:10px 0;box-shadow:0 6px 16px rgba(0,0,0,.3)}
.link{color:#72c8ff;font-weight:800;text-decoration:none}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:14px;margin-top:16px}
.bundle{background:#0f2631;border:1px solid #103141;border-radius:18px;padding:16px}
.tag{display:inline-block;background:#103141;color:#9CC7D1;border:1px solid #123a4a;padding:2px 8px;border-radius:999px;font-weight:800;font-size:.8rem;margin-right:.35rem}
.thumb{width:56px;height:56px;border-radius:14px;background:linear-gradient(135deg,#66c1ff,#2e97ff);display:flex;align-items:center;justify-content:center;margin-right:10px}
.linkset{display:flex;flex-wrap:wrap;gap:.45rem;margin-top:.5rem}
.chip{display:inline-block;background:linear-gradient(180deg,#66c1ff,#2e97ff);color:#04121e;padding:.52rem .8rem;border-radius:12px;text-decoration:none;font-weight:800}
.badgeSA{display:inline-block;background:#103141;color:#9CC7D1;border:1px solid #123a4a;padding:2px 8px;border-radius:999px;font-weight:800;font-size:.85rem}
</style>
</head>
<body>
<div class="container">
  <div class="header">
    <div class="brand"><span class="logo">ThriveHub</span><span>V7.7</span></div>
    <div></div>
  </div>

  <section class="card">
    <h2 style="margin:.35rem 0 8px">Premium Library — One Page</h2>
    <p style="color:var(--muted)">Use search, the SA-only toggle, or scroll the bundles.</p>

    <div class="searchbar">
      <input id="q" type="text" placeholder="Search (e.g., Trauma, EALD, Interoception, SA)">
      <button id="saBtn" aria-pressed="false" title="Show South Australia only">SA‑only</button>
      <button id="resetBtn" title="Reset all filters">Reset</button>
    </div>

    <div id="list" aria-live="polite"></div>

    <!-- Example bundle card (feel free to duplicate/edit later) -->
    <div class="grid">
      <div class="bundle">
        <div style="display:flex;align-items:center">
          <div class="thumb">
            <!-- simple icon -->
            <svg viewBox="0 0 24 24" width="34" height="34"><rect x="3" y="4" width="18" height="16" rx="2" ry="2" fill="white" opacity=".15"/><path d="M7 7h10M7 11h10M7 15h6" stroke="white" stroke-width="2" stroke-linecap="round"/></svg>
          </div>
          <div>
            <h3 style="margin:0">Early Years bundle</h3>
            <span class="tag">Early Learning</span><span class="tag">SEL</span><span class="tag">Interoception</span>
          </div>
        </div>
        <p style="color:#9CC7D1;margin:.5rem 0 0.6rem">High‑impact classroom resources and PL for ages 3–8.</p>
        <p class="linkset">
          <a class="chip" href="https://studentwellbeinghub.edu.au/" target="_blank" rel="noopener">Student Wellbeing Hub</a>
          <a class="chip" href="https://www.narragunnawali.org.au/curriculum-resources" target="_blank" rel="noopener">Narragunnawali</a>
        </p>
      </div>
    </div>
  </section>

  <p style="margin-top:10px;color:#6ea7b4">Tip: type “Autism”, “EALD”, or “Interoception”.</p>
  <p><a class="link" href="index.html">Back to Home</a></p>
  <footer>Created by Teresa Bruno • © Teresa Bruno</footer>
</div>

<script>
const RES=[
  {t:'SA Dept — Interoception',u:'https://www.education.sa.gov.au/student-support-services/health-and-wellbeing/interoception',tags:'Interoception, Regulation',region:'SA'},
  {t:'eSafety — Classroom resources',u:'https://www.esafety.gov.au/educators/classroom-resources',tags:'Online safety, Digital wellbeing',region:'National'}
];
const list=document.getElementById('list'), q=document.getElementById('q'),
      saBtn=document.getElementById('saBtn'), resetBtn=document.getElementById('resetBtn');
let saOnly=false;
function draw(){
  const term=(q.value||'').toLowerCase();
  let arr=RES.slice();
  if(saOnly) arr=arr.filter(r=>r.region==='SA');
  arr=arr.filter(r=>!term||r.t.toLowerCase().includes(term)||r.tags.toLowerCase().includes(term));
  list.innerHTML = arr.map(r=>`
    <div class="item">
      <strong>${r.t}</strong><br>
      <a class="link" href="${r.u}" target="_blank" rel="noopener">Open link ↗</a>
      <div style="margin-top:.25rem"><span class="badgeSA">${r.region}</span>
        <span style="color:#9CC7D1;font-size:.9rem"> • ${r.tags}</span></div>
    </div>`).join('') || '<p style="color:#9CC7D1">No results — try clearing filters.</p>';
}
saBtn.onclick=()=>{saOnly=!saOnly;saBtn.setAttribute('aria-pressed', String(saOnly));saBtn.textContent=saOnly?'SA‑only (on)':'SA‑only';draw();};
resetBtn.onclick=()=>{saOnly=false;saBtn.setAttribute('aria-pressed','false');saBtn.textContent='SA‑only';q.value='';draw();};
q.oninput=draw; draw();
</script>
</body>
</html>
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

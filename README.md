[index.html](https://github.com/user-attachments/files/24898186/index.html)[404.html](https://github.com/user-attachments/files/24898182/404.html)[index.html](https://github.com/user-attachments/files/24898181/index.html)





[adhd.html](https://github.com/user-attachments/files/24898176/adhd.html)<!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'><meta name='viewport' content='width=device-width, initial-scale=1.0'><title>One‑Pager – ADHD</title><style>body{font-family:Arial,sans-serif;margin:24px;color:#111}h1{margin:0 0 8px}h2{margin:16px 0 6px}ul{margin:6px 0 16px}.small{opacity:.75}@media print{a:after{content:''}} .print{position:fixed;top:12px;right:12px;padding:.4rem .6rem;border:1px solid #ccc;border-radius:6px;}</style></head><body><button class='print' onclick='window.print()'>Print</button><h1>ThriveHub One‑Pager</h1><h2>ADHD</h2><p>Quick checklist for planning and classroom use. For full links and details, open <strong>https://DGR125.github.io/thrivehub/</strong>.</p><h3>Core strategies</h3><ul><li>Use clear goals, chunk tasks, provide visuals.</li><li>Build predictable routines; pre‑teach and model.</li><li>Offer adjustments and assistive tools as needed.</li></ul><h3>Live resources</h3><p>See the <em>Additional Resources</em> section in ThriveHub (e.g., NCCD, Student Wellbeing Hub, Positive Partnerships, eSafety, EAL/D, SWPBS).</p><p class='small'>Generated one‑pager.</p></body></html>

[Uploading i<!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'><meta name='viewport' content='width=device-width, initial-scale=1.0'><title>ThriveHub – Additional Resources</title></head><body><p>This content now appears on the home page. <a href='../index.html'>Back to ThriveHub</a></p></body></html>ndex.html…]()



[Uploading 404.htm<!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'><meta http-equiv='refresh' content='2; url=./index.html'><meta name='viewport' content='width=device-width, initial-scale=1.0'><title>Redirecting…</title><style>body{font-family:Arial,Helvetica,sans-serif;margin:2rem}a{color:#00796b}</style></head><body><h1>We moved something.</h1><p>Taking you back to ThriveHub… If not redirected automatically, <a href='./index.html'>click here</a>.</p></body></html>l…]()




<img width="900" height="280" alt="thrivehub-logo" src="https://github.com/user-attachments/assets/20bd7056-b3d1-41a0-8767-0e9194786b63" />

<img width="64" height="64" alt="favicon" src="https://github.com/user-attachments/assets/d3f079d4-f6b0-4343-86d3-461a05094011" />


<img width="370" height="370" alt="qr_thrivehub" src="https://github.com/user-attachments/assets/eea4c30a-f2cc-432e-acbb-d9df42dd4983" />


[Uploading # ThriveHub (V4) — Quick Start & Troubleshooting

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
[README.md](https://github.com/user-attachments/files/24898188/README.md)
ind<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ThriveHub – Helping Teachers Empower Every Learner</title>
  <meta name="description" content="ThriveHub is a teacher‑friendly hub for inclusive practice. Explore clear categories, evidence‑based strategies and live links to trusted Australian resources (NCCD, state departments, specialists). Search, like and save what works. Built for quick planning, classroom use and alignment with SA’s education strategy." />
  <link rel="icon" type="image/png" href="favicon.png" />
  <style>
    :root { --bg:#f8fafc; --card:#ffffff; --text:#0b1020; --brand:#004d40; --accent:#00796b; --like:#e91e63; --muted:#e7f5f2; --focus:#ffbf47; }
    .dark { --bg:#0f172a; --card:#0b1320; --text:#e5e7eb; --brand:#0ea5e9; --accent:#22d3ee; --like:#fb7185; --muted:#0b1b2b; --focus:#ffbf47; }
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:Arial,Helvetica,sans-serif;line-height:1.5}
    a{color:var(--accent)}
    a:focus, button:focus, input:focus{outline:3px solid var(--focus); outline-offset:2px}
    .visually-hidden{position:absolute!important;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}
    .skip-link{position:absolute;left:-9999px;top:auto;width:1px;height:1px;overflow:hidden}
    .skip-link:focus{left:1rem;top:1rem;width:auto;height:auto;background:#fff;color:#000;padding:.5rem .75rem;border-radius:6px;z-index:1000}
    header{background:var(--brand);color:#fff;padding:1rem 1rem 1.2rem}
    header .wrap{max-width:1150px;margin:0 auto;display:flex;align-items:center;gap:1rem}
    header img.logo{width:160px;height:auto}
    header h1{margin:.2rem 0 .1rem 0;font-size:1.6rem}
    header p{margin:0;opacity:.9}
    header .controls{margin-left:auto}
    .btn{border:none;padding:.5rem .8rem;border-radius:6px;background:var(--accent);color:#fff;cursor:pointer}
    main{padding:1.2rem;max-width:1150px;margin:0 auto}
    .search-bar{display:flex;justify-content:center;margin-bottom:1rem}
    .search-bar input{width:min(760px,92vw);padding:.6rem;border-radius:6px;border:1px solid #cbd5e1}
    .carousel-wrap{background:var(--muted);border-radius:12px;margin:1rem 0 2rem;padding:.5rem 0}
    .carousel{display:flex;overflow-x:auto;gap:1rem;padding:1rem}
    .carousel-item{min-width:260px;background:var(--card);padding:1rem;border-radius:10px;box-shadow:0 2px 6px rgba(0,0,0,.12)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:1rem}
    .category-card,.card{background:var(--card);border-radius:10px;padding:1rem;box-shadow:0 2px 6px rgba(0,0,0,.1)}
    .category-card{cursor:pointer}
    .strategy-section{display:none;background:var(--card);border-radius:10px;padding:1rem;box-shadow:0 2px 6px rgba(0,0,0,.1)}
    .strategy-item{display:flex;justify-content:space-between;align-items:center;padding:.5rem .75rem;margin:.35rem 0;border:1px solid #ddd;border-radius:8px}
    .like-btn{background:none;border:none;color:var(--like);font-size:1.1rem;cursor:pointer}
    .card h2, .card h3{margin-top:0}
    footer{margin-top:2rem;background:var(--brand);color:#fff}
    footer .wrap{max-width:1150px;margin:0 auto;padding:1rem;display:flex;align-items:center;gap:1rem}
    footer img.logo{width:80px;height:auto}
  </style>
</head>
<body>
  <a href="#main" class="skip-link">Skip to main content</a>
  <header role="banner">
    <div class="wrap">
      <img src="thrivehub-logo.png" alt="ThriveHub logo" class="logo" />
      <div>
        <h1>ThriveHub</h1>
        <p>Helping Teachers Empower Every Learner</p>
      </div>
      <div class="controls">
        <button class="btn" id="toggleTheme" aria-label="Toggle dark mode">🌗 Dark Mode</button>
      </div>
    </div>
  </header>

  <main id="main" role="main">
    <div class="search-bar" aria-label="Global search">
      <input type="text" id="searchInput" placeholder="Search categories or strategies…" oninput="searchContent()" aria-label="Search" />
    </div>

    <section class="carousel-wrap" aria-labelledby="popularHeading">
      <h2 id="popularHeading" style="text-align:center;">🌟 Most Liked Strategies</h2>
      <div class="carousel" id="popular-strategies" role="region" aria-live="polite"></div>
    </section>

    <section id="categories" aria-labelledby="catHeading">
      <h2 id="catHeading">Categories</h2>
      <div class="grid">
        <div class="category-card" tabindex="0" role="button" aria-pressed="false" onclick="showStrategies('intellectual')">🧠 Intellectual Disability <button class="btn" onclick="event.stopPropagation();openOnePager('intellectual')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('autism')">🧩 Autism / Social Communication <button class="btn" onclick="event.stopPropagation();openOnePager('autism')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('adhd')">💡 ADHD <button class="btn" onclick="event.stopPropagation();openOnePager('adhd')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('trauma')">🫶 Trauma‑aware Practice <button class="btn" onclick="event.stopPropagation();openOnePager('trauma')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('physical')">♿ Physical Disability <button class="btn" onclick="event.stopPropagation();openOnePager('physical')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('communication')">💬 Communication Needs & AAC <button class="btn" onclick="event.stopPropagation();openOnePager('communication')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('dyslexia')">🔤 Dyslexia & Specific Learning Difficulties <button class="btn" onclick="event.stopPropagation();openOnePager('dyslexia')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('hearing')">🦻 Deaf / Hard of Hearing <button class="btn" onclick="event.stopPropagation();openOnePager('hearing')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('vision')">👁️ Blind / Low Vision <button class="btn" onclick="event.stopPropagation();openOnePager('vision')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="showStrategies('assistive')">🛠️ Assistive Technology <button class="btn" onclick="event.stopPropagation();openOnePager('assistive')" aria-label="Open one‑pager">Print</button></div>
        <div class="category-card" tabindex="0" role="button" onclick="location.hash='#resources';document.getElementById('resources').scrollIntoView({behavior:'smooth'})">📚 Additional Resources (Free links)</div>
        <div class="category-card" tabindex="0" role="button" onclick="window.open('https://thestudentwellbeing.wordpress.com/','_blank')">📝 Teacher Resources (Blog)</div>
      </div>
    </section>

    <!-- Strategy Sections (short lists) -->
    <section id="intellectual" class="strategy-section" aria-labelledby="intellectualHeading">
      <h2 id="intellectualHeading">Intellectual Disability</h2>
      <ul>
        <li class="strategy-item">Use clear, simple instructions <button class="like-btn" onclick="likeStrategy('like_id_clear_instructions', this)">❤️ 0</button></li>
        <li class="strategy-item">Chunk tasks & provide visual supports <button class="like-btn" onclick="likeStrategy('like_id_chunk_visuals', this)">❤️ 0</button></li>
        <li class="strategy-item">Consistent routines & feedback <button class="like-btn" onclick="likeStrategy('like_id_routines_feedback', this)">❤️ 0</button></li>
      </ul>
      <button class="btn" onclick="goBack()">← Back to Categories</button>
    </section>

    <section id="autism" class="strategy-section" aria-labelledby="autismHeading">
      <h2 id="autismHeading">Autism / Social Communication</h2>
      <ul>
        <li class="strategy-item">Visual schedules & social stories <button class="like-btn" onclick="likeStrategy('like_aut_visual_schedules', this)">❤️ 0</button></li>
        <li class="strategy-item">Minimise sensory overload <button class="like-btn" onclick="likeStrategy('like_aut_sensory', this)">❤️ 0</button></li>
        <li class="strategy-item">Explicit teaching of social skills <button class="like-btn" onclick="likeStrategy('like_aut_social_skills', this)">❤️ 0</button></li>
      </ul>
      <button class="btn" onclick="goBack()">← Back to Categories</button>
    </section>

    <section id="adhd" class="strategy-section" aria-labelledby="adhdHeading">
      <h2 id="adhdHeading">ADHD</h2>
      <ul>
        <li class="strategy-item">Movement breaks & flexible seating <button class="like-btn" onclick="likeStrategy('like_adhd_movement', this)">❤️ 0</button></li>
        <li class="strategy-item">Chunked instructions & visuals <button class="like-btn" onclick="likeStrategy('like_adhd_chunk_visual', this)">❤️ 0</button></li>
        <li class="strategy-item">Timers & immediate feedback <button class="like-btn" onclick="likeStrategy('like_adhd_timers', this)">❤️ 0</button></li>
      </ul>
      <button class="btn" onclick="goBack()">← Back to Categories</button>
    </section>

    <!-- Embedded Additional Resources (searchable) -->
    <section id="resources" class="card" aria-labelledby="resHeading">
      <h2 id="resHeading">Additional Resources (Free)</h2>
      <p>Curated Australian links for inclusive practice, wellbeing and classroom support. Use the search box to filter quickly.</p>
      <div style="display:flex; gap:.5rem; align-items:center; margin:0 0 1rem 0;">
        <input id="resSearch" type="text" placeholder="Search resources (e.g. SWPBS, EAL/D, trauma, eSafety)…" style="flex:1; padding:.6rem; border:1px solid #cbd5e1; border-radius:6px;" aria-label="Search resources">
        <button id="clearBtn" class="btn" style="background:#fff;color:#0f0f0f;border:1px solid #cbd5e1;">Clear</button>
      </div>
      <div class="grid">
        <div class="card"><h3>Fetal Alcohol Spectrum Disorder (FASD)</h3>
          <ul>
            <li><a href="https://learningwithfasd.org.au/primary-school/classroom-strategies/" target="_blank" rel="noopener">Learning with FASD – Classroom strategies</a></li>
            <li><a href="https://fasdhub.org.au/for-educators/" target="_blank" rel="noopener">FASD Hub Australia – For educators</a></li>
            <li><a href="https://www.nofasd.org.au/fasd-information/service-providers/education/" target="_blank" rel="noopener">NOFASD Australia – Education resources</a></li>
          </ul>
        </div>
        <div class="card"><h3>Wellbeing (Whole‑school)</h3>
          <ul>
            <li><a href="https://beyou.edu.au/" target="_blank" rel="noopener">Be You – National mental health in education</a></li>
            <li><a href="https://studentwellbeinghub.edu.au/" target="_blank" rel="noopener">Student Wellbeing Hub – Free resources</a></li>
            <li><a href="https://schools.au.reachout.com/" target="_blank" rel="noopener">ReachOut Schools – Classroom resources</a></li>
          </ul>
        </div>
        <div class="card"><h3>Online Safety</h3>
          <ul>
            <li><a href="https://www.esafety.gov.au/educators/classroom-resources" target="_blank" rel="noopener">eSafety Commissioner – Classroom resources</a></li>
            <li><a href="https://studentwellbeinghub.edu.au/resources/esafety-classroom-resources-for-educators/" target="_blank" rel="noopener">eSafety on Student Wellbeing Hub</a></li>
          </ul>
        </div>
        <div class="card"><h3>Autism – Free PL & tools</h3>
          <ul>
            <li><a href="https://www.positivepartnerships.com.au/" target="_blank" rel="noopener">Positive Partnerships – Workshops & resources</a></li>
            <li><a href="https://studentwellbeinghub.edu.au/resources/positive-partnerships-online-learning/" target="_blank" rel="noopener">Positive Partnerships – Online learning</a></li>
            <li><a href="https://autismsa.org.au/supports-services/school-inclusion-program-for-educators/" target="_blank" rel="noopener">Autism SA – School Inclusion Program</a></li>
          </ul>
        </div>
        <div class="card"><h3>Trauma‑aware practice</h3>
          <ul>
            <li><a href="https://research.qut.edu.au/c4ie/national-guidelines-for-trauma-aware-education/" target="_blank" rel="noopener">National Guidelines for Trauma‑Aware Education</a></li>
            <li><a href="https://www.aitsl.edu.au/tools-resources/resource/national-guidelines-for-trauma---aware-education" target="_blank" rel="noopener">AITSL – Guidelines overview</a></li>
          </ul>
        </div>
        <div class="card"><h3>EAL/D – English as an Additional Language or Dialect</h3>
          <ul>
            <li><a href="https://www.acara.edu.au/_resources/EALD_teacher_resource.pdf" target="_blank" rel="noopener">ACARA – EAL/D Teacher Resource</a></li>
            <li><a href="https://education.nsw.gov.au/teaching-and-learning/multicultural-education/english-as-an-additional-language-or-dialect/resources" target="_blank" rel="noopener">NSW DoE – EAL/D resources</a></li>
            <li><a href="https://www.australiancurriculum.edu.au/student-diversity/eal-d-students" target="_blank" rel="noopener">Australian Curriculum – EAL/D students</a></li>
          </ul>
        </div>
        <div class="card"><h3>Gifted / High Potential</h3>
          <ul>
            <li><a href="https://education.nsw.gov.au/teaching-and-learning/high-potential-and-gifted-education" target="_blank" rel="noopener">NSW – High Potential & Gifted Education</a></li>
            <li><a href="https://education.nsw.gov.au/teaching-and-learning/high-potential-and-gifted-education/supporting-educators" target="_blank" rel="noopener">HPGE – Supporting educators</a></li>
          </ul>
        </div>
        <div class="card"><h3>Behaviour & SWPBS</h3>
          <ul>
            <li><a href="https://www.vic.gov.au/school-wide-positive-behaviour-support" target="_blank" rel="noopener">Victoria – SWPBS overview</a></li>
            <li><a href="https://www.education.vic.gov.au/Documents/school/teachers/support/SWPBS-Information-for-schools.pdf" target="_blank" rel="noopener">SWPBS – Info for Schools (PDF)</a></li>
          </ul>
        </div>
        <div class="card"><h3>Evidence for Learning</h3>
          <ul>
            <li><a href="https://evidenceforlearning.org.au/education-evidence/teaching-learning-toolkit" target="_blank" rel="noopener">Teaching & Learning Toolkit</a></li>
            <li><a href="https://education.nsw.gov.au/about-us/education-data-and-research/cese/publications/teaching-and-learning-toolkit" target="_blank" rel="noopener">NSW CESE – Toolkit overview</a></li>
          </ul>
        </div>
        <div class="card"><h3>Assistive Technology</h3>
          <ul>
            <li><a href="https://education.qld.gov.au/students/inclusive-education/assistive-technology" target="_blank" rel="noopener">QLD Education – Assistive technology</a></li>
            <li><a href="https://projects.purpleorange.org.au/inclusiveschoolcommunities/resources/toolkit/assistive-technologies-schools" target="_blank" rel="noopener">Inclusive School Communities – AT toolkit</a></li>
            <li><a href="https://dsf.net.au/professionals/teachers-and-tutors/supporting-students-with-learning-difficulties-in-/assistive-technology-resources" target="_blank" rel="noopener">DSF – AT resources list</a></li>
          </ul>
        </div>
        <div class="card"><h3>First Nations resources</h3>
          <ul>
            <li><a href="https://beyou.edu.au/" target="_blank" rel="noopener">Be You – culturally responsive practice & PL</a></li>
            <li><a href="https://www.australiancurriculum.edu.au/" target="_blank" rel="noopener">Australian Curriculum – cross‑curriculum priorities</a></li>
          </ul>
        </div>
        <div class="card"><h3>Interoception & Self‑regulation</h3>
          <ul>
            <li><a href="https://studentwellbeinghub.edu.au/" target="_blank" rel="noopener">Student Wellbeing Hub – Interoception PL & activities</a></li>
          </ul>
        </div>
        <div class="card"><h3>Teacher Resources (Blog)</h3>
          <ul>
            <li><a href="https://thestudentwellbeing.wordpress.com/" target="_blank" rel="noopener">The Student Wellbeing – classroom ideas</a></li>
          </ul>
        </div>
      </div>
    </section>

    <section class="card" aria-labelledby="blogHeading">
      <h2 id="blogHeading">Latest from the blog</h2>
      <ul id="blogList"><li>Loading…</li></ul>
      <p><a class="btn" href="https://thestudentwellbeing.wordpress.com/" target="_blank" rel="noopener">Open the Teacher Resources blog</a></p>
    </section>

    <section class="card" aria-labelledby="whyHeading">
      <h2 id="whyHeading">Why ThriveHub?</h2>
      <p>ThriveHub supports inclusive, trauma‑aware and evidence‑informed practice aligned with South Australia’s Department for Education strategy and inclusive principles.</p>
    </section>
  </main>

  <footer role="contentinfo">
    <div class="wrap">
      <img src="thrivehub-logo.png" alt="ThriveHub" class="logo" />
      <p>© 2026 ThriveHub — Inclusive Education Strategies</p>
    </div>
  </footer>

  <script>
    // Theme
    const toggle=document.getElementById('toggleTheme');
    const userPref=localStorage.getItem('thrivehub_theme')||'light';
    if(userPref==='dark')document.body.classList.add('dark');
    toggle.addEventListener('click',()=>{document.body.classList.toggle('dark');localStorage.setItem('thrivehub_theme',document.body.classList.contains('dark')?'dark':'light')});

    // Navigation
    function showStrategies(id){
      document.getElementById('categories').style.display='block';
      document.querySelectorAll('.strategy-section').forEach(sec=>sec.style.display='none');
      document.getElementById(id).style.display='block';
      window.scrollTo({top:0,behavior:'smooth'});
    }
    function goBack(){
      document.getElementById('categories').style.display='block';
      document.querySelectorAll('.strategy-section').forEach(sec=>sec.style.display='none');
      window.scrollTo({top:0,behavior:'smooth'});
    }

    function openOnePager(key){
      window.open('one-pagers/'+key+'.html','_blank');
    }

    // Global search (categories + strategy list items)
    function searchContent(){
      const q=document.getElementById('searchInput').value.toLowerCase();
      document.querySelectorAll('.category-card').forEach(card=>{card.style.display=card.textContent.toLowerCase().includes(q)?'block':'none'});
      document.querySelectorAll('.strategy-section li').forEach(item=>{item.style.display=item.textContent.toLowerCase().includes(q)?'flex':'none'});
    }

    // Likes + carousel
    function getLikes(key){return parseInt(localStorage.getItem(key)||'0',10)}
    function likeStrategy(key,btn){const count=getLikes(key)+1;localStorage.setItem(key,count);btn.textContent=`❤️ ${count}`;updateCarousel()}
    function updateCarousel(){
      const c=document.getElementById('popular-strategies');
      c.innerHTML='';
      const likes=[];
      for(const k in localStorage){ if(k.startsWith('like_')){ likes.push({key:k,count:getLikes(k),label:k.replace('like_','').replace(/_/g,' ')}); } }
      likes.sort((a,b)=>b.count-a.count).slice(0,12).forEach(item=>{
        const div=document.createElement('div');div.className='carousel-item';div.textContent=`${item.label} (${item.count} likes)`;c.appendChild(div);
      })
    }
    updateCarousel();

    // Embedded resources search
    const resS=document.getElementById('resSearch');
    const resC=document.getElementById('clearBtn');
    const resCards=[...document.querySelectorAll('#resources .card')];
    function resFilter(){const q=(resS?.value||'').trim().toLowerCase();resCards.forEach(card=>{card.style.display=card.innerText.toLowerCase().includes(q)?'block':'none'})}
    if(resS)resS.addEventListener('input',resFilter);
    if(resC)resC.addEventListener('click',()=>{resS.value='';resFilter()});

    // Latest from WordPress blog (progressive enhancement)
    (async ()=>{
      const list = document.getElementById('blogList');
      try{
        const resp = await fetch('https://public-api.wordpress.com/rest/v1.1/sites/thestudentwellbeing.wordpress.com/posts/?number=3');
        if(!resp.ok) throw new Error('WP API not OK');
        const data = await resp.json();
        list.innerHTML = '';
        (data.posts||[]).slice(0,3).forEach(p=>{
          const li=document.createElement('li');
          const a=document.createElement('a'); a.href=p.URL; a.target='_blank'; a.rel='noopener'; a.textContent=p.title || 'Untitled';
          const em=document.createElement('em'); em.textContent = p.excerpt ? ' – ' + (p.excerpt.replace(/<[^>]*>?/gm,'').slice(0,90)+'…') : '';
          li.appendChild(a); li.appendChild(em); list.appendChild(li);
        });
        if(!list.children.length){ throw new Error('No posts'); }
      }catch(e){
        list.innerHTML = '<li><a href="https://thestudentwellbeing.wordpress.com/" target="_blank" rel="noopener">Open the Teacher Resources blog</a></li>';
      }
    })();
  </script>
</body>
</html>
ex.html…]()



index.html
favicon.png
thrivehub-logo.png
404.html
qr_thrivehub.png
/one-pagers
/resources
README.md[index.html](https://github.com/user-attachments/files/24898160/index.html)<!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'><meta name='viewport' content='width=device-width, initial-scale=1.0'><title>ThriveHub – Additional Resources</title></head><body><p>This content now appears on the home page. <a href='../index.html'>Back to ThriveHub</a<!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'><met<img width="64" height="64" alt="favicon" src="https://github.com/user-attachments/assets/23970118-2941-4097-9e5d-f1ea1462e29c" />
a http-equiv='refresh' content='2; url=./index.html'><meta name='viewport' content='width=device-width, initial-scale=1.0'><title>Redirecting…</title><style>body{font-family:Arial,Helvetica,sans-serif;margin:2rem}a{color:#00796b}</style></head><body><h1>We moved something.</h1><p>Taking you back to ThriveHub… If not redirected automatically, <a href='./index.html'>click here</a>.</p></body></html>[404.html](https://github.com/user-attachments/files/24898161/404.html)
></p></body></html>

index.html
favicon.png
thrivehub-logo.png
404.html[adhd.html](https://github.com/user-attachments/files/24898159/adhd.html)<!DOCTYPE html><html lang='en'><head><meta charset='UTF-8'><meta name='viewport' content='width=device-width, initial-scale=1.0'><title>One‑Pager – ADHD</title><style>body{font-family:Arial,sans-serif;margin:24px;color:#111}h1{margin:0 0 8px}h2{margin:16px 0 6px}ul{margin:6px 0 16px}.small{opacity:.75}@media print{a:after{content:''}} .print{position:fixed;top:12px;right:12px;padding:.4rem .6rem;border:1px solid #ccc;border-radius:6px;}</style></head><body><button class='print' onclick='window.print()'>Print</button><h1>ThriveHub One‑Pager</h1><h2>ADHD</h2><p>Quick checklist for planning and classroom use. For full links and details, open <strong>https://DGR125.github.io/thrivehub/</strong>.</p><h3>Core strategies</h3><ul><li>Use clear goals, chunk tasks, provide visuals.</li><li>Build predictable routines; pre‑teach and model.</li><li>Offer adjustments and assistive tools as needed.</li></ul><h3>Live resources</h3><p>See the <em>Additional Resources</em> section in ThriveHub (e.g., NCCD, Student Wellbeing Hub, Positive Partnerships, eSafety, EAL/D, SWPBS).</p><p class='small'>Generated one‑pager.</p></body></html>

qr_thrivehub.png
/one-pagers
/resources
README.md

index.html
favicon.png
thrivehub-logo.png
resources/      (folder)
  └── index.html
README.md

<!-- BEFORE -->
<div class="category-card" onclick="window.open('resources/index.html','_blank')">📚 Additional Resources (Free links)</div>

<!-- AFTER -->
<div class="category-card" onclick="location.hash='#resources';document.getElementById('resources').scrollIntoView({behavior:'smooth'});">
  📚 Additional Resources (Free links)
</div>

<section id="resources" class="card">
  <h2>Additional Resources (Free)</h2>
  <p>Curated Australian links for inclusive practice, wellbeing and classroom support. Use the search box to filter quickly.</p>

  <div style="display:flex; gap:.5rem; align-items:center; margin:0 0 1rem 0;">
    <input id="resSearch" type="text" placeholder="Search resources (e.g. SWPBS, EAL/D, trauma, eSafety)…"
           style="flex:1; padding:.6rem; border:1px solid #ccc; border-radius:6px;">
    <button id="clearBtn" class="btn" style="background:#fff;color:#0f0f0f;border:1px solid #ccc;">Clear</button>
  </div>

  <!-- RESOURCES GRID: paste the cards below -->
  <div class="grid">

    <!-- FASD -->
    <div class="card">
      <h3>Fetal Alcohol Spectrum Disorder (FASD)</h3>
      <ul>
        <li><a href="https://learningwithfasd.org.au/primary-school/classroom-strategies/" target="_blank" rel="noopener">Learning with FASD – Classroom strategies</a></li>
        <li><a href="https://fasdhub.org.au/for-educators/" target="_blank" rel="noopener">FASD Hub Australia – For educators</a></li>
        <li><a href="https://www.nofasd.org.au/fasd-information/service-providers/education/" target="_blank" rel="noopener">NOFASD Australia – Education resources</a></li>
      </ul>
      <small>Moved from the home page as requested.</small>
    </div>

    <!-- Wellbeing -->
    <div class="card">
      <h3>Wellbeing (Whole‑school)</h3>
      <ul>
        <li><a href="https://beyou.edu.au/" target="_blank" rel="noopener">Be You – National mental health in education</a></li>
        <li><a href="https://studentwellbeinghub.edu.au/" target="_blank" rel="noopener">Student Wellbeing Hub – Free resources</a></li>
        <li><a href="https://schools.au.reachout.com/" target="_blank" rel="noopener">ReachOut Schools – Classroom resources</a></li>
      </ul>
    </div>

    <!-- Online Safety -->
    <div class="card">
      <h3>Online Safety</h3>
      <ul>
        <li><a href="https://www.esafety.gov.au/educators/classroom-resources" target="_blank" rel="noopener">eSafety Commissioner – Classroom resources</a></li>
        <li><a href="https://studentwellbeinghub.edu.au/resources/esafety-classroom-resources-for-educators/" target="_blank" rel="noopener">eSafety resources on Student Wellbeing Hub</a></li>
      </ul>
    </div>

    <!-- Autism -->
    <div class="card">
      <h3>Autism – Free PL & tools</h3>
      <ul>
        <li><a href="https://www.positivepartnerships.com.au/" target="_blank" rel="noopener">Positive Partnerships – Workshops & resources</a></li>
        <li><a href="https://studentwellbeinghub.edu.au/resources/positive-partnerships-online-learning/" target="_blank" rel="noopener">Positive Partnerships – Online learning</a></li>
        <li><a href="https://autismsa.org.au/supports-services/school-inclusion-program-for-educators/" target="_blank" rel="noopener">Autism SA – School Inclusion Program</a></li>
      </ul>
    </div>

    <!-- Trauma-aware practice -->
    <div class="card">
      <h3>Trauma‑aware practice</h3>
      <ul>
        <li><a href="https://research.qut.edu.au/c4ie/national-guidelines-for-trauma-aware-education/" target="_blank" rel="noopener">National Guidelines for Trauma‑Aware Education</a></li>
        <li><a href="https://www.aitsl.edu.au/tools-resources/resource/national-guidelines-for-trauma---aware-education" target="_blank" rel="noopener">AITSL – Guidelines overview</a></li>
      </ul>
    </div>

    <!-- EAL/D -->
    <div class="card">
      <h3>EAL/D – English as an Additional Language or Dialect</h3>
      <ul>
        <li><a href="https://www.acara.edu.au/_resources/EALD_teacher_resource.pdf" target="_blank" rel="noopener">ACARA – EAL/D Teacher Resource</a></li>
        <li><a href="https://education.nsw.gov.au/teaching-and-learning/multicultural-education/english-as-an-additional-language-or-dialect/resources" target="_blank" rel="noopener">NSW DoE – EAL/D resources</a></li>
        <li><a href="https://www.australiancurriculum.edu.au/student-diversity/eal-d-students" target="_blank" rel="noopener">Australian Curriculum – EAL/D students</a></li>
      </ul>
    </div>

    <!-- Gifted / HPGE -->
    <div class="card">
      <h3>Gifted / High Potential</h3>
      <ul>
        <li><a href="https://education.nsw.gov.au/teaching-and-learning/high-potential-and-gifted-education" target="_blank" rel="noopener">NSW – High Potential & Gifted Education</a></li>
        <li><a href="https://education.nsw.gov.au/teaching-and-learning/high-potential-and-gifted-education/supporting-educators" target="_blank" rel="noopener">HPGE – Supporting educators</a></li>
      </ul>
    </div>

    <!-- Behaviour & SWPBS -->
    <div class="card">
      <h3>Behaviour & SWPBS</h3>
      <ul>
        <li><a href="https://www.vic.gov.au/school-wide-positive-behaviour-support" target="_blank" rel="noopener">Victoria – SWPBS overview</a></li>
        <li><a href="https://www.education.vic.gov.au/Documents/school/teachers/support/SWPBS-Information-for-schools.pdf" target="_blank" rel="noopener">SWPBS – Info for Schools (PDF)</a></li>
      </ul>
    </div>

    <!-- Evidence for Learning -->
    <div class="card">
      <h3>Evidence for Learning</h3>
      <ul>
        <li><a href="https://evidenceforlearning.org.au/education-evidence/teaching-learning-toolkit" target="_blank" rel="noopener">Teaching & Learning Toolkit</a></li>
        <li><a href="https://education.nsw.gov.au/about-us/education-data-and-research/cese/publications/teaching-and-learning-toolkit" target="_blank" rel="noopener">NSW CESE – Toolkit overview</a></li>
      </ul>
    </div>

    <!-- Assistive Technology -->
    <div class="card">
      <h3>Assistive Technology</h3>
      <ul>
        <li><a href="https://education.qld.gov.au/students/inclusive-education/assistive-technology" target="_blank" rel="noopener">QLD Education – Assistive technology</a></li>
        <li><a href="https://projects.purpleorange.org.au/inclusiveschoolcommunities/resources/toolkit/assistive-technologies-schools" target="_blank" rel="noopener">Inclusive School Communities – AT toolkit</a></li>
        <li><a href="https://dsf.net.au/professionals/teachers-and-tutors/supporting-students-with-learning-difficulties-in-/assistive-technology-resources" target="_blank" rel="noopener">DSF – AT resources list</a></li>
      </ul>
    </div>

    <!-- Teacher Resources (Blog) -->
    <div class="card">
      <h3>Teacher Resources (Blog)</h3>
      <ul>
        <li><a href="https://thestudentwellbeing.wordpress.com/" target="_blank" rel="noopener">The Student Wellbeing – Blog (classroom ideas)</a></li>
      </ul>
    </div>

  </div>
</section>

<script>
  const resS = document.getElementById('resSearch');
  const resC = document.getElementById('clearBtn');
  const resCards = Array.from(document.querySelectorAll('#resources .card'));
  function resFilter() {
    const q = (resS?.value || '').trim().toLowerCase();
    resCards.forEach(card => {
      card.style.display = card.innerText.toLowerCase().includes(q) ? 'block' : 'none';
    });
  }
  if (resS) resS.addEventListener('input', resFilter);
  if (resC) resC.addEventListener('click', () => { resS.value=''; resFilter(); });
</script>

# ThriveHub (V2) — Quick Start

**Public URL (after GitHub Pages):** `https://DGR125.github.io/thrivehub/`

## What changed in V2
- Removed the FASD category from the home page
- Added **Additional Resources** page with FASD and many more free links
- Prominent link to your **Teacher Resources blog** (thestudentwellbeing.wordpress.com)
- Australian English throughout

## How to publish
1. Create a public repo named `thrivehub` under `DGR125`.
2. Upload all files in this folder (keep `index.html` at the repo root).
3. Settings → Pages → Source: `main` / `/root`.
4. Your link will be `https://DGR125.github.io/thrivehub/`.

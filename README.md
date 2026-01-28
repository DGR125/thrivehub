index.html
favicon.png
thrivehub-logo.png
404.html
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

### ThriveHub: Library visual refresh + new sections

**What’s changed**
- Removed any visible developer tips; deployment note kept as a hidden HTML comment at the bottom of the file.
- Added **visual headers (gradient SVG “thumbs”)** to every category card.
- Added a simple **inline SVG logo** in the top nav (no external assets).
- Added sections:
  - **Executive Function & Study Skills** (Learning Scientists, EEF, Cornell templates, Pomodoro)
  - **Assessment Templates & Tools** (ReadWriteThink rubric & notetaker, Maths Hub Number Check, Ochre, NCCD)
- Internal links are **relative** (`index.html`, `library.html`, `resources.html`) so the page works reliably under `/thrivehub/`.

**Why these resources**
- The Learning Scientists’ six strategies posters are widely used, Creative Commons, and directly support student study skills in class. [1](https://www.sa.gov.au/topics/education-and-learning/international-students/english-language-support/english-as-a-second-language)
- The EEF’s *Metacognition & Self‑Regulated Learning* guidance offers practical, high‑impact classroom routines and tools. [2](https://www.dyscalculia.me.uk/?view=category&id=10)
- Cornell note‑taking templates provide immediate scaffolds (printable + Google Docs). [3](https://dyslexiaassociation.org.au/support/)
- Pomodoro focus timer adds simple, browser‑based time‑boxing for students. [4](https://www.blocksuniverse.tv/numberblocks/home)
- Assessment add‑ons: ReadWriteThink’s notetaker/rubrics, Maths Hub Number Check, Ochre assessment library, and NCCD evidence tools. [5](https://www.microsoft.com/en-us/edge/features/immersive-reader)[6](https://www.australiancurriculum.edu.au/student-diversity/eal-d-students)[7](https://education.nsw.gov.au/teaching-and-learning/multicultural-education/english-as-an-additional-language-or-dialect/resources)[8](https://apps.mathlearningcenter.org/math-clock/)

**Post‑merge**
- Bypass cache to confirm:  
  `…/thrivehub/library.html?v=v82`
- If Home has final brand colours, update the CSS tokens at the top of `library.html`:

```css
:root{
  --brand:#0E7C86;   /* primary */
  --accent:#673AB7;  /* secondary */
  --bg:#f7fafc;
  --surface:#ffffff;
  --text:#1f2937;
  --muted:#64748b;
}
### ThriveHub: Library visual refresh + new sections

- Removed any visible developer tips; moved deployment notes to HTML comment.
- Added **visual headers (SVG thumbs)** to every category card.
- Added a simple **inline SVG logo** in the top nav (no external assets).
- Added sections:
  - **Executive Function & Study Skills** (Learning Scientists, EEF, Cornell templates, Pomodoro)
  - **Assessment Templates & Tools** (ReadWriteThink rubric & notetaker, Maths Hub Number Check, Ochre, NCCD)
- All links remain **relative**; page works under `/thrivehub/`.

Cache‑bust after merge:
```
https://<user>.github.io/thrivehub/library.html?v=v82
```

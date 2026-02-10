<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Calm Space | ThriveHub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #0f172a; color: #ffffff; font-family: sans-serif; display: flex; flex-direction: column; align-items: center; justify-content: center; min-h-screen; }
        .breath-circle {
            width: 200px; height: 200px; border-radius: 50%;
            background: rgba(34, 211, 238, 0.2);
            border: 4px solid #22d3ee;
            animation: breathe 8s infinite ease-in-out;
            margin: 40px auto;
        }
        @keyframes breathe {
            0%, 100% { transform: scale(1); opacity: 0.5; }
            50% { transform: scale(1.8); opacity: 1; }
        }
    </style>
</head>
<body class="p-10">
    <div class="logo-circle" style="width:30px; height:30px; background:#22d3ee; border-radius:50% 50% 0 50%; position:absolute; top:40px; left:40px;"></div>
    <a href="index.html" class="absolute top-10 right-10 text-[#22d3ee] font-black">← BACK HOME</a>
    
    <div class="text-center mt-20">
        <h1 class="text-5xl font-black italic mb-4">The Calm Space</h1>
        <p class="text-xl text-slate-400 mb-10 tracking-widest uppercase">Breathe with the circle</p>
        <div class="breath-circle"></div>
        <h2 class="text-2xl font-bold mt-10 text-slate-500 uppercase tracking-[1rem]">Inhale ... Exhale</h2>
    </div>
</body>
</html>
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

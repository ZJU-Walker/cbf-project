---
layout: page
title: Home
robots: NOINDEX
---

<style>
/* --- Card-like sections for jekyll-theme-console --- */
:root{
  --panel-bg: rgba(255,255,255,0.04);
  --panel-border: rgba(255,255,255,0.14);
  --panel-shadow: 0 10px 30px rgba(0,0,0,0.35);
  --muted: rgba(255,255,255,0.75);
  --accent: rgba(0,255,180,0.9);
}

/* Make content not overly wide on large screens */
.page-content, .container, main, article {
  max-width: 980px;
  margin-left: auto;
  margin-right: auto;
}

/* Panels */
.panel{
  background: var(--panel-bg);
  border: 1px solid var(--panel-border);
  border-radius: 14px;
  box-shadow: var(--panel-shadow);
  padding: 18px 18px;
  margin: 16px 0;
}

.panel h2, .panel h3{
  margin-top: 0;
}

/* Hero */
.hero-title{
  font-size: 34px;
  line-height: 1.15;
  margin: 0 0 6px 0;
}
.hero-tagline{
  margin: 0;
  color: var(--muted);
}
.badges{
  margin-top: 12px;
  display:flex;
  gap:10px;
  flex-wrap: wrap;
}
.badge{
  border: 1px solid var(--panel-border);
  border-radius: 999px;
  padding: 4px 10px;
  font-size: 13px;
  color: var(--muted);
}

/* Callout line */
.callout{
  border-left: 3px solid var(--accent);
  padding-left: 12px;
  color: var(--muted);
  margin: 12px 0 0 0;
}

/* Video embed */
.video-wrap{
  max-width: 900px;
  margin: 12px auto 0 auto;
  position: relative;
  padding-top: 56.25%;
  border: 1px solid var(--panel-border);
  border-radius: 12px;
  overflow: hidden;
}
.video-wrap iframe{
  position:absolute;
  inset:0;
  width:100%;
  height:100%;
  border:0;
}

/* Small footer note */
.note{
  color: var(--muted);
  font-size: 13px;
}
</style>

<section class="panel">
  <div class="hero-title">Project Title <span style="color:var(--muted);font-size:16px;">(Unpublished)</span></div>
  <p class="hero-tagline">One-line tagline goes here. Brief, specific, and non-sensitive.</p>

  <div class="badges">
    <span class="badge">Intro</span>
    <span class="badge">Video</span>
    <span class="badge">Coming soon</span>
  </div>

  <p class="callout">
    This project is under review / unpublished. Please do not redistribute without permission.
  </p>
</section>

<section class="panel" id="intro">
  <h2>Intro</h2>

  <p>
    <strong>[PLACEHOLDER INTRO]</strong>
    Write 4–8 lines here. Recommended structure:
  </p>

  <ul>
    <li><strong>Problem:</strong> 1–2 sentences describing the setting and challenge.</li>
    <li><strong>Approach:</strong> 1–2 sentences describing your core idea.</li>
    <li><strong>Result:</strong> 1 sentence describing what the demo shows / takeaway.</li>
  </ul>

  <p class="note">
    Tip: keep it high-level for unpublished work (no exact numbers / secret details).
  </p>
</section>

<section class="panel" id="video">
  <h2>Video</h2>

  <p class="note">
    Replace <code>VIDEO_ID</code> with your YouTube ID.
    If you use Bilibili, tell me the BV number and I’ll paste the embed code.
  </p>

  <div class="video-wrap">
    <iframe
      src="https://www.youtube.com/embed/VIDEO_ID?rel=0&modestbranding=1"
      title="Project demo video"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen></iframe>
  </div>
</section>

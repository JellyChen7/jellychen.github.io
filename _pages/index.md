---
permalink: /
title: " "
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">

<style>
/* ── reset & base ─────────────────────────────── */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

.gc-root {
  font-family: 'DM Sans', sans-serif;
  font-weight: 400;
  color: #1a1a1a;
  line-height: 1.7;
  max-width: 780px;
}

/* ── hero ─────────────────────────────────────── */
.gc-hero {
  padding: 48px 0 40px;
  border-bottom: 1px solid #e8e4dc;
  margin-bottom: 40px;
}
.gc-name {
  font-family: 'DM Serif Display', serif;
  font-size: 2.6rem;
  font-weight: 400;
  letter-spacing: -.5px;
  color: #0f0f0f;
  line-height: 1.15;
  margin-bottom: 6px;
}
.gc-role {
  font-size: 0.95rem;
  color: #555;
  margin-bottom: 16px;
  font-weight: 300;
}
.gc-affils {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-bottom: 20px;
}
.gc-pill {
  display: inline-block;
  font-size: 0.72rem;
  font-weight: 500;
  letter-spacing: .04em;
  text-transform: uppercase;
  padding: 4px 10px;
  border: 1px solid #c8c0b0;
  border-radius: 2px;
  color: #555;
  background: #faf9f6;
}
.gc-links {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}
.gc-links a {
  font-size: 0.82rem;
  color: #2a5caa;
  text-decoration: none;
  font-weight: 500;
  border-bottom: 1px solid transparent;
  padding-bottom: 1px;
  transition: border-color .15s;
}
.gc-links a:hover { border-color: #2a5caa; }

/* ── stats bar ────────────────────────────────── */
.gc-stats {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1px;
  background: #e8e4dc;
  border: 1px solid #e8e4dc;
  border-radius: 4px;
  overflow: hidden;
  margin-bottom: 48px;
}
.gc-stat {
  background: #faf9f6;
  padding: 16px 18px;
  text-align: center;
}
.gc-stat-n {
  font-family: 'DM Serif Display', serif;
  font-size: 1.9rem;
  color: #0f0f0f;
  line-height: 1;
  margin-bottom: 4px;
}
.gc-stat-l {
  font-size: 0.7rem;
  text-transform: uppercase;
  letter-spacing: .06em;
  color: #888;
  font-weight: 500;
}

/* ── section ──────────────────────────────────── */
.gc-section {
  margin-bottom: 52px;
}
.gc-section-label {
  font-size: 0.68rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: .1em;
  color: #aaa;
  margin-bottom: 18px;
  padding-bottom: 10px;
  border-bottom: 1px solid #e8e4dc;
}

/* ── narrative ────────────────────────────────── */
.gc-narrative p {
  font-size: 0.97rem;
  color: #333;
  line-height: 1.8;
  margin-bottom: 14px;
}
.gc-narrative strong {
  font-weight: 500;
  color: #0f0f0f;
}
.gc-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 18px;
}
.gc-tag {
  font-size: 0.73rem;
  padding: 4px 11px;
  border-radius: 2px;
  font-weight: 500;
  letter-spacing: .03em;
}
.gc-tag-blue  { background: #eaf1fb; color: #1a4a8c; border: 1px solid #c2d6f0; }
.gc-tag-green { background: #eaf4ec; color: #1a5c2e; border: 1px solid #b8dfc0; }
.gc-tag-sand  { background: #f7f3ec; color: #6b4c1e; border: 1px solid #ddd0bc; }


/* ── education / academic formation ──────────── */
.gc-edu-intro {
  font-size: 0.94rem;
  color: #4a4a4a;
  line-height: 1.8;
  margin-bottom: 26px;
  max-width: 710px;
}
.gc-edu-intro strong {
  color: #161616;
  font-weight: 500;
}
.gc-edu-timeline {
  position: relative;
}
.gc-edu-timeline::before {
  content: "";
  position: absolute;
  left: 86px;
  top: 12px;
  bottom: 14px;
  width: 1px;
  background: #ddd7cc;
}
.gc-edu-item {
  display: grid;
  grid-template-columns: 72px 1fr;
  gap: 30px;
  position: relative;
  padding-bottom: 26px;
}
.gc-edu-item:last-child { padding-bottom: 0; }
.gc-edu-item::before {
  content: "";
  position: absolute;
  left: 82px;
  top: 11px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: #faf9f6;
  border: 2px solid #2a5caa;
  z-index: 2;
}
.gc-edu-years {
  font-family: 'DM Serif Display', serif;
  font-size: 0.86rem;
  color: #777;
  line-height: 1.35;
  padding-top: 3px;
  text-align: right;
  white-space: nowrap;
}
.gc-edu-card {
  position: relative;
  padding: 20px 22px 19px;
  border: 1px solid #e4dfd5;
  border-radius: 6px;
  background: linear-gradient(135deg, #ffffff 0%, #fcfbf8 100%);
  box-shadow: 0 6px 20px rgba(30, 30, 25, 0.035);
  transition: transform .18s ease, box-shadow .18s ease, border-color .18s ease;
  overflow: hidden;
}
.gc-edu-card:hover {
  transform: translateY(-2px);
  border-color: #d5cec1;
  box-shadow: 0 10px 28px rgba(30, 30, 25, 0.06);
}
.gc-edu-card::after {
  content: attr(data-mark);
  position: absolute;
  right: 16px;
  top: 7px;
  font-family: 'DM Serif Display', serif;
  font-size: 3.4rem;
  line-height: 1;
  color: rgba(42, 92, 170, 0.045);
  letter-spacing: -.06em;
  pointer-events: none;
}
.gc-edu-inst {
  font-size: 0.69rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: .085em;
  color: #2a5caa;
  margin-bottom: 5px;
  padding-right: 64px;
}
.gc-edu-degree {
  font-family: 'DM Serif Display', serif;
  font-size: 1.13rem;
  font-weight: 400;
  color: #111;
  line-height: 1.35;
  margin-bottom: 5px;
  padding-right: 44px;
}
.gc-edu-meta {
  font-size: 0.79rem;
  color: #858585;
  margin-bottom: 12px;
}
.gc-edu-desc {
  font-size: 0.86rem;
  color: #4d4d4d;
  line-height: 1.7;
  margin-bottom: 11px;
}
.gc-edu-desc strong {
  color: #222;
  font-weight: 500;
}
.gc-edu-details {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-top: 10px;
}
.gc-edu-chip {
  display: inline-block;
  font-size: 0.66rem;
  line-height: 1.2;
  padding: 4px 8px;
  border: 1px solid #ddd6c9;
  border-radius: 2px;
  color: #665c4e;
  background: #faf7f1;
  font-weight: 500;
  letter-spacing: .02em;
}
.gc-edu-chip-award {
  color: #6b4c1e;
  background: #f8f2e8;
  border-color: #dfcfb5;
}
.gc-edu-footnote {
  margin: 22px 0 0 102px;
  padding: 12px 15px;
  border-left: 2px solid #c6d7ee;
  background: #f8fafc;
  font-size: 0.78rem;
  color: #66717d;
  line-height: 1.65;
}

/* ── pub cards ────────────────────────────────── */
.gc-pub {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 12px;
  align-items: start;
  padding: 16px 0;
  border-bottom: 1px solid #e8e4dc;
}
.gc-pub:first-child { border-top: 1px solid #e8e4dc; }
.gc-pub-num {
  font-family: 'DM Serif Display', serif;
  font-size: 0.85rem;
  color: #bbb;
  min-width: 24px;
  padding-top: 2px;
}
.gc-pub-body { flex: 1; }
.gc-pub-title {
  font-size: 0.92rem;
  font-weight: 500;
  color: #0f0f0f;
  line-height: 1.4;
  margin-bottom: 4px;
}
.gc-pub-title a {
  color: inherit;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color .15s;
}
.gc-pub-title a:hover { border-color: #0f0f0f; }
.gc-pub-venue {
  font-size: 0.8rem;
  color: #777;
  margin-bottom: 7px;
}
.gc-pub-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 5px;
}
.gc-badge {
  font-size: 0.65rem;
  text-transform: uppercase;
  letter-spacing: .05em;
  font-weight: 500;
  padding: 2px 7px;
  border-radius: 2px;
}
.gc-badge-ni    { background: #f0eef9; color: #3d2f8f; border: 1px solid #cec6f0; }
.gc-badge-if    { background: #eaf4ec; color: #1a5c2e; border: 1px solid #b8dfc0; }
.gc-badge-cell  { background: #fdf0e8; color: #8c3a10; border: 1px solid #f0c8a8; }
.gc-badge-code  { background: #f1f1ee; color: #444; border: 1px solid #d0d0c8; }
.gc-pub-year {
  font-size: 0.78rem;
  color: #bbb;
  font-weight: 300;
  white-space: nowrap;
  padding-top: 3px;
}

/* ── awards row ───────────────────────────────── */
.gc-award {
  display: flex;
  gap: 14px;
  align-items: baseline;
  padding: 10px 0;
  border-bottom: 1px solid #f0ece4;
  font-size: 0.88rem;
}
.gc-award:first-child { border-top: 1px solid #f0ece4; }
.gc-award-pct {
  min-width: 36px;
  font-family: 'DM Serif Display', serif;
  font-size: 1rem;
  color: #2a5caa;
  font-weight: 400;
}
.gc-award-name { color: #222; flex: 1; }
.gc-award-inst { font-size: 0.78rem; color: #999; }

/* ── responsive ───────────────────────────────── */
@media (max-width: 600px) {
  .gc-name { font-size: 2rem; }
  .gc-stats { grid-template-columns: repeat(2, 1fr); }
  .gc-edu-timeline::before { left: 7px; }
  .gc-edu-item { grid-template-columns: 1fr; gap: 8px; padding-left: 24px; }
  .gc-edu-item::before { left: 3px; top: 7px; }
  .gc-edu-years { text-align: left; padding-top: 0; font-family: 'DM Sans', sans-serif; font-size: 0.72rem; color: #999; }
  .gc-edu-card { padding: 17px 18px 16px; }
  .gc-edu-card::after { font-size: 2.8rem; }
  .gc-edu-footnote { margin-left: 24px; }
}
</style>

<div class="gc-root">

<!-- HERO -->

<div class="gc-hero">
  <h1 class="gc-name">Guodong Chen</h1>
  <p class="gc-role">Postdoctoral Researcher &nbsp;·&nbsp; UC Berkeley &amp; Lawrence Berkeley National Laboratory</p>
  <div class="gc-affils">
    <span class="gc-pill">UC Berkeley</span>
    <span class="gc-pill">LBNL</span>
    <span class="gc-pill">Cornell (prev.)</span>
    <span class="gc-pill">HKU PhD</span>
    <span class="gc-pill">CUP-East China</span>
  </div>
  <div class="gc-links">
    <a href="https://jellychen7.github.io/jellychen.github.io/files/cv.pdf">Curriculum Vitae (PDF)</a>
    <a href="mailto:guodong.chen@berkeley.edu">Email</a>
    <a href="https://github.com/JellyChen7">GitHub</a>
    <a href="https://scholar.google.com/citations?user=U2YFkAgAAAAJ&hl=zh-CN&authuser=1&oi=ao">Google Scholar</a>
  </div>
</div>

<!-- STATS -->

<div class="gc-stats">
  <div class="gc-stat">
    <div class="gc-stat-n">40+</div>
    <div class="gc-stat-l">Publications</div>
  </div>
  <div class="gc-stat">
    <div class="gc-stat-n">1,800+</div>
    <div class="gc-stat-l">Citations</div>
  </div>
  <div class="gc-stat">
    <div class="gc-stat-n">21</div>
    <div class="gc-stat-l">h-index</div>
  </div>
  <div class="gc-stat">
    <div class="gc-stat-n">3</div>
    <div class="gc-stat-l">Highly cited papers</div>
  </div>
</div>

<!-- RESEARCH NARRATIVE -->

<div class="gc-section">
  <div class="gc-section-label">Research</div>
  <div class="gc-narrative">
    <p>
      I develop <strong>generative AI and foundation models for subsurface geoscience</strong> — 
      accelerating simulation, design, and discovery for energy systems at the heart of the climate transition.
      My work sits at the intersection of diffusion models, physics-informed learning, and 
      multi-objective optimization, applied to CO₂ sequestration, geothermal energy, fracture characterisation, 
      and underground hydrogen storage.
    </p>
    <p>
      A thread running through all my work: <strong>replacing expensive physical simulations with 
      AI surrogates that preserve the underlying physics</strong>, while enabling decisions at reservoir 
      scale and over climate-relevant timescales. I build tools that close the loop between data, 
      simulation, and optimal design — from pore-scale fluid dynamics to field-scale production systems.
    </p>
    <p>
      I am actively building towards an independent research program that bridges 
      <strong>scientific machine learning, subsurface energy systems, and sustainable engineering</strong>, 
      with a long-term vision of developing foundation models for the geosciences.
    </p>
    <div class="gc-tags">
      <span class="gc-tag gc-tag-blue">Diffusion models</span>
      <span class="gc-tag gc-tag-blue">Foundation models</span>
      <span class="gc-tag gc-tag-blue">Physics-informed ML</span>
      <span class="gc-tag gc-tag-green">CO₂ sequestration</span>
      <span class="gc-tag gc-tag-green">Geothermal systems</span>
      <span class="gc-tag gc-tag-green">H₂ storage</span>
      <span class="gc-tag gc-tag-sand">Surrogate optimisation</span>
      <span class="gc-tag gc-tag-sand">Fracture inversion</span>
      <span class="gc-tag gc-tag-sand">Data assimilation</span>
    </div>
  </div>
</div>

<!-- EDUCATION -->

<div class="gc-section">
  <div class="gc-section-label">Education</div>
  <p class="gc-edu-intro">
    My academic training spans <strong>petroleum engineering, reservoir development, and hydrogeology</strong>,
    providing a cross-disciplinary foundation for research on AI-enabled subsurface science. This progression
    from engineered energy reservoirs to natural subsurface systems now underpins my work in scientific machine
    learning, geothermal energy, geological CO₂ storage, and physics-grounded AI.
  </p>

  <div class="gc-edu-timeline">
    <div class="gc-edu-item">
      <div class="gc-edu-years">2021<br>— 2025</div>
      <div class="gc-edu-card" data-mark="HKU">
        <div class="gc-edu-inst">The University of Hong Kong · Hong Kong</div>
        <div class="gc-edu-degree">Ph.D. in Hydrogeology</div>
        <div class="gc-edu-meta">Supervisor: Prof. Jiu Jimmy Jiao</div>
        <p class="gc-edu-desc">
          Doctoral training at the intersection of <strong>subsurface flow, fractured geothermal systems,
          inverse modelling, and data-driven optimisation</strong>, forming the scientific basis for my later
          work on generative AI and physics-aware learning for subsurface energy systems.
        </p>
        <div class="gc-edu-details">
          <span class="gc-edu-chip gc-edu-chip-award">HKIE Ringo Yu Prize for Best PhD Thesis</span>
          <span class="gc-edu-chip gc-edu-chip-award">HKU Foundation Excellent PhD Award</span>
        </div>
      </div>
    </div>

<div class="gc-edu-item">
  <div class="gc-edu-years">2018<br>— 2021</div>
  <div class="gc-edu-card" data-mark="CUP">
    <div class="gc-edu-inst">China University of Petroleum (East China) · Qingdao</div>
    <div class="gc-edu-degree">M.Sc. in Oil &amp; Gas Development Engineering</div>
    <div class="gc-edu-meta">Full English Program · Supervisor: Prof. Kai Zhang</div>
    <p class="gc-edu-desc">
      Advanced training in <strong>reservoir engineering, production optimisation, and computational
      modelling</strong>, with an increasing emphasis on machine-learning-assisted optimisation of complex
      subsurface energy systems.
    </p>
    <div class="gc-edu-details">
      <span class="gc-edu-chip gc-edu-chip-award">Outstanding Master’s Thesis of Shandong Province</span>
      <span class="gc-edu-chip">Scientific computing &amp; optimisation</span>
    </div>
  </div>
</div>

<div class="gc-edu-item">
  <div class="gc-edu-years">2014<br>— 2018</div>
  <div class="gc-edu-card" data-mark="CUP">
    <div class="gc-edu-inst">China University of Petroleum (East China) · Qingdao</div>
    <div class="gc-edu-degree">B.Eng. in Petroleum Engineering</div>
    <div class="gc-edu-meta">Undergraduate education in subsurface energy engineering</div>
    <p class="gc-edu-desc">
      Built a rigorous engineering foundation in <strong>reservoir development, fluid flow, drilling and
      production systems</strong>, which established my long-term interest in quantitative subsurface science
      and computational decision-making.
    </p>
    <div class="gc-edu-details">
      <span class="gc-edu-chip gc-edu-chip-award">National Scholarship · China Ministry of Education</span>
      <span class="gc-edu-chip">Petroleum &amp; reservoir engineering</span>
    </div>
  </div>
</div>

  </div>

  <div class="gc-edu-footnote">
    <strong>Academic trajectory.</strong> Engineering the subsurface → understanding the subsurface →
    building intelligent systems that can simulate, infer, and ultimately support scientific discovery and decision-making.
  </div>
</div>

<!-- SELECTED PUBLICATIONS -->

<div class="gc-section">
  <div class="gc-section-label">Selected publications</div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://www.sciencedirect.com/science/article/pii/S0306261926000899">Energy-efficient greenhouse climate control with diffusion reinforcement learning</a>
      </p>
      <p class="gc-pub-venue">Applied Energy (Nature Index) · IF 12.2 · 2026</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-if">IF 12.2</span>
        <span class="gc-badge gc-badge-code">Nature Index</span>
      </div>
    </div>
    <span class="gc-pub-year">2026</span>
  </div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11224780">Expensive multi-objective optimization guided by attention-enhanced generative models</a>
      </p>
      <p class="gc-pub-venue">IEEE Transactions on Neural Networks and Learning Systems · IF 9.7</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-if">IF 9.7</span>
      </div>
    </div>
    <span class="gc-pub-year">2025</span>
  </div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://www.cell.com/nexus/fulltext/S2950-1601(24)00042-1">Machine learning-accelerated multi-objective design of fractured geothermal systems</a>
      </p>
      <p class="gc-pub-venue">Nexus · Cell Press · 2024</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-cell">Cell Press</span>
        <span class="gc-badge gc-badge-code">Code</span>
      </div>
    </div>
    <span class="gc-pub-year">2024</span>
  </div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S1364032123007189">Surrogate-assisted level-based learning evolutionary search for geothermal heat extraction optimisation</a>
      </p>
      <p class="gc-pub-venue">Renewable and Sustainable Energy Reviews · IF 18.0 · 2024</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-if">IF 18.0</span>
      </div>
    </div>
    <span class="gc-pub-year">2024</span>
  </div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://ager.yandypress.com/index.php/2207-9963/article/view/506/524">Multi-fidelity machine learning with knowledge transfer enhances geothermal energy system design</a>
      </p>
      <p class="gc-pub-venue">Advances in Geo-Energy Research · IF 11.2 · 2025</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-if">IF 11.2</span>
      </div>
    </div>
    <span class="gc-pub-year">2025</span>
  </div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0360544223006965">Fracture network characterisation with deep generative model-based stochastic inversion</a>
      </p>
      <p class="gc-pub-venue">Energy (Nature Index) · IF 10.1 · 2023</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-if">IF 10.1</span>
        <span class="gc-badge gc-badge-code">Nature Index</span>
      </div>
    </div>
    <span class="gc-pub-year">2023</span>
  </div>

  <div class="gc-pub">
    <div>
      <p class="gc-pub-title">
        <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025GL120253?utm_medium=article&utm_source=researchgate.net">Physics‐Supervised Autonomous Inverse Fracture Modeling via Generative Artificial Intelligence</a>
      </p>
      <p class="gc-pub-venue">Geophysical Research Letters (Nature Index) · IF 5.0 · 2026</p>
      <div class="gc-pub-badges">
        <span class="gc-badge gc-badge-if">IF 5.0</span>
        <span class="gc-badge gc-badge-code">Nature Index</span>
      </div>
    </div>
    <span class="gc-pub-year">2026</span>
  </div>

  <p style="margin-top:16px;font-size:0.82rem;color:#888;">
    <a href="https://jellychen7.github.io/jellychen.github.io/publications/" style="color:#2a5caa;text-decoration:none;font-weight:500;border-bottom:1px solid transparent;" onmouseover="this.style.borderColor='#2a5caa'" onmouseout="this.style.borderColor='transparent'">View all publications →</a>
  </p>
</div>

<!-- AWARDS (condensed) -->

<div class="gc-section">
  <div class="gc-section-label">Recognition</div>

  <div class="gc-award">
    <span class="gc-award-pct"></span>
    <span class="gc-award-name">HKIE Ringo Yu Prize for Best PhD Thesis</span>
    <span class="gc-award-inst">HKIE</span>
  </div>
  <div class="gc-award">
    <span class="gc-award-pct"></span>
    <span class="gc-award-name">HKU Foundation Excellent PhD Award</span>
    <span class="gc-award-inst">HKU</span>
  </div>
  <div class="gc-award">
    <span class="gc-award-pct"></span>
    <span class="gc-award-name">Outstanding Master's Thesis of Shandong Province</span>
    <span class="gc-award-inst">Shandong Province</span>
  </div>
  <div class="gc-award">
    <span class="gc-award-pct"></span>
    <span class="gc-award-name">National Scholarship, China Ministry of Education</span>
    <span class="gc-award-inst">China MOE</span>
  </div>

  <p style="margin-top:14px;font-size:0.82rem;color:#888;">
    Full list of awards and scholarships in 
    <a href="https://jellychen7.github.io/jellychen.github.io/files/cv.pdf" style="color:#2a5caa;text-decoration:none;font-weight:500;">CV (PDF)</a>.
  </p>
</div>

<!-- CONFERENCE TALKS (condensed) -->

<div class="gc-section">
  <div class="gc-section-label">Selected talks</div>
  <div class="gc-award">
    <span class="gc-award-pct" style="font-size:0.75rem;color:#aaa;min-width:44px;">AGU 2024</span>
    <span class="gc-award-name" style="font-size:0.88rem;">Machine learning-enabled discovery of optimal fractured geothermal system design <em style="color:#aaa;font-size:0.8rem;">(oral)</em></span>
  </div>
  <div class="gc-award">
    <span class="gc-award-pct" style="font-size:0.75rem;color:#aaa;min-width:44px;">AGU 2024</span>
    <span class="gc-award-name" style="font-size:0.88rem;">Accelerated generative inversion of fracture networks via diffusion models <em style="color:#aaa;font-size:0.8rem;">(poster)</em></span>
  </div>
  <div class="gc-award">
    <span class="gc-award-pct" style="font-size:0.75rem;color:#aaa;min-width:44px;">AGU 2023</span>
    <span class="gc-award-name" style="font-size:0.88rem;">Deep learning enhanced evolutionary multi-objective optimisation for geothermal systems <em style="color:#aaa;font-size:0.8rem;">(poster)</em></span>
  </div>
  <div class="gc-award">
    <span class="gc-award-pct" style="font-size:0.75rem;color:#aaa;min-width:44px;">EGU 2023</span>
    <span class="gc-award-name" style="font-size:0.88rem;">Classifier-assisted level-based evolutionary search for geothermal heat extraction <em style="color:#aaa;font-size:0.8rem;">(poster)</em></span>
  </div>
</div>

<!-- REVIEWER SERVICE -->

<div class="gc-section">
  <div class="gc-section-label">Reviewer service</div>
  <p style="font-size:0.85rem;color:#555;line-height:2;">
    Applied Energy &nbsp;·&nbsp; Geophysical Research Letters &nbsp;·&nbsp; Water Resources Research &nbsp;·&nbsp;
    IEEE Trans. Evolutionary Computation &nbsp;·&nbsp; IEEE Trans. Neural Networks &nbsp;·&nbsp;
    IEEE Trans. Systems Man Cybernetics &nbsp;·&nbsp; Renewable &amp; Sustainable Energy Reviews &nbsp;·&nbsp;
    SPE Journal &nbsp;·&nbsp; Fuel &nbsp;·&nbsp; Journal of Hydrology &nbsp;·&nbsp;
    Information Sciences &nbsp;·&nbsp; Applied Soft Computing &nbsp;·&nbsp;
    Computational Geosciences &nbsp;+&nbsp; 10 others
  </p>
</div>

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=300&t=tt&d=ewcit6dbr21sN_H1W7FrIsT7oGsPAbBWnjn2ZH1UI8U&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>

<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=ucQPKPnN4O5zRRYSv11g1dxvQtRDXVKmw09uWFLjL3I&cl=ffffff&w=a"></script>

</div>

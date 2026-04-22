---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
.gc-root { font-family: 'DM Sans', sans-serif; color: #1a1a1a; line-height: 1.7; max-width: 720px; }
.gc-section-label {
  font-size: 0.68rem; font-weight: 500; text-transform: uppercase;
  letter-spacing: .1em; color: #aaa; margin-bottom: 18px;
  padding-bottom: 10px; border-bottom: 1px solid #e8e4dc; margin-top: 44px;
}
.gc-intro { font-size: 1.05rem; color: #222; line-height: 1.8; margin-bottom: 14px; font-weight: 300; }
.gc-intro strong { font-weight: 500; color: #0f0f0f; }
.gc-body  { font-size: 0.95rem; color: #444; line-height: 1.8; margin-bottom: 14px; }
.gc-theme-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 14px; margin-top: 8px; }
.gc-theme {
  border: 1px solid #e8e4dc; border-radius: 4px;
  padding: 18px 20px; background: #faf9f6;
}
.gc-theme-title { font-size: 0.9rem; font-weight: 500; color: #0f0f0f; margin-bottom: 6px; }
.gc-theme-body  { font-size: 0.82rem; color: #666; line-height: 1.6; }
.gc-theme-tag {
  display: inline-block; font-size: 0.65rem; font-weight: 500;
  text-transform: uppercase; letter-spacing: .05em;
  padding: 2px 7px; border-radius: 2px; margin-bottom: 8px;
}
.t-blue  { background: #eaf1fb; color: #1a4a8c; border: 1px solid #c2d6f0; }
.t-green { background: #eaf4ec; color: #1a5c2e; border: 1px solid #b8dfc0; }
.t-sand  { background: #f7f3ec; color: #6b4c1e; border: 1px solid #ddd0bc; }
.t-purple{ background: #f0eef9; color: #3d2f8f; border: 1px solid #cec6f0; }
.gc-project {
  padding: 18px 0; border-bottom: 1px solid #e8e4dc;
  display: grid; grid-template-columns: 1fr auto; gap: 12px; align-items: start;
}
.gc-project:first-of-type { border-top: 1px solid #e8e4dc; }
.gc-project-title { font-size: 0.92rem; font-weight: 500; color: #0f0f0f; margin-bottom: 4px; }
.gc-project-title a { color: inherit; text-decoration: none; border-bottom: 1px solid transparent; transition: border-color .15s; }
.gc-project-title a:hover { border-color: #0f0f0f; }
.gc-project-desc { font-size: 0.82rem; color: #666; line-height: 1.6; margin-bottom: 7px; }
.gc-badge {
  font-size: 0.65rem; text-transform: uppercase; letter-spacing: .05em;
  font-weight: 500; padding: 2px 7px; border-radius: 2px;
}
.gc-badge-ni   { background: #f0eef9; color: #3d2f8f; border: 1px solid #cec6f0; }
.gc-badge-if   { background: #eaf4ec; color: #1a5c2e; border: 1px solid #b8dfc0; }
.gc-badge-cell { background: #fdf0e8; color: #8c3a10; border: 1px solid #f0c8a8; }
.gc-badge-code { background: #f1f1ee; color: #444;    border: 1px solid #d0d0c8; }
.gc-project-year { font-size: 0.78rem; color: #bbb; white-space: nowrap; padding-top: 3px; }
@media (max-width: 600px) { .gc-theme-grid { grid-template-columns: 1fr; } }
</style>

<div class="gc-root">

<div class="gc-section-label">Vision</div>
<p class="gc-intro">
  My research develops <strong>generative AI and foundation models for the geosciences</strong> — 
  building the computational tools needed to accelerate simulation, design, and discovery 
  in subsurface energy systems at the scale and speed the climate transition demands.
</p>
<p class="gc-body">
  Physical simulation of the subsurface — whether for CO₂ storage site selection, geothermal 
  field optimisation, or fracture network characterisation — is extraordinarily expensive. 
  A single reservoir simulation can take hours to days; ensemble runs for uncertainty 
  quantification are often computationally infeasible. This creates a fundamental bottleneck 
  for both science and engineering decisions.
</p>
<p class="gc-body">
  My research attacks this bottleneck from three directions: (1) <strong>generative AI 
  surrogates</strong> that replace expensive forward simulations while preserving physical 
  consistency; (2) <strong>inverse modelling</strong> that reconstructs subsurface structure 
  from sparse observations; and (3) <strong>AI-guided optimisation</strong> that identifies 
  optimal system designs with minimal simulation budget. Together, these form a foundation 
  for an AI-native approach to geoscience.
</p>

<div class="gc-section-label">Research themes</div>
<div class="gc-theme-grid">
  <div class="gc-theme">
    <div class="gc-theme-tag t-blue">Theme 1</div>
    <div class="gc-theme-title">Generative models for subsurface flow</div>
    <p class="gc-theme-body">Diffusion models and flow-matching networks as fast, physics-consistent surrogates for spatiotemporal fluid flow in fractured and porous media. Core application: CO₂ plume prediction and uncertainty quantification at storage sites.</p>
  </div>
  <div class="gc-theme">
    <div class="gc-theme-tag t-green">Theme 2</div>
    <div class="gc-theme-title">AI-accelerated geothermal &amp; energy system design</div>
    <p class="gc-theme-body">Multi-objective, surrogate-assisted evolutionary algorithms for optimal well placement, fracture stimulation, and heat extraction in geothermal systems. Extends to underground H₂ storage and CO₂-EOR.</p>
  </div>
  <div class="gc-theme">
    <div class="gc-theme-tag t-sand">Theme 3</div>
    <div class="gc-theme-title">Physics-supervised inverse fracture modelling</div>
    <p class="gc-theme-body">Autonomous inversion of fracture network geometry from hydraulic and tracer test data using generative AI constrained by physical laws — enabling characterisation without expensive direct observation.</p>
  </div>
  <div class="gc-theme">
    <div class="gc-theme-tag t-purple">Theme 4</div>
    <div class="gc-theme-title">Foundation models for geoscience</div>
    <p class="gc-theme-body">Long-term vision: pre-trained geoscience foundation models that generalise across reservoir types, scales, and tasks — reducing the data and compute requirements for new subsurface projects.</p>
  </div>
</div>

<div class="gc-section-label">Selected projects</div>

<div class="gc-project">
  <div>
    <p class="gc-project-title"><a href="https://github.com/JellyChen7/FracCGM">Diffusion models for subsurface fractured flow prediction (FracCGM)</a></p>
    <p class="gc-project-desc">A conditional diffusion model trained to predict spatiotemporal pressure and saturation fields in fractured media — replacing Lattice-Boltzmann simulations at ~1000× speedup. Under review at JGR: Solid Earth.</p>
    <div style="display:flex;gap:5px;flex-wrap:wrap">
      <span class="gc-badge gc-badge-ni">Nature Index</span>
      <span class="gc-badge gc-badge-code">Code available</span>
    </div>
  </div>
  <span class="gc-project-year">2025</span>
</div>

<div class="gc-project">
  <div>
    <p class="gc-project-title"><a href="https://github.com/JellyChen7/GenFrac">Physics-supervised generative fracture inversion (GenFrac)</a></p>
    <p class="gc-project-desc">Autonomous inverse fracture modelling using generative AI supervised by physical consistency constraints — characterising fracture networks from sparse well and seismic data without direct observation.</p>
    <div style="display:flex;gap:5px;flex-wrap:wrap">
      <span class="gc-badge gc-badge-ni">Nature Index (GRL)</span>
      <span class="gc-badge gc-badge-code">Code available</span>
    </div>
  </div>
  <span class="gc-project-year">2025</span>
</div>

<div class="gc-project">
  <div>
    <p class="gc-project-title"><a href="https://www.cell.com/nexus/fulltext/S2950-1601(24)00042-1">ML-accelerated multi-objective geothermal system design (ALEMO)</a></p>
    <p class="gc-project-desc">Active learning enhanced multi-objective evolutionary optimisation (ALEMO) for fractured geothermal systems — simultaneously maximising heat extraction, minimising CO₂ footprint, and managing thermal breakthrough risk.</p>
    <div style="display:flex;gap:5px;flex-wrap:wrap">
      <span class="gc-badge gc-badge-cell">Cell Press · Nexus</span>
      <span class="gc-badge gc-badge-code">Code available</span>
    </div>
  </div>
  <span class="gc-project-year">2024</span>
</div>

<div class="gc-project">
  <div>
    <p class="gc-project-title">Diffusion reinforcement learning for energy-efficient greenhouse control</p>
    <p class="gc-project-desc">Diffusion-based policy models for climate control in controlled environment agriculture — balancing crop yield, energy consumption, and resilience to external climate disturbances.</p>
    <div style="display:flex;gap:5px;flex-wrap:wrap">
      <span class="gc-badge gc-badge-if">Applied Energy · IF 11.0</span>
    </div>
  </div>
  <span class="gc-project-year">2025</span>
</div>

<div class="gc-section-label">Funding &amp; collaborations</div>
<p class="gc-body">
  Current and past research has been supported by or conducted within:
</p>
<ul style="font-size:0.88rem;color:#555;line-height:2;padding-left:18px;margin-top:8px;">
  <li>USDA ADVANCEA grant — Advancing Controlled Environment Agriculture (US$3.77M, Cornell/You lab)</li>
  <li>Research Grants Council Hong Kong — Poshan drainage tunnel hillslope observatory (HK$2.79M)</li>
  <li>Research Grants Council Hong Kong — Digital twin landslide risk management (HK$2.506M)</li>
</ul>

</div>

---
permalink: /
title: " "
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-page {
  max-width: 780px;
  color: #242424;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  line-height: 1.72;
}

.home-page * { box-sizing: border-box; }

.home-hero {
  padding: 2.4rem 0 1.6rem;
}

.home-name {
  margin: 0 0 .25rem;
  color: #111;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 2.45rem;
  font-weight: 400;
  line-height: 1.15;
}

.home-role {
  margin: 0 0 .45rem;
  color: #4c4c4c;
  font-size: .98rem;
}

.home-affiliation {
  margin: 0 0 1rem;
  color: #777;
  font-size: .84rem;
}

.home-links {
  display: flex;
  flex-wrap: wrap;
  gap: .55rem 1.15rem;
}

.home-links a {
  color: #24558a;
  font-size: .81rem;
  font-weight: 500;
  text-decoration: none;
  border-bottom: 1px solid transparent;
}

.home-links a:hover { border-bottom-color: #24558a; }

.home-campus {
  position: relative;
  min-height: 215px;
  margin: 0 0 .4rem;
  border-radius: 3px;
  overflow: hidden;
  background:
    linear-gradient(to right, rgba(13,25,40,.05), rgba(13,25,40,.12)),
    url("https://upload.wikimedia.org/wikipedia/commons/6/66/UC-Berkeley-001-campanile-way-view-west-from-bottom-of-Sather-Tower.jpg")
    center 46% / cover no-repeat;
}

.home-photo-credit {
  margin: 0 0 2.2rem;
  color: #aaa;
  font-size: .66rem;
  text-align: right;
}

.home-photo-credit a {
  color: inherit;
  text-decoration: none;
}

.home-photo-credit a:hover { text-decoration: underline; }

.home-stats {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  margin-bottom: 2.8rem;
  border-top: 1px solid #dedede;
  border-bottom: 1px solid #dedede;
}

.home-stat {
  padding: 1rem .6rem;
  text-align: center;
  border-right: 1px solid #e5e5e5;
}

.home-stat:last-child { border-right: none; }

.home-stat strong {
  display: block;
  margin-bottom: .15rem;
  color: #111;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1.45rem;
  font-weight: 400;
}

.home-stat span {
  color: #858585;
  font-size: .68rem;
  text-transform: uppercase;
  letter-spacing: .06em;
}

.home-section {
  margin-bottom: 3rem;
}

.home-heading {
  margin: 0 0 1.1rem;
  padding-bottom: .5rem;
  border-bottom: 1px solid #dedede;
  color: #111;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1.18rem;
  font-weight: 400;
}

.home-prose p {
  margin: 0 0 .85rem;
  color: #424242;
  font-size: .94rem;
  line-height: 1.78;
}

.home-prose strong {
  color: #171717;
  font-weight: 600;
}

.home-directions {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.4rem;
  margin-top: 1.35rem;
}

.home-direction {
  padding-top: .8rem;
  border-top: 2px solid #d9d9d9;
}

.home-direction h3 {
  margin: 0 0 .35rem;
  color: #1a1a1a;
  font-family: Georgia, "Times New Roman", serif;
  font-size: .93rem;
  font-weight: 600;
  line-height: 1.35;
}

.home-direction p {
  margin: 0;
  color: #777;
  font-size: .77rem;
  line-height: 1.55;
}

.home-group-label {
  margin: 1.3rem 0 .25rem;
  color: #999;
  font-size: .66rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: .09em;
}

.home-row {
  display: grid;
  grid-template-columns: 112px minmax(0, 1fr);
  gap: 1rem;
  padding: .85rem 0;
  border-bottom: 1px solid #ebebeb;
}

.home-row:first-of-type { border-top: 1px solid #ebebeb; }

.home-date {
  color: #9a9a9a;
  font-size: .74rem;
  white-space: nowrap;
  padding-top: .12rem;
}

.home-row-title {
  color: #1b1b1b;
  font-size: .88rem;
  font-weight: 600;
  line-height: 1.45;
}

.home-row-inst {
  margin-top: .1rem;
  color: #555;
  font-size: .80rem;
  line-height: 1.5;
}

.home-row-meta {
  margin-top: .16rem;
  color: #8a8a8a;
  font-size: .73rem;
  line-height: 1.5;
}

.home-pub {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;
  gap: 1rem;
  padding: .95rem 0;
  border-bottom: 1px solid #e9e9e9;
}

.home-pub:first-of-type { border-top: 1px solid #e2e2e2; }

.home-pub-title {
  margin: 0 0 .18rem;
  color: #171717;
  font-size: .87rem;
  font-weight: 600;
  line-height: 1.5;
}

.home-pub-title a {
  color: inherit;
  text-decoration: none;
}

.home-pub-title a:hover { text-decoration: underline; }

.home-pub-meta {
  margin: 0;
  color: #818181;
  font-size: .74rem;
  line-height: 1.5;
}

.home-year {
  color: #aaa;
  font-size: .73rem;
  white-space: nowrap;
}

.home-more {
  margin-top: .85rem;
  font-size: .78rem;
}

.home-more a {
  color: #24558a;
  text-decoration: none;
}

.home-more a:hover { text-decoration: underline; }

.home-two-col {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2.2rem;
}

.home-compact {
  margin: 0;
  padding: 0;
  list-style: none;
}

.home-compact li {
  padding: .55rem 0;
  border-bottom: 1px solid #ededed;
  color: #555;
  font-size: .80rem;
  line-height: 1.5;
}

.home-compact strong {
  color: #222;
  font-weight: 600;
}

@media (max-width: 680px) {
  .home-name { font-size: 2rem; }
  .home-campus { min-height: 165px; }
  .home-stats { grid-template-columns: repeat(2, 1fr); }
  .home-stat:nth-child(2) { border-right: none; }
  .home-stat:nth-child(-n+2) { border-bottom: 1px solid #e5e5e5; }
  .home-directions { grid-template-columns: 1fr; gap: .85rem; }
  .home-row { grid-template-columns: 1fr; gap: .2rem; }
  .home-date { white-space: normal; }
  .home-two-col { grid-template-columns: 1fr; gap: 1.5rem; }
}
</style>

<div class="home-page">

  <header class="home-hero">
    <h1 class="home-name">Guodong Chen</h1>
    <p class="home-role">Postdoctoral Researcher · UC Berkeley &amp; Lawrence Berkeley National Laboratory</p>
    <p class="home-affiliation">Scientific machine learning · Subsurface energy systems · Computational geoscience</p>
    <div class="home-links">
      <a href="{{ site.url }}{{ site.baseurl }}/files/cv.pdf">Curriculum Vitae</a>
      <a href="mailto:gchen6@lbl.gov">Email</a>
      <a href="https://scholar.google.com/citations?user=U2YFkAgAAAAJ&hl=en">Google Scholar</a>
      <a href="https://orcid.org/0000-0002-5704-638X">ORCID</a>
      <a href="https://github.com/JellyChen7">GitHub</a>
    </div>
  </header>

  <div class="home-campus" role="img" aria-label="Campanile Way at the University of California, Berkeley"></div>
  <p class="home-photo-credit">
    UC Berkeley, Campanile Way ·
    <a href="https://commons.wikimedia.org/wiki/File:UC-Berkeley-001-campanile-way-view-west-from-bottom-of-Sather-Tower.jpg">CC0 image, Wikimedia Commons</a>
  </p>

  <div class="home-stats">
    <div class="home-stat"><strong>40+</strong><span>Journal papers</span></div>
    <div class="home-stat"><strong>1,800+</strong><span>Citations</span></div>
    <div class="home-stat"><strong>21</strong><span>h-index</span></div>
    <div class="home-stat"><strong>3</strong><span>Highly cited papers</span></div>
  </div>

  <section class="home-section">
    <h2 class="home-heading">Research profile</h2>
    <div class="home-prose">
      <p>
        I develop <strong>computational and machine-learning methods for subsurface energy and environmental systems</strong>,
        with particular interests in forward simulation, inverse modelling, uncertainty quantification, and optimization.
        My work addresses problems in geothermal energy, geological CO<sub>2</sub> storage, fractured-media flow,
        and sustainable reservoir development.
      </p>
      <p>
        A recurring objective is to connect physical modelling with modern learning methods so that complex subsurface
        systems can be characterized and optimized from sparse observations without sacrificing physical consistency.
        My current work at UC Berkeley and LBNL extends this direction toward transferable scientific models and
        autonomous workflows for geoscience.
      </p>
    </div>

    <div class="home-directions">
      <div class="home-direction">
        <h3>Scientific machine learning</h3>
        <p>Fast and physically grounded surrogates for coupled subsurface flow and geothermal multiphysics.</p>
      </div>
      <div class="home-direction">
        <h3>Inverse problems &amp; uncertainty</h3>
        <p>Generative inference of fractures, flow states, and geological structure from sparse observations.</p>
      </div>
      <div class="home-direction">
        <h3>Optimization &amp; decision-making</h3>
        <p>Surrogate-assisted design and operational optimization under geological and model uncertainty.</p>
      </div>
    </div>
  </section>

  <section class="home-section">
    <h2 class="home-heading">Appointments &amp; education</h2>

    <div class="home-group-label">Academic appointments</div>

    <div class="home-row">
      <div class="home-date">Oct. 2025 — Present</div>
      <div>
        <div class="home-row-title">Postdoctoral Researcher</div>
        <div class="home-row-inst">University of California, Berkeley &amp; Lawrence Berkeley National Laboratory</div>
        <div class="home-row-meta">Advisors: Prof. Kenichi Soga &amp; Prof. Nori Nakata · Subsurface multiphysics and scientific foundation models</div>
      </div>
    </div>

    <div class="home-row">
      <div class="home-date">Apr. — Sep. 2025</div>
      <div>
        <div class="home-row-title">Postdoctoral Researcher</div>
        <div class="home-row-inst">Cornell University</div>
        <div class="home-row-meta">Advisor: Prof. Fengqi You · Geothermal energy and controlled-environment agriculture</div>
      </div>
    </div>

    <div class="home-row">
      <div class="home-date">Mar. — Jun. 2024</div>
      <div>
        <div class="home-row-title">Visiting Research Scholar</div>
        <div class="home-row-inst">Westlake University</div>
        <div class="home-row-meta">Host: Prof. Yaochu Jin</div>
      </div>
    </div>

    <div class="home-group-label">Education</div>

    <div class="home-row">
      <div class="home-date">2021 — 2025</div>
      <div>
        <div class="home-row-title">Ph.D. in Hydrogeology</div>
        <div class="home-row-inst">The University of Hong Kong</div>
        <div class="home-row-meta">Supervisor: Prof. Jiu Jimmy Jiao · HKIE Ringo Yu Prize for Best PhD Thesis · HKU Foundation Excellent PhD Award</div>
      </div>
    </div>

    <div class="home-row">
      <div class="home-date">2018 — 2021</div>
      <div>
        <div class="home-row-title">M.Sc. in Oil &amp; Gas Development Engineering</div>
        <div class="home-row-inst">China University of Petroleum (East China)</div>
        <div class="home-row-meta">Supervisor: Prof. Kai Zhang · Outstanding Master’s Thesis of Shandong Province</div>
      </div>
    </div>

    <div class="home-row">
      <div class="home-date">2014 — 2018</div>
      <div>
        <div class="home-row-title">B.Eng. in Petroleum Engineering</div>
        <div class="home-row-inst">China University of Petroleum (East China)</div>
        <div class="home-row-meta">National Scholarship, China Ministry of Education</div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <h2 class="home-heading">Selected publications</h2>

    <div class="home-pub">
      <div>
        <p class="home-pub-title">
          <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2025GL120253">Physics-supervised autonomous inverse fracture modelling via generative artificial intelligence</a>
        </p>
        <p class="home-pub-meta">Geophysical Research Letters</p>
      </div>
      <div class="home-year">2026</div>
    </div>

    <div class="home-pub">
      <div>
        <p class="home-pub-title">
          <a href="https://www.sciencedirect.com/science/article/pii/S0306261926000899">Energy-efficient greenhouse climate control with diffusion reinforcement learning</a>
        </p>
        <p class="home-pub-meta">Applied Energy</p>
      </div>
      <div class="home-year">2026</div>
    </div>

    <div class="home-pub">
      <div>
        <p class="home-pub-title">
          <a href="https://ieeexplore.ieee.org/document/11224780">Expensive multi-objective optimization guided by attention-enhanced generative models</a>
        </p>
        <p class="home-pub-meta">IEEE Transactions on Neural Networks and Learning Systems</p>
      </div>
      <div class="home-year">2025</div>
    </div>

    <div class="home-pub">
      <div>
        <p class="home-pub-title">Multi-fidelity machine learning with knowledge transfer enhances geothermal energy system design and optimization</p>
        <p class="home-pub-meta">Advances in Geo-Energy Research</p>
      </div>
      <div class="home-year">2025</div>
    </div>

    <div class="home-pub">
      <div>
        <p class="home-pub-title">
          <a href="https://www.cell.com/nexus/fulltext/S2950-1601(24)00042-1">Machine-learning-accelerated multi-objective design of fractured geothermal systems</a>
        </p>
        <p class="home-pub-meta">Nexus · Cell Press</p>
      </div>
      <div class="home-year">2024</div>
    </div>

    <div class="home-pub">
      <div>
        <p class="home-pub-title">
          <a href="https://www.sciencedirect.com/science/article/abs/pii/S1364032123007189">Surrogate-assisted level-based learning evolutionary search for geothermal heat extraction optimization</a>
        </p>
        <p class="home-pub-meta">Renewable and Sustainable Energy Reviews</p>
      </div>
      <div class="home-year">2024</div>
    </div>

    <p class="home-more"><a href="{{ site.url }}{{ site.baseurl }}/publications/">View complete publication list →</a></p>
  </section>

  <section class="home-section">
    <h2 class="home-heading">Selected scholarly activities</h2>
    <div class="home-two-col">
      <div>
        <div class="home-group-label" style="margin-top:0;">Invited seminars</div>
        <ul class="home-compact">
          <li><strong>Stanford University</strong> · 2026</li>
          <li><strong>Lawrence Berkeley National Laboratory</strong> · 2025</li>
          <li><strong>Cornell University</strong> · 2025</li>
          <li><strong>MIT</strong> · 2024</li>
          <li><strong>Yale University</strong> · 2024</li>
          <li><strong>Stanford University</strong> · 2024</li>
        </ul>
      </div>
      <div>
        <div class="home-group-label" style="margin-top:0;">Teaching, mentoring &amp; service</div>
        <ul class="home-compact">
          <li>Teaching assistant and tutorial leader across <strong>five Earth Sciences courses at HKU</strong>.</li>
          <li>Research mentoring involving PhD and MSc researchers at <strong>Stanford/LBNL, Peking University, Arizona State University, and CUP(E)</strong>.</li>
          <li><strong>Primary Convener</strong>, AGU Annual Meeting 2026 session.</li>
          <li>Reviewer for journals spanning geoscience, energy systems, and machine learning.</li>
        </ul>
      </div>
    </div>
    <p class="home-more"><a href="{{ site.url }}{{ site.baseurl }}/activities/">More academic activities →</a></p>
  </section>

  <section class="home-section">
    <h2 class="home-heading">Recognition</h2>
    <div class="home-row">
      <div class="home-date">Doctoral</div>
      <div>
        <div class="home-row-title">HKIE Ringo Yu Prize for Best PhD Thesis</div>
        <div class="home-row-meta">Hong Kong Institution of Engineers</div>
      </div>
    </div>
    <div class="home-row">
      <div class="home-date">Doctoral</div>
      <div>
        <div class="home-row-title">HKU Foundation Excellent PhD Award</div>
        <div class="home-row-meta">The University of Hong Kong</div>
      </div>
    </div>
    <div class="home-row">
      <div class="home-date">Master's</div>
      <div>
        <div class="home-row-title">Outstanding Master’s Thesis of Shandong Province</div>
      </div>
    </div>
    <div class="home-row">
      <div class="home-date">Undergraduate</div>
      <div>
        <div class="home-row-title">National Scholarship, China Ministry of Education</div>
        <div class="home-row-meta">Top 1%</div>
      </div>
    </div>
  </section>

</div>

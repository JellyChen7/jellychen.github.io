<style>
/* =========================================================
   Research page
   Restrained academic styling; scoped to this page only
   ========================================================= */

.research-page {
  max-width: 760px;
  color: #232323;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  font-size: 15px;
  line-height: 1.72;
}

.research-page * {
  box-sizing: border-box;
}

.research-lead {
  margin: 0 0 2.6rem;
  padding: 0 0 2rem;
  border-bottom: 1px solid #e3e3e3;
}

.research-lead p {
  margin: 0 0 0.9rem;
  color: #3d3d3d;
  font-size: 1.02rem;
  line-height: 1.78;
}

.research-lead p:first-child {
  color: #222;
  font-size: 1.08rem;
}

.research-lead strong {
  color: #111;
  font-weight: 600;
}

.research-section {
  margin: 0 0 3.1rem;
}

.research-heading {
  margin: 0 0 1.25rem;
  padding-bottom: 0.55rem;
  border-bottom: 1px solid #dedede;
  color: #111;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1.22rem;
  font-weight: 400;
  letter-spacing: 0;
}

.research-directions {
  border-top: 1px solid #dedede;
}

.research-direction {
  display: grid;
  grid-template-columns: 42px minmax(0, 1fr);
  column-gap: 1.05rem;
  padding: 1.25rem 0 1.35rem;
  border-bottom: 1px solid #e8e8e8;
}

.research-number {
  padding-top: 0.12rem;
  color: #9a9a9a;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 0.88rem;
}

.research-direction h3 {
  margin: 0 0 0.35rem;
  color: #111;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1.01rem;
  font-weight: 600;
  line-height: 1.4;
}

.research-direction p {
  margin: 0;
  color: #555;
  font-size: 0.92rem;
  line-height: 1.7;
}

.research-keywords {
  margin-top: 0.45rem !important;
  color: #888 !important;
  font-size: 0.78rem !important;
  letter-spacing: 0.01em;
}

.research-projects {
  border-top: 1px solid #dedede;
}

.research-project {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;
  column-gap: 1.2rem;
  padding: 1.2rem 0 1.25rem;
  border-bottom: 1px solid #e8e8e8;
}

.research-project h3 {
  margin: 0 0 0.3rem;
  color: #151515;
  font-size: 0.94rem;
  font-weight: 600;
  line-height: 1.48;
}

.research-project h3 a {
  color: inherit;
  text-decoration: none;
  border-bottom: 1px solid transparent;
}

.research-project h3 a:hover {
  border-bottom-color: #777;
}

.research-project p {
  margin: 0;
  color: #5a5a5a;
  font-size: 0.86rem;
  line-height: 1.68;
}

.research-meta {
  margin-top: 0.38rem !important;
  color: #8a8a8a !important;
  font-size: 0.76rem !important;
}

.research-year {
  padding-top: 0.08rem;
  color: #a0a0a0;
  font-size: 0.77rem;
  white-space: nowrap;
}

.research-current {
  margin-top: 1.1rem;
  padding-left: 1rem;
  border-left: 2px solid #c9d5e7;
}

.research-current h3 {
  margin: 0 0 0.35rem;
  color: #1a1a1a;
  font-size: 0.95rem;
  font-weight: 600;
}

.research-current p {
  margin: 0;
  color: #555;
  font-size: 0.88rem;
  line-height: 1.7;
}

.research-funding {
  margin: 0;
  padding: 0;
  list-style: none;
  border-top: 1px solid #dedede;
}

.research-funding li {
  padding: 0.85rem 0;
  border-bottom: 1px solid #ececec;
  color: #555;
  font-size: 0.86rem;
  line-height: 1.6;
}

.research-funding strong {
  color: #222;
  font-weight: 600;
}

.research-note {
  margin-top: 1.1rem;
  color: #888;
  font-size: 0.78rem;
  line-height: 1.6;
}

.research-page a {
  color: #2b5d9b;
}

@media (max-width: 640px) {
  .research-page {
    font-size: 14px;
  }

  .research-direction {
    grid-template-columns: 30px minmax(0, 1fr);
    column-gap: 0.75rem;
  }

  .research-project {
    grid-template-columns: 1fr;
  }

  .research-year {
    margin-top: 0.35rem;
  }
}
</style>

<div class="research-page">

  <section class="research-lead">
    <p>
      My research develops <strong>computational methods for subsurface energy and environmental systems</strong>,
      with an emphasis on scientific machine learning, inverse modelling, uncertainty quantification,
      and optimization.
    </p>
    <p>
      Many subsurface problems are defined by the same practical constraints: observations are sparse,
      geological structure is uncertain, high-fidelity multiphysics simulation is expensive, and
      engineering decisions must be made under incomplete information. I use machine learning where it
      can reduce this computational burden or extract information that is difficult to obtain directly,
      while retaining the governing physics as an explicit part of the modelling framework.
    </p>
    <p>
      Current work focuses on geothermal reservoirs, geological CO<sub>2</sub> storage, fractured-media
      flow, and transferable scientific models for subsurface systems.
    </p>
  </section>

  <section class="research-section">
    <h2 class="research-heading">Research directions</h2>

<div class="research-directions">

  <div class="research-direction">
    <div class="research-number">01</div>
    <div>
      <h3>Scientific machine learning for subsurface multiphysics</h3>
      <p>
        Learning reduced and surrogate representations of pressure, temperature, saturation,
        and coupled reservoir dynamics across heterogeneous porous and fractured media. The
        objective is to make repeated simulation, uncertainty analysis, and history matching
        feasible at field scale without treating physical simulation as a black box.
      </p>
      <p class="research-keywords">
        geothermal · CO₂ storage · multiphysics simulation · surrogate modelling
      </p>
    </div>
  </div>

  <div class="research-direction">
    <div class="research-number">02</div>
    <div>
      <h3>Generative inverse modelling and uncertainty quantification</h3>
      <p>
        Developing generative approaches for reconstructing geological structure and subsurface
        states from sparse, indirect observations. A particular focus is fracture-network inversion,
        where non-uniqueness and limited observability require probabilistic rather than purely
        deterministic solutions.
      </p>
      <p class="research-keywords">
        diffusion models · inverse problems · fracture characterization · data assimilation
      </p>
    </div>
  </div>

  <div class="research-direction">
    <div class="research-number">03</div>
    <div>
      <h3>Optimization and decision-making under geological uncertainty</h3>
      <p>
        Combining surrogate models, evolutionary optimization, and active learning to reduce the
        number of expensive simulations required for reservoir design and operation. Applications
        include well placement, injection and production control, heat-extraction design, and
        multi-objective trade-offs among energy recovery, risk, and environmental performance.
      </p>
      <p class="research-keywords">
        multi-objective optimization · active learning · reservoir design · decision support
      </p>
    </div>
  </div>

  <div class="research-direction">
    <div class="research-number">04</div>
    <div>
      <h3>Transferable models and autonomous workflows for geoscience</h3>
      <p>
        My current research is moving from task-specific models toward reusable representations
        and scientific workflows that can transfer across reservoirs, physical conditions, and
        modelling tasks. This includes foundation-model concepts for subsurface systems and
        agentic workflows that connect observation, simulation, inference, and decision-making.
      </p>
      <p class="research-keywords">
        scientific foundation models · transfer learning · agentic workflows · scientific discovery
      </p>
    </div>
  </div>

</div>

  </section>

  <section class="research-section">
    <h2 class="research-heading">Current research</h2>

<div class="research-current">
  <h3>Subsurface multiphysics modelling and scientific foundation models</h3>
  <p>
    At UC Berkeley and Lawrence Berkeley National Laboratory, I work on machine-learning methods
    for geothermal-reservoir modelling and transferable subsurface representations, including
    research connected to The Geysers, Cape Station, and Utah FORGE.
  </p>
</div>

  </section>

  <section class="research-section">
    <h2 class="research-heading">Selected research</h2>

<div class="research-projects">

  <div class="research-project">
    <div>
      <h3>
        <a href="https://github.com/JellyChen7/GenFrac">
          Physics-supervised generative inversion of fracture networks
        </a>
      </h3>
      <p>
        A generative inverse-modelling framework for recovering fracture-network structure from
        indirect hydraulic observations while enforcing physical consistency in the inferred solutions.
      </p>
      <p class="research-meta">
        Geophysical Research Letters · code available
      </p>
    </div>
    <div class="research-year">2026</div>
  </div>

  <div class="research-project">
    <div>
      <h3>
        <a href="https://github.com/JellyChen7/FracCGM">
          Diffusion modelling of spatiotemporal flow in fractured media
        </a>
      </h3>
      <p>
        Conditional generative modelling of transient pressure and temperature fields in stochastic
        fracture networks, with probabilistic ensembles for uncertainty characterization and
        subsequent inverse analysis.
      </p>
      <p class="research-meta">
        JGR: Machine Learning and Computation · under review · code available
      </p>
    </div>
    <div class="research-year">2026</div>
  </div>

  <div class="research-project">
    <div>
      <h3>
        <a href="https://www.cell.com/nexus/fulltext/S2950-1601(24)00042-1">
          Machine-learning-accelerated design of fractured geothermal systems
        </a>
      </h3>
      <p>
        Surrogate-assisted multi-objective optimization for fractured geothermal reservoirs,
        designed to identify high-value operating strategies with substantially fewer high-fidelity
        simulations.
      </p>
      <p class="research-meta">
        Nexus · Cell Press
      </p>
    </div>
    <div class="research-year">2024</div>
  </div>

  <div class="research-project">
    <div>
      <h3>
        Multi-fidelity learning for geothermal system design
      </h3>
      <p>
        Knowledge-transfer methods that combine simulations of different fidelities to improve
        predictive accuracy and reduce the computational cost of geothermal-reservoir optimization.
      </p>
      <p class="research-meta">
        Advances in Geo-Energy Research
      </p>
    </div>
    <div class="research-year">2025</div>
  </div>

  <div class="research-project">
    <div>
      <h3>
        Data-driven production optimization in subsurface reservoirs
      </h3>
      <p>
        A series of surrogate-assisted evolutionary methods for high-dimensional well-placement
        and control problems, forming the methodological basis for my later work on geothermal
        design and scientific machine learning.
      </p>
      <p class="research-meta">
        SPE Journal · Fuel · Information Sciences · Applied Soft Computing
      </p>
    </div>
    <div class="research-year">2020–2022</div>
  </div>

</div>

  </section>

  <section class="research-section">
    <h2 class="research-heading">Collaborative projects</h2>

<ul class="research-funding">
  <li>
    <strong>Subsurface Multi-Physics Modelling &amp; Scientific Foundation Model</strong><br>
    UC Berkeley &amp; Lawrence Berkeley National Laboratory
  </li>
  <li>
    <strong>ADVANCEA — Advancing Controlled Environment Agriculture Through Data-Driven Decision-Making and Workforce Development</strong><br>
    U.S. Department of Agriculture · US$3.77M
  </li>
  <li>
    <strong>Poshan Drainage Tunnel System as a Hillslope Critical Zone Observatory</strong><br>
    Research Grants Council of Hong Kong · Collaborative Research Fund · HK$2.79M
  </li>
  <li>
    <strong>Digital Twin-Empowered Landslide Emergency Risk Management</strong><br>
    Research Grants Council of Hong Kong · Theme-based Research Scheme · HK$2.506M
  </li>
</ul>

<p class="research-note">
  See the <a href="/publications/">Publications</a> page for the full publication record and
  the <a href="/files/cv.pdf">CV</a> for additional project and collaboration details.
</p>

  </section>

</div>

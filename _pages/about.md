---
layout: default
title: Home
permalink: /
portfolio_home: true
---

<div class="portfolio-home">
  <section class="portfolio-hero" aria-labelledby="portfolio-name">
    <div class="portfolio-wrap portfolio-hero-grid">
      <div class="portfolio-hero-copy">
        <p class="portfolio-eyebrow">Aerospace engineering <span aria-hidden="true">/</span> Lunar ISRU</p>
        <h1 id="portfolio-name">Lucas-Brian <span>Christen</span></h1>
        <p class="portfolio-role">PhD Researcher · The University of Tokyo</p>
        <div class="portfolio-hero-rule" aria-hidden="true"></div>
        <p class="portfolio-lead">
          I investigate laser-driven vaporization of lunar regolith, with a focus on
          selective material removal, compositional changes, and process energy requirements.
        </p>
        <p class="portfolio-affiliation">
          Department of Aeronautics and Astronautics<br>
          Komurasaki &amp; Koizumi Laboratory · Tokyo, Japan
        </p>
        <div class="portfolio-actions">
          <a class="portfolio-button portfolio-button-primary" href="{{ '/research/' | relative_url }}">
            Explore research <span aria-hidden="true">↗</span>
          </a>
          <a class="portfolio-button portfolio-button-outline" href="{{ '/engineering/' | relative_url }}">
            Engineering portfolio
          </a>
        </div>
        <div class="portfolio-social" aria-label="Professional profiles">
          <a href="mailto:l.christen@al.t.u-tokyo.ac.jp">Email</a>
          <a href="https://researchmap.jp/lucasbrianchristen" target="_blank" rel="noopener noreferrer">researchmap</a>
          <a href="https://www.linkedin.com/in/lucas-brian-christen" target="_blank" rel="noopener noreferrer">LinkedIn</a>
          <a href="https://orcid.org/0009-0008-0968-349X" target="_blank" rel="noopener noreferrer">ORCID</a>
          <a href="https://github.com/lucaschristen" target="_blank" rel="noopener noreferrer">GitHub</a>
        </div>
      </div>
      <div class="portfolio-portrait-wrap">
        <img
          class="portfolio-portrait"
          src="{{ '/assets/img/portfolio/profile.jpg' | relative_url }}"
          alt="Portrait of Lucas-Brian Christen"
          width="720"
          height="900"
          fetchpriority="high"
        >
      </div>
    </div>
  </section>

  <section class="portfolio-section portfolio-research" id="research-highlights" aria-labelledby="portfolio-research-title">
    <div class="portfolio-wrap">
      <div class="portfolio-section-head">
        <div>
          <p class="portfolio-eyebrow">Selected work</p>
          <h2 id="portfolio-research-title">Research &amp; engineering</h2>
        </div>
        <p>
          Selected experiments, diagnostic methods, and numerical analyses related to
          thermal processing of lunar materials.
        </p>
      </div>
      <div class="portfolio-card-grid">
        <a class="portfolio-photo-card" href="{{ '/research/' | relative_url }}">
          <img src="{{ '/assets/img/portfolio/research-laser.jpg' | relative_url }}" alt="" loading="lazy">
          <div class="portfolio-card-content">
            <span class="portfolio-card-kicker">01 / Research</span>
            <h3>Laser-driven vaporization of lunar regolith</h3>
            <p>Studying mass loss, selective volatilization, and melt behavior under continuous-wave laser heating.</p>
            <span class="portfolio-card-detail">CW fiber lasers · Vacuum processing · Thermal fractionation</span>
          </div>
        </a>

        <a class="portfolio-photo-card" href="{{ '/engineering/' | relative_url }}">
          <img src="https://raw.githubusercontent.com/lucaschristen/Personal_Website/main/assets/images/research-thermometry.jpg" alt="" loading="lazy">
          <div class="portfolio-card-content">
            <span class="portfolio-card-kicker">02 / Instrumentation</span>
            <h3>High-temperature optical diagnostics</h3>
            <p>Ratio pyrometry, emission spectroscopy, and calibrated measurements for laser-heated materials.</p>
            <span class="portfolio-card-detail">Spectroscopy · Optics · Python</span>
          </div>
        </a>

        <a class="portfolio-photo-card" href="{{ '/research/' | relative_url }}">
          <img src="{{ '/assets/img/portfolio/al2o3.png' | relative_url }}" alt="" loading="lazy">
          <div class="portfolio-card-content">
            <span class="portfolio-card-kicker">03 / Lunar ISRU</span>
            <h3>Oxide enrichment for metal extraction</h3>
            <p>Investigating thermal beneficiation as a potential precursor to aluminium extraction from lunar resources.</p>
            <span class="portfolio-card-detail">Selective vaporization · Oxide chemistry · ISRU</span>
          </div>
        </a>

        <a class="portfolio-photo-card" href="{{ '/research/' | relative_url }}">
          <img src="https://raw.githubusercontent.com/lucaschristen/Personal_Website/main/assets/images/simulants.JPG" alt="" loading="lazy">
          <div class="portfolio-card-content">
            <span class="portfolio-card-kicker">04 / Materials</span>
            <h3>Lunar regolith simulants</h3>
            <p>Characterizing and processing lunar analogue materials to understand their behavior under extreme heating.</p>
            <span class="portfolio-card-detail">LHS-1 · Material characterization · Experimentation</span>
          </div>
        </a>
      </div>
      <p class="portfolio-section-note">
        Further technical details are available in the
        <a href="{{ '/engineering/' | relative_url }}">engineering portfolio <span aria-hidden="true">↗</span></a>.
      </p>
    </div>

  </section>

  <section class="portfolio-section portfolio-bottom" id="contact" aria-labelledby="portfolio-contact-title">
    <div class="portfolio-wrap portfolio-bottom-grid">
      <div class="portfolio-bottom-intro">
        <p class="portfolio-eyebrow">Contact &amp; collaboration</p>
        <h2 id="portfolio-contact-title">Get in touch</h2>
        <p class="portfolio-contact-description">
          I welcome discussions about lunar ISRU, experimental research,
          and possible scientific collaborations. Please feel free to contact me.
        </p>
        <div class="portfolio-contact-links">
          <a href="mailto:l.christen@al.t.u-tokyo.ac.jp">Email me <span aria-hidden="true">↗</span></a>
          <a href="https://www.linkedin.com/in/lucas-brian-christen" target="_blank" rel="noopener noreferrer">Connect on LinkedIn <span aria-hidden="true">↗</span></a>
        </div>
      </div>
      <div class="portfolio-publication">
        <p class="portfolio-eyebrow">Selected publication · 2025</p>
        <h3>Laser processing of lunar regolith simulants for beneficiation and metal extraction</h3>
        <p><em>Vacuum</em></p>
        <a href="{{ '/publications/' | relative_url }}">View publications <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </section>
</div>

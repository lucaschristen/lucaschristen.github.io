---
layout: default
title: Engineering
permalink: /engineering/
description: Hardware, optics, control software and simulation tools for aerospace research.
nav: true
nav_order: 2
portfolio_page: true
---

<div class="portfolio-detail portfolio-detail-engineering">
  <header class="portfolio-detail-hero">
    <div class="portfolio-wrap">
      <p class="portfolio-eyebrow">Engineering / Experimental systems &amp; software</p>
      <h1>Engineering portfolio</h1>
      <p class="portfolio-detail-lead">
        Building the hardware and software required to perform repeatable high-temperature experiments:
        from laser and vacuum integration to real-time measurement and modelling.
      </p>
      <div class="portfolio-detail-chips" aria-label="Engineering disciplines">
        <span>Laser systems</span>
        <span>Vacuum hardware</span>
        <span>Optics</span>
        <span>Python</span>
        <span>Measurement &amp; control</span>
      </div>
    </div>
  </header>

  <nav class="portfolio-jumpbar" aria-label="Jump to engineering projects">
    <div class="portfolio-wrap">
      {% for item in site.data.engineering_portfolio.sections %}
        <a href="#{{ item.id }}"><span>{{ item.number }}</span> {{ item.title }}</a>
      {% endfor %}
    </div>
  </nav>

  <div class="portfolio-wrap portfolio-showcase-list">
    {% for item in site.data.engineering_portfolio.sections %}
      {% include portfolio/showcase.liquid item=item %}
    {% endfor %}
  </div>

  <section class="portfolio-detail-outro">
    <div class="portfolio-wrap portfolio-detail-outro-grid">
      <div>
        <p class="portfolio-eyebrow">Beyond the apparatus</p>
        <h2>Design, build, measure, improve.</h2>
        <p>The portfolio is organized around engineering problems and methods. Each project section is ready for original photos, layouts, diagrams and validation plots.</p>
      </div>
      <div class="portfolio-outro-links">
        <a href="https://github.com/lucaschristen" target="_blank" rel="noopener noreferrer">GitHub repositories <span aria-hidden="true">↗</span></a>
        <a href="{{ '/research/' | relative_url }}">Research applications <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </section>
</div>

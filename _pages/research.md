---
layout: default
title: Research
permalink: /research/
description: Lunar regolith vaporization, selective enrichment and modelling.
nav: true
nav_order: 1
portfolio_page: true
---

<div class="portfolio-detail portfolio-detail-research">
  <header class="portfolio-detail-hero">
    <div class="portfolio-wrap">
      <p class="portfolio-eyebrow">Research / Lunar in-situ resource utilization</p>
      <h1>Research</h1>
      <p class="portfolio-detail-lead">
        Can laser heating help separate lunar materials before metal extraction?
        My research combines controlled vaporization experiments, optical diagnostics, and modelling.
      </p>
      <div class="portfolio-detail-chips" aria-label="Research themes">
        <span>Lunar regolith</span>
        <span>Selective vaporization</span>
        <span>ISRU</span>
        <span>High-temperature processing</span>
      </div>
    </div>
  </header>

  <nav class="portfolio-jumpbar" aria-label="Jump to research topics">
    <div class="portfolio-wrap">
      {% for item in site.data.research_portfolio.sections %}
        <a href="#{{ item.id }}"><span>{{ item.number }}</span> {{ item.title }}</a>
      {% endfor %}
    </div>
  </nav>

  <div class="portfolio-wrap portfolio-showcase-list">
    {% for item in site.data.research_portfolio.sections %}
      {% include portfolio/showcase.liquid item=item %}
    {% endfor %}
  </div>

  <section class="portfolio-detail-outro">
    <div class="portfolio-wrap portfolio-detail-outro-grid">
      <div>
        <p class="portfolio-eyebrow">Research outcome</p>
        <h2>Connecting science to future lunar resource use</h2>
        <p>These experiments support evaluation of thermal beneficiation as a possible step in a broader lunar metal-production process.</p>
      </div>
      <div class="portfolio-outro-links">
        <a href="{{ '/publications/' | relative_url }}">Papers &amp; conferences <span aria-hidden="true">↗</span></a>
        <a href="{{ '/engineering/' | relative_url }}">Experimental engineering <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </section>
</div>

---
layout: default
title: Publications
permalink: /publications/
description: Peer-reviewed papers, talks and poster presentations.
nav: true
nav_order: 3
portfolio_page: true
---

<div class="portfolio-detail portfolio-detail-publications">
  <header class="portfolio-detail-hero">
    <div class="portfolio-wrap">
      <p class="portfolio-eyebrow">Academic record</p>
      <h1>Publications &amp; conferences</h1>
      <p class="portfolio-detail-lead">
        Peer-reviewed articles and research presentations on laser processing, lunar ISRU,
        and high-temperature materials.
      </p>
      <div class="portfolio-detail-chips">
        <span>3 papers</span>
        <span>8 presentations &amp; posters</span>
        <a href="https://researchmap.jp/lucasbrianchristen" target="_blank" rel="noopener noreferrer">researchmap ↗</a>
      </div>
    </div>
  </header>

  <nav class="portfolio-jumpbar" aria-label="Jump to academic output">
    <div class="portfolio-wrap">
      <a href="#papers">Peer-reviewed papers</a>
      <a href="#presentations">Conferences &amp; posters</a>
      <a href="https://researchmap.jp/lucasbrianchristen" target="_blank" rel="noopener noreferrer">Full researchmap profile ↗</a>
    </div>
  </nav>

  <section class="portfolio-record-section" id="papers">
    <div class="portfolio-wrap">
      <div class="portfolio-record-head">
        <p class="portfolio-eyebrow">Journal articles</p>
        <h2>Peer-reviewed papers</h2>
      </div>
      <div class="portfolio-paper-grid">
        {% for paper in site.data.academic_works.papers %}
          <article class="portfolio-paper-card">
            <div class="portfolio-paper-meta">
              <span>{{ paper.year }}</span>
              <span>{{ paper.topic }}</span>
            </div>
            <h3>{{ paper.title }}</h3>
            <p class="portfolio-paper-journal">{{ paper.journal }} · {{ paper.details }}</p>
            <details class="portfolio-paper-authors">
              <summary>Authors</summary>
              <p>{{ paper.authors }}</p>
            </details>
            <a href="https://doi.org/{{ paper.doi }}" target="_blank" rel="noopener noreferrer">
              View article / DOI <span aria-hidden="true">↗</span>
            </a>
          </article>
        {% endfor %}
      </div>
    </div>
  </section>

  <section class="portfolio-record-section portfolio-record-section-alt" id="presentations">
    <div class="portfolio-wrap">
      <div class="portfolio-record-head">
        <p class="portfolio-eyebrow">Talks &amp; poster presentations</p>
        <h2>Conferences</h2>
        <p>Presented research, listed newest first. Publication type and event information are kept separate from journal papers.</p>
      </div>
      {% assign yearly_talks = site.data.academic_works.presentations | group_by: "year" %}
      {% for year_group in yearly_talks %}
        <div class="portfolio-talk-year">
          <h3>{{ year_group.name }}</h3>
          <div class="portfolio-talk-list">
            {% for talk in year_group.items %}
              <article class="portfolio-talk">
                <div class="portfolio-talk-date">
                  <strong>{{ talk.year }}</strong>
                  {% if talk.month != blank %}
                    <span>{{ talk.month }}</span>
                  {% endif %}
                </div>
                <div class="portfolio-talk-content">
                  <h4>{{ talk.title }}</h4>
                  <p>{{ talk.event }}{% if talk.location != blank %} · {{ talk.location }}{% endif %}</p>
                </div>
                <span class="portfolio-talk-category">{{ talk.category }}</span>
              </article>
            {% endfor %}
          </div>
        </div>
      {% endfor %}
      <p class="portfolio-record-note">
        This manually maintained list is cross-checked against public researchmap-derived records
        and earlier conference details. For entries added most recently, consult
        <a href="https://researchmap.jp/lucasbrianchristen" target="_blank" rel="noopener noreferrer">researchmap</a>.
      </p>
    </div>
  </section>
</div>

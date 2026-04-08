---
layout: page-fullwidth
title: "Publications"
subheadline: "Research outputs from the AI4ED project"
teaser: "Peer-reviewed papers, conference presentations, and preprints documenting our work on emergency department chart summarization, simulation, and workflow optimization."
permalink: "/publications/"
header:
  image_fullwidth: "visuals/header_ai4ed_signal.svg"
---

<div class="ai4ed-section-intro">
  <p>AI4ED publications document the project across language-model evaluation, chart summarization, and agentic emergency department simulation. Together, they show how clinically grounded AI research can move from benchmarking and prototype development toward operational decision support.</p>
</div>

<div class="publication-list">
  {% for paper in site.data.publications %}
    <article class="publication-card publication-card--featured">
      <p class="publication-card__eyebrow">AI4ED research output</p>
      <h2 class="publication-card__title"><a href="{{ paper.url }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a></h2>
      <div class="publication-badges">
        <span class="publication-badge">{{ paper.venue }}</span>
        <span class="publication-badge publication-badge--status">{{ paper.status }}</span>
      </div>
      <p class="publication-card__authors"><strong>Authors:</strong> {{ paper.authors }}</p>
      <p class="publication-card__summary">{{ paper.summary }}</p>
      <p class="publication-card__actions"><a class="button tiny radius" href="{{ paper.url }}" target="_blank" rel="noopener noreferrer">Open publication</a></p>
    </article>
  {% endfor %}
</div>

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
  <p>AI4ED publications document the project across language-model evaluation, chart summarization, and agentic emergency department simulation. Together, they show how the work is moving from early prototypes and benchmarking toward clinically grounded decision-support research.</p>
</div>

<div class="research-publication-list">
  {% for paper in site.data.publications %}
    <article class="research-publication-card">
      <header class="research-publication-card__header">
        <div class="research-publication-card__heading">
          <h2><a href="{{ paper.url }}" target="_blank" rel="noopener noreferrer">{{ paper.title }}</a></h2>
          <div class="research-publication-card__meta" aria-label="Publication details">
            <span>{{ paper.venue }}</span>
            <span>{{ paper.status }}</span>
          </div>
        </div>
        <a class="research-publication-card__link" href="{{ paper.url }}" target="_blank" rel="noopener noreferrer">Open publication</a>
      </header>
      <p class="research-publication-card__authors"><strong>Authors:</strong> {{ paper.authors }}</p>
      <p class="research-publication-card__summary">{{ paper.summary }}</p>
    </article>
  {% endfor %}
</div>

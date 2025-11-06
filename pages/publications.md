---
layout: page
title: "Publications"
subheadline: "Research on LLMs for emergency medicine"
teaser: "Peer-reviewed and in-progress papers driving our emergency department simulation work."
permalink: "/publications/"
header:
  image_fullwidth: "header_roadmap_2.jpg"
---

Below is a growing list of our publications exploring how large language models can support emergency department teams.

{% for paper in site.data.publications %}
- **[{{ paper.title }}]({{ paper.url }})**  
  *{{ paper.venue }} – {{ paper.status }}*  
  *Authors:* {{ paper.authors }}  
  {{ paper.summary }}

{% endfor %}


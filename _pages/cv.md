---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Computer Science and Engineering**, University of Texas at Arlington (Expected 2028) — GPA: 4.0/4.0
* **Computer Science**, Rutgers University (2021–2023) — GPA: 4.0/4.0
* **M.S. in Electrical Engineering**, University of Southern California (2019–2021) — GPA: 3.94/4.0
* **B.E. in Communication Engineering**, University of Science and Technology Beijing (2015–2019) — GPA: 3.66/4.0
  * Dissertation: "Complex Aviation Mobile Services Link Aggregation with Hidden Markov Model" — University Excellent Student Paper Award (top 3%)

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Research Interests

* **Trustworthy and Interpretable AI**: Explainability and uncertainty quantification in AI systems
* **Correlation Learning**: Learning and exploiting label and feature correlations in modern machine learning
* **AI4Science**: Applications of deep learning in healthcare (time-series, pathology data) and biology (genetic data)

## Services

**Reviewer**: ICLR, CVPR, NeurIPS, AAAI, WACV, ACML

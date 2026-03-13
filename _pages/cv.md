---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

I am a fourth-year Ph.D. candidate in the School of Statistics and Data Science at Nankai University, working on statistical matching, online decision-making, and data-efficient machine learning.

Education
======
* Ph.D. Candidate in Statistics, Nankai University, 2022.09–2027.06 (expected), Supervisor: Prof. Jianfeng Yang  
* Visiting Scholar, University of California, Irvine, 2025.03–2026.03, Supervisor: Prof. Annie Qu.<br> I also work with Prof. Xiaowu Dai from the University of California, Los Angeles.  
* B.S. in Mathematics, Nankai University, 2018.09–2022.06

Research Interests
======
* Online Decision-Making and Economics: matching markets, incentives and social welfare, contract theory, applications to LLM routing.
* Data-Efficient Machine Learning: active learning, experimental design.

Preprints
======
{% for post in site.publications reversed %}
{% if post.category == "preprints" %}
{% include archive-single-cv.html %}
{% endif %}
{% endfor %}

Journal Articles
======
{% for post in site.publications reversed %}
{% if post.category == "manuscripts" %}
{% include archive-single-cv.html %}
{% endif %}
{% endfor %}

Academic Service
======
I serve as an anonymous reviewer for *Journal of the American Statistical Association*, *Electronic Journal of Statistics*, and *Statistical Learning and Data Science*.

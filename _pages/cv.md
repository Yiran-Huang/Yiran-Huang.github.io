---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. Candidate in Statistics, Nankai University, 2022.09–2027.06 (expected), Supervisor: Prof. Jianfeng Yang  
* Visiting Scholar, University of California, Irvine, 2025.03–2026.03, Supervisor: Prof. Annie Qu.<br> I also work with Prof. Xiaowu Dai from the University of California, Los Angeles.  
* B.S. in Mathematics, Nankai University, 2018.09–2022.06

Preprints
======
{% for post in site.publications reversed %}
{% if post.category == "preprints" %}
{% include archive-single-cv.html %}
{% endif %}
{% endfor %}

Journal
======
{% for post in site.publications reversed %}
{% if post.category == "manuscripts" %}
{% include archive-single-cv.html %}
{% endif %}
{% endfor %}

Academic Service
======
I am an anonymous reviewer for *Journal of the American Statistical Association* and *Electronic Journal of Statistics*.

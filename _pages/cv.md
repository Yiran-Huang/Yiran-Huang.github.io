---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

I am a fourth-year Ph.D. candidate in the School of Statistics and Data Science at Nankai University. My research focuses on statistical matching and online decision-making. I am also interested in applying these methods to practical applications such as recommendation systems and large language models. Another research focus is active learning.

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

Journal Articles
======
{% for post in site.publications reversed %}
{% if post.category == "manuscripts" %}
{% include archive-single-cv.html %}
{% endif %}
{% endfor %}

Academic Service
======
I am an anonymous reviewer for *Journal of the American Statistical Association* and *Electronic Journal of Statistics*.

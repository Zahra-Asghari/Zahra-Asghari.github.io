---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Publication

Explainability of Vision Transformers: A Comprehensive Review and New Perspectives [[Preprint](https://arxiv.org/abs/2311.06786)]

**Rojina Kashefi<sup>*</sup>**, Leili Barekatain<sup>*</sup>, Mohammad Sabokrou, Fatemeh Aghaeipoor (To be Submitted in TMLR - Dec 2023)
{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=dH-0GtkAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

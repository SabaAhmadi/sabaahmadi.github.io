---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Conference Publications

**An Algorithm for Multi-Attribute Diverse Matching** with Faez Ahmed, John P. Dickerson, Mark Fuge, and Samir Khuller. IJCAI 2020

**Min-Max Correlation Clustering via Multicut** with Samir Khuller, and Barna Saha. IPCO 2019, ([conference version](https://link.springer.com/chapter/10.1007/978-3-030-17953-3_2))

**On Scheduling Coflows** with Samir Khuller, Manish Purohit, Sheng Yang. IPCO 2017, ([long version](https://sabaahmadi.github.io/files/coflow.pdf))

## Working Papers

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Conference Publications
**An Algorithm for Multi-Attribute Diverse Matching** with Faez Ahmed, John P. Dickerson, Mark Fuge, Samir Khuller, IJCAI 2020[arxiv version](https://arxiv.org/abs/1909.03350)

##Working Papers

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

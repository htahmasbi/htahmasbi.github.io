---
title: "Research"
permalink: /research/
layout: archive
author_profile: true
redirect_from:
  - /portfolio/
---

{% include base_path %}


{% assign researches = site.research | sort: "sort_order" %}

{% for post in researches %}
  {% include archive-single.html %}
{% endfor %}

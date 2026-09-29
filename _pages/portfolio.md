---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

{% assign portfolio_sorted = site.portfolio | sort: "importance" %}

{% for post in portfolio_sorted %}
  {% include archive-single.html %}
{% endfor %}
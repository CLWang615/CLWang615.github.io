---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[1] Proportional optimization forecasting analysis of photovoltaic and coal-fired power in 2050, China: the economic and environmental perspectives. Energy Sources, Part A: Recovery, Utilization, and Environmental Effects (SCI-IF:2.9)

[2] Revealing the impact of built environment, air pollution and housing price on health inequality: an empirical analysis of Nanjing, China. Frontiers in Public Health (SCI-IF:5.2)

[3] Air pollution and human health: Investigating the moderating effect of the built environment. Remote Sensing (SCI-IF:5.0)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

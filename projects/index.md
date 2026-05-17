---
title: titles.projects
nav:
  order: 2
  tooltip: tooltips.projects
---


{% if site.lang == 'en' %}
# {% include icon.html icon="fa-solid fa-wrench" %} Research Fields
{% else %}
# {% include icon.html icon="fa-solid fa-wrench" %} 研究分野
{% endif %}

{% include section.html %}

## {% if site.lang == 'en' %}Fields{% else %}分野一覧{% endif %}

{% include research-field-list.html %}


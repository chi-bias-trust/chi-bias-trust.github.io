---
title: Participants
nav: true
---

# Workshop Participants

{% assign papers = site.data.papers %}
{% for paper in papers %}
{% if paper.show_name == "TRUE" %}
- {{ paper.authors }}
{% endif %}
{% endfor %}

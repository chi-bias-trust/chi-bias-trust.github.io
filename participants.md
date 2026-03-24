---
title: Participants
nav: true
---

# Workshop Participants

{% assign papers = site.data.papers %}
{% for paper in papers %}
{% if paper.show_name == "Yes" %}
- {{ paper.authors }}
{% endif %}
{% endfor %}

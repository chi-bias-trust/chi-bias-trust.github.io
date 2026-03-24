---
title: Participants & Submissions
nav: true
---

# Participants & Submissions

{% assign papers = site.data.papers %}
{% for paper in papers %}
{% if paper.show_name == "TRUE" %}

### {{ paper.authors }}
{{ paper.title }}
{% if paper.show_pdf == "TRUE" %}
[📄 View PDF]({{ paper.pdf_links }}){:target="_blank"}
{% endif %}

---
{% endif %}
{% endfor %}

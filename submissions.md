---
title: Submissions
nav: true
---

# Accepted Submissions

{% assign papers = site.data.papers %}
{% for paper in papers %}
{% if paper.show_pdf == "TRUE" %}

### {{ paper.title }}
**{{ paper.authors }}**
[View PDF]({{ paper.pdf_links }}){:target="_blank"}

---
{% endif %}
{% endfor %}

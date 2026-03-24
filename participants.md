---
title: Participants & Submissions
nav: true
---

<style>
.participants-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}

.participant-card {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 1.25rem 1.5rem;
  transition: box-shadow 0.2s ease;
}

.participant-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.participant-name {
  font-size: 1rem;
  font-weight: 600;
  color: #111827;
  margin: 0 0 0.25rem 0;
}

.paper-title {
  font-size: 0.875rem;
  color: #6b7280;
  margin: 0 0 0.75rem 0;
  line-height: 1.5;
}

.pdf-link {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-size: 0.8rem;
  font-weight: 500;
  color: #2563eb;
  text-decoration: none;
  background: #eff6ff;
  padding: 4px 10px;
  border-radius: 6px;
  border: 1px solid #bfdbfe;
}

.pdf-link:hover {
  background: #dbeafe;
  text-decoration: none;
}
</style>

# Participants & Submissions

<div class="participants-grid">
{% assign papers = site.data.papers %}
{% for paper in papers %}
{% if paper.show_name == "TRUE" %}
<div class="participant-card">
  <p class="participant-name">{{ paper.authors }}</p>
  <p class="paper-title">{{ paper.title }}</p>
  {% if paper.show_pdf == "TRUE" %}
  <a class="pdf-link" href="{{ paper.pdf_links }}" target="_blank">
    📄 View PDF
  </a>
  {% endif %}
</div>
{% endif %}
{% endfor %}
</div>

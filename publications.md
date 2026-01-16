---
layout: default
title: Publications
---

# Publications

Here is a list of my selected publications.

<div class="publications-list">
{% for pub in site.data.publications %}
  <div class="publication-item" style="margin-bottom: 20px; border-bottom: 1px solid #eee; padding-bottom: 20px;">
    <h3><a href="{{ pub.link }}">{{ pub.title }}</a></h3>
    <div style="display: flex; gap: 20px; align-items: start;">
      {% if pub.thumbnail %}
      <img src="{{ pub.thumbnail }}" alt="{{ pub.title }}" style="width: 150px; height: auto; border: 1px solid #ddd;">
      {% endif %}
      <p>{{ pub.description }}</p>
    </div>
  </div>
{% endfor %}
</div>

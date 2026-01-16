---
layout: default
title: Paper Review
---

# Paper Reviews

Summaries and critiques of recent papers in my field.

## Categories

<ul>
  {% assign review_posts = site.categories['Paper Review'] %}
  {% for post in review_posts %}
    <li>
        <span style="color: #666; font-size: 0.9em;">{{ post.date | date: "%Y-%m-%d" }}</span> - 
        <a href="{{ post.url }}">{{ post.title }}</a>
        <br>
        <small>Tags: {{ post.categories | join: ', ' }}</small>
    </li>
  {% endfor %}
</ul>

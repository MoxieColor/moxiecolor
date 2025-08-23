---
layout: default
title: Installations
permalink: /installations/
description: "Site-specific and immersive works."
---

{% assign items = site.pages | where: "type", "install" | sort: "date" | reverse %}

<ul class="gallery-grid">
  {% for work in items %}
  <li>
    <a href="{{ work.url | relative_url }}">
      <img src="{{ work.image | default: '/assets/images/placeholders/portfolio.jpg' | relative_url }}"
           alt="{{ work.title | escape }}" loading="lazy" decoding="async">
      <span>{{ work.title }}</span>
    </a>
  </li>
  {% endfor %}
</ul>

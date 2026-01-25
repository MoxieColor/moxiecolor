---
layout: default
title: "Moxie Zines"
permalink: /moxie-zines/
---

# Moxie Zines

{% assign zines = site['moxie-zines'] | sort: 'date' | reverse %}
<ul>
  {% for z in zines %}
    <li>
      <a href="{{ z.url | relative_url }}">{{ z.title }}</a>
      {% if z.date %}<span class="muted"> — {{ z.date | date: "%b %d, %Y" }}</span>{% endif %}
    </li>
  {% endfor %}
</ul>

---
layout: default
title: "Moxie Color | Shop"
permalink: /shop/
---

<p class="lede">Collect my art in digital or physical form.
<strong>Instant downloads</strong> for the impatient. <strong>Fabric & decor</strong> for the dreamers.</p>

<div class="shop-grid">
  {% for s in site.data.storefronts %}
  <article class="shop-card">
    <div class="img-wrap">
      <a class="img-link" aria-label="Shop {{ s.name }}"
         {% if s.url %}href="{{ s.url }}"{% endif %}
         {% if s.status != 'waitlist' %}target="_blank" rel="noopener"{% endif %}>
        <img src="{{ s.image | relative_url }}" alt="{{ s.name }} preview">
      </a>
      {% if s.badge %}
        <span class="badge badge--overlay">{{ s.badge }}</span>
      {% endif %}
    </div>

    <h3>{{ s.name }}</h3>
    <p>{{ s.blurb }}</p>

    {% if s.status == 'waitlist' %}
      <a class="btn" href="{{ s.waitlist_url | relative_url }}">Notify me</a>
    {% else %}
      <a class="btn" href="{{ s.url }}" target="_blank" rel="noopener">Shop {{ s.name }} ↗</a>
    {% endif %}

    {% if s.trust and s.status != 'waitlist' %}
  <p class="trust">{{ s.trust }}</p>
{% endif %}

    {% if s.featured %}
      <ul class="featured">
        {% for f in s.featured %}
          <li>
            <a href="{{ f.url }}" target="_blank" rel="noopener">
              {{ f.title }} ↗
            </a>
          </li>
        {% endfor %}
      </ul>
    {% endif %}
  </article>
  {% endfor %}
</div>

<p class="fineprint">Questions about usage or returns? See
  <a href="{{ '/licensing/' | relative_url }}">Licensing</a> and
  <a href="{{ '/faq/' | relative_url }}">FAQ</a>.
  Purchases are handled securely by each storefront.</p>

---
layout: default
title: Hue & Tell — Newsletter
permalink: /newsletter/
description: "Short studio stories + a quick Moxie Lab Minute. 1–2×/month. No spam."
---

{% assign sample = site.data.issues | first %}

<section class="nl-hero">
  <div class="nl-hero-grid">
    <!-- Left: sample issue card -->
    <a class="sample-card"
       href="{{ sample.url }}?utm_source=site&utm_medium=sample_card&utm_campaign=hue_and_tell"
       aria-label="Read a sample: {{ sample.title }}">
      <img
        src="{{ (sample.image | default: '/assets/newsletter/placeholder.jpg') | relative_url }}"
        alt="{{ sample.title }} cover"
        loading="lazy">
      <span class="sample-badge">Read a sample →</span>
    </a>

    <!-- Right: copy + CTA -->
    <div class="hero-copy">
      <h1>Hue & Tell</h1>
      <p class="lead">
        Short studio stories + a quick <strong>Moxie Lab Minute</strong>. 1–2×/month. No spam.
      </p>

      <a class="btn"
         href="https://mailchi.mp/d9fccc887890/join-hue-and-tell?utm_source=site&utm_medium=newsletter_page&utm_campaign=hue_and_tell"
         target="_blank" rel="noopener noreferrer">
        Subscribe free
      </a>

      <ul class="nl-benefits">
        <li>Studio peeks & process notes</li>
        <li>Tiny tests → bold results (Moxie Lab Minute)</li>
        <li>Early dibs & occasional exclusives</li>
      </ul>
    </div>
  </div>
</section>

<section class="nl-issues">
  <h2>Back Issues</h2>  
  <p class="all-issues"><a href="{{ '/newsletter/archive/' | relative_url }}">View all →</a></p> 
  <div class="issues-grid">
    {% assign latest = site.data.issues | slice: 0, 6 %}
    {% for i in latest %}
      <article class="issue-card">
        <h3><a href="{{ i.url }}?utm_source=site&utm_medium=back_issues&utm_campaign=hue_and_tell">{{ i.title }}</a></h3>
        <p class="meta">{{ i.date | date: "%b %-d, %Y" }}</p>
        <p>{{ i.blurb }}</p>
      </article>
    {% endfor %}
  </div>
</section>

<section class="nl-faq small">
  <p><strong>How often?</strong> 1–2×/month. <strong>Unsubscribe?</strong> Anytime with one click. <strong>Privacy?</strong> I only use your email to send Hue & Tell.</p>
</section>

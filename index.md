---
layout: default
title: "Moxie Color | A Creative Enterprise"
permalink: /
---
<section>
  <p>Hi, I’m Jenn — I create art that visually merges color, texture, and narrative. Every piece tells a layered story. Explore my latest work, discover digital downloads, or connect for collaborations.</p>
</section>

<section class="hero">
  <div class="hero-text">
    <h2>Logic is found in the chaos around us.</h2>
    <p>Bold art for curious minds.</p>
    <div class="cta">
      <a class="btn" href="{{ '/shop/' | relative_url }}">Shop My Art</a>
      <a class="btn" href="{{ '/newsletter/' | relative_url }}">Subscribe to Hue & Tell</a>
      <a class="btn" href="{{ '/about/' | relative_url }}">About the Artist - Me</a>
    </div>
  </div>
  <div class="hero-image">
    <!-- Replace with your strongest piece -->
    <img src="{{ 'assets/images/portfolio/meditations/StargazingIntoTheBlue.jpeg' | relative_url }}" alt="Stargazing into the Blue, Original acrylic painting, 42&quot;x60&quot; ">
  </div>
</section>  

## Portfolio  

{% comment %}
Pull the newest page for each type by date.
{% endcomment %}
{% assign latest_install = site.pages | where: "type", "install" | sort: "date" | reverse | first %}
{% assign latest_series  = site.pages | where: "type", "series"  | sort: "date" | reverse | first %}
{% assign latest_small   = site.pages | where: "type", "small"   | sort: "date" | reverse | first %}

{% comment %}
Find the category landing pages so links stay correct even if URLs change.
{% endcomment %}
{% assign installations_page = site.pages | where: "name", "installations.md" | first %}
{% assign pcd_page          = site.pages | where: "name", "paintings-collage-drawings.md" | first %}
{% assign smallworks_page   = site.pages | where: "name", "small-works-studies.md" | first %}

<style>
  .portfolio-grid{
    display:grid;
    gap:1rem;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  }
  .portfolio-card{
    display:block;
    border:1px solid color-mix(in oklab, currentColor 10%, transparent);
    border-radius:16px;
    overflow:hidden;
    text-decoration:none;
    background: color-mix(in oklab, Canvas 98%, currentColor 2%);
    transition: transform .12s ease, box-shadow .12s ease;
  }
  .portfolio-card:hover{ transform: translateY(-2px); box-shadow: 0 6px 18px rgba(0,0,0,.12); }
  .portfolio-card img{
    width:100%;
    aspect-ratio: 4/3;
    object-fit: cover;
    display:block;
  }
  .portfolio-card figcaption{ padding: .9rem 1rem; }
  .portfolio-card h3{ margin:0 0 .25rem; font-size:1.1rem; }
  .portfolio-card p{ margin:0; opacity:.75; font-size:.95rem; }
</style>

<div class="portfolio-grid">
  {%- assign series_img = latest_series.image | default: "/assets/images/placeholders/portfolio.jpg" -%}
  <a class="portfolio-card" href="{{ pcd_page.url | relative_url }}">
    <figure>
      <img src="{{ series_img | relative_url }}" alt="{{ latest_series.title | default: 'Paintings, Collage, & Drawings' | escape }}" loading="lazy" decoding="async">
      <figcaption>
        <h3>Paintings, Collage, &amp; Drawings</h3>
      <!--  <p>{{ latest_series.title | default: "Latest series work" }}</p> -->
      </figcaption>
    </figure>
  </a>

  {%- assign small_img = latest_small.image | default: "/assets/images/placeholders/portfolio.jpg" -%}
  <a class="portfolio-card" href="{{ smallworks_page.url | relative_url }}">
    <figure>
      <img src="{{ small_img | relative_url }}" alt="{{ latest_small.title | default: 'Small Works' | escape }}" loading="lazy" decoding="async">
      <figcaption>
        <h3>Small Works, Studies, &amp; Sketches</h3>
     <!--   <p>{{ latest_small.title | default: "Latest small work" }}</p> -->
      </figcaption>
    </figure>
  </a>

  {%- assign install_img = latest_install.image | default: "/assets/images/placeholders/portfolio.jpg" -%}
  <a class="portfolio-card" href="{{ installations_page.url | relative_url }}">
    <figure>
      <img src="{{ install_img | relative_url }}" alt="{{ latest_install.title | default: 'Installations' | escape }}" loading="lazy" decoding="async">
      <figcaption>
        <h3>Installations</h3>
       <!-- <p>{{ latest_install.title | default: "Latest installation" }}</p> -->
      </figcaption>
    </figure>
  </a>

</div>

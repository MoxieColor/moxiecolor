---
layout: default
title: "Moxie Color | A Creative Enterprise"
permalink: /homepage-test/
---
<!-- Gumroad overlay script -->
<script src="https://gumroad.com/js/gumroad.js"></script>

<section>
  <p>Hi, I’m Jenn — I create art that visually merges color, texture, and narrative. Every piece tells a layered story. Explore my latest work, discover digital downloads, or connect for collaborations.</p>
</section>

<style>
  /* Brand hero: full-width text + CTA (no image) */
  .brand-hero{
    display:block;
    margin-block:1.5rem 2rem;
    padding:1.25rem 1.25rem 1.5rem;
    border:1px solid rgba(0,0,0,.08);
    border-radius:1rem;
    background:#fff;
    box-shadow:0 8px 24px rgba(0,0,0,.06);
  }
  .brand-hero h2{margin:.1rem 0 .35rem 0}
  .brand-hero p{margin:0 0 .75rem 0}

  /* Shared buttons */
  .btn{display:inline-block;padding:.9rem 1.1rem;border-radius:.75rem;background:#111;color:#fff;
       text-decoration:none;font-weight:700;line-height:1}
  .btn.light{background:#222}
  .cta-row{display:flex;gap:.6rem;flex-wrap:wrap;margin-top:.25rem}

  /* Product heroes (stacked) */
  .hero{display:grid;grid-template-columns:1.1fr 1fr;gap:2rem;align-items:center;margin-block:2rem 2.5rem}
  .hero img{width:100%;height:auto;border-radius:1rem;box-shadow:0 10px 30px rgba(0,0,0,.12)}
  .hero h1,.hero h2{margin:0 0 .5rem 0}
  .hero.reverse{grid-template-columns:1fr 1.1fr}
  @media (max-width:900px){.hero,.hero.reverse{grid-template-columns:1fr}}

  /* Featured cards */
  .featured-grid{display:grid;gap:1rem;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));margin-block:2rem}
  .card{background:#fff;border:1px solid rgba(0,0,0,.08);border-radius:1rem;padding:1rem}
  .card img{width:100%;height:auto;border-radius:.75rem;margin-bottom:.65rem}
  .card h3{margin:.25rem 0 .4rem 0}

  /* Portfolio grid */
  .portfolio-grid{display:grid;gap:1rem;grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));}
  .portfolio-card{display:block;border:1px solid color-mix(in oklab, currentColor 10%, transparent);border-radius:16px;overflow:hidden;text-decoration:none;background: color-mix(in oklab, Canvas 98%, currentColor 2%);transition: transform .12s ease, box-shadow .12s ease;}
  .portfolio-card:hover{ transform: translateY(-2px); box-shadow: 0 6px 18px rgba(0,0,0,.12); }
  .portfolio-card img{width:100%;aspect-ratio: 4/3;object-fit: cover;display:block;}
  .portfolio-card figcaption{ padding: .9rem 1rem; }
  .portfolio-card h3{ margin:0 0 .25rem; font-size:1.1rem; }

  /* Newsletter block */
  .newsletter{display:grid;grid-template-columns:1.2fr 1fr;gap:1.5rem;align-items:center;margin-block:2.5rem}
  .newsletter .panel{background:#fff;border:1px solid rgba(0,0,0,.08);border-radius:1rem;padding:1.25rem}
  @media (max-width:900px){.newsletter{grid-template-columns:1fr}}

  /* Quicklinks bar (optional) */
  .quicklinks{display:flex;gap:.75rem;flex-wrap:wrap;margin:2rem 0}
  .quicklinks a{background:#f5f5f5;border:1px solid rgba(0,0,0,.08);padding:.6rem .8rem;border-radius:.65rem;text-decoration:none;color:inherit}
</style>

<!-- BRAND HERO (no image) -->
<section class="brand-hero">
  <h2>Logic is found in the chaos around us.</h2>
  <p>Bold art for curious minds.</p>
  <div class="cta-row">
    <a class="btn" href="{{ '/shop/' | relative_url }}">🔥 Shop the New Drop</a>
    <a class="btn light" href="{{ '/shop/' | relative_url }}#freebies">🎁 Get a Freebie</a>
    <a class="btn light" href="{{ '/newsletter/' | relative_url }}">📩 Subscribe to Hue & Tell</a>
  </div>
</section>

<!-- HERO #1: SysAdmin Neon -->
<section class="hero">
  <img src="{{ '/assets/images/stores/sysadmin-superbundle.png' | relative_url }}"
       alt="Neon zine collage posters — You Are Your Own Sysadmin mega bundle preview.">
  <div>
    <h1>🔥 Limited Collector’s Edition Posters — Only 50 with Exclusives</h1>
    <p><strong>Six neon zine collages × six colorways = 36 instant-download posters.</strong><br>
    First 50 buyers also get <em>Mad Cat</em> + <em>Bad Dog</em>. Once they’re gone, they’re gone.</p>
    <div class="cta-row">
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/you-are-your-own-sysadmin"
         data-gumroad-overlay-checkout="true">Get the Collector’s Edition →</a>
    </div>
  </div>
</section>

<!-- HERO #2: ProtoNext Foundation (flipped layout) -->
<section class="hero reverse">
  <div>
    <h2>🧪 ProtoNext Vol. 1–3 — <em>The Foundation Set</em></h2>
    <p>Three volumes of acrylic+ink prints pulled from sold-out originals — curated into a print-ready bundle for instant download.</p>
    <div class="cta-row">
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/the-foundation-set"
         data-gumroad-overlay-checkout="true">Get the Foundation Set →</a>
    </div>
  </div>
  <img src="{{ '/assets/images/stores/protonext-thebundle-thumbnail.png' | relative_url }}"
       alt="ProtoNext Foundation Set — printable wall art bundle preview.">
</section>

<!-- FEATURED: drive to Portfolio with shop buttons on page -->
<section>
  <h2>Featured Collections</h2>
  <div class="featured-grid">
    <div class="card">
      <img src="{{ '/assets/images/stores/sysadmin-neon-kiss.png' | relative_url }}" alt="SysAdmin Neon Posters — colorways preview.">
      <h3>SysAdmin Neon Posters (Collector’s Edition)</h3>
      <a class="btn" href="{{ '/sysadmin/' | relative_url }}">Explore You Are Your Own Sysadmin →</a>
    </div>
    <div class="card">
      <img src="{{ '/assets/images/stores/protonext-the-inked-series.png' | relative_url }}" alt="ProtoNext — The Inked Series preview.">
      <h3>Learn more about ProtoNext</h3>
      <a class="btn" href="{{ '/protonext/' | relative_url }}#protonext">Explore ProtoNext →</a>
    </div>
  </div>
</section>

## Portfolio

{% comment %}
Pull the newest page for each type by date.
{% endcomment %}
{% assign latest_install = site.pages | where: "type", "install" | sort: "date" | reverse | first %}
{% assign latest_series  = site.pages | where: "type", "series"  | sort: "date" | reverse | first %}
{% assign latest_small   = site.pages | where: "type", "small"   | sort: "date" | reverse | first %}

{% comment %} Find the category landing pages so links stay correct even if URLs change. {% endcomment %}
{% assign installations_page = site.pages | where: "name", "installations.md" | first %}
{% assign pcd_page          = site.pages | where: "name", "paintings-collage-drawings.md" | first %}
{% assign smallworks_page   = site.pages | where: "name", "small-works-studies.md" | first %}

<div class="portfolio-grid">
  {%- assign series_img = latest_series.image | default: "/assets/images/placeholders/portfolio.jpg" -%}
  <a class="portfolio-card" href="{{ pcd_page.url | relative_url }}">
    <figure>
      <img src="{{ series_img | relative_url }}" alt="{{ latest_series.title | default: 'Paintings, Collage, & Drawings' | escape }}" loading="lazy" decoding="async">
      <figcaption><h3>Paintings, Collage, &amp; Drawings</h3></figcaption>
    </figure>
  </a>

  {%- assign small_img = latest_small.image | default: "/assets/images/placeholders/portfolio.jpg" -%}
  <a class="portfolio-card" href="{{ smallworks_page.url | relative_url }}">
    <figure>
      <img src="{{ small_img | relative_url }}" alt="{{ latest_small.title | default: 'Small Works' | escape }}" loading="lazy" decoding="async">
      <figcaption><h3>Small Works, Studies, &amp; Sketches</h3></figcaption>
    </figure>
  </a>

  {%- assign install_img = latest_install.image | default: "/assets/images/placeholders/portfolio.jpg" -%}
  <a class="portfolio-card" href="{{ installations_page.url | relative_url }}">
    <figure>
      <img src="{{ install_img | relative_url }}" alt="{{ latest_install.title | default: 'Installations' | escape }}" loading="lazy" decoding="async">
      <figcaption><h3>Installations</h3></figcaption>
    </figure>
  </a>
</div>

<!-- Newsletter hook -->
<section class="newsletter">
  <div class="panel">
    <h2>✨ Hue & Tell — Join the list</h2>
    <p>Bold color, creative rituals, and occasional freebies. Short, thoughtful notes from the studio.</p>
    <div class="cta-row">
      <a class="btn" href="{{ '/newsletter/' | relative_url }}">Subscribe to Hue & Tell →</a>
      <a class="btn light" href="{{ '/shop/' | relative_url }}#freebies">Grab a Freebie →</a>
    </div>
  </div>
  <img src="{{ '/assets/images/stores/Cheshire-Purple-thumbnail.webp' | relative_url }}" alt="Purple Cheshire Cat poster — newsletter vibe image." />
</section>

<!-- Optional quicklinks strip (remove if your global footer already covers this) -->
<div class="quicklinks">
  <a href="{{ '/shop/' | relative_url }}">Shop</a>
  <a href="{{ '/newsletter/' | relative_url }}">Newsletter</a>
  <a href="{{ '/portfolio/' | relative_url }}">Portfolio</a>
  <a href="{{ '/about/' | relative_url }}">About</a>
  <a href="{{ '/licensing/' | relative_url }}">Licensing</a>
  <a href="{{ '/faq/' | relative_url }}">FAQ</a>
</div>

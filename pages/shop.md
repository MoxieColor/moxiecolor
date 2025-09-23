---
layout: default
title: "Shop"
permalink: /shop/
description: "Limited Collector’s Edition Posters and printables from MoxieColor."
---

<!-- Gumroad overlay script -->
<script src="https://gumroad.com/js/gumroad.js"></script>

<style>
  .hero{display:grid;grid-template-columns:1.1fr 1fr;gap:2rem;align-items:center;margin-block:2rem 2.5rem}
  .hero img{width:100%;height:auto;border-radius:1rem;box-shadow:0 10px 30px rgba(0,0,0,.12)}
  .hero h1,.hero h2{margin:0 0 .5rem 0}
  .hero.reverse{grid-template-columns:1fr 1.1fr}
  
  /* Unified button style (matches Collector’s Edition button) */
  .btn{display:inline-block;padding:.9rem 1.1rem;border-radius:.75rem;background:#111;color:#fff;
       text-decoration:none;font-weight:700;line-height:1}
  .btn.secondary{background:#222}
  .btn:hover{opacity:.92}

  .benefits{list-style:none;padding-left:0;margin-top:1rem}
  .benefits li{margin:.35rem 0}

  .section{margin-block:2.5rem}
  .cards {display: grid;  gap: 1.25rem;  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));}
  .card{background:#fff;border:1px solid rgba(0,0,0,.08);border-radius:1rem;padding:1rem}
  .card img{width:100%;height:auto;border-radius:.75rem;margin-bottom:.75rem}
  .card h3{margin:.25rem 0 .25rem 0}

  .bundles-list{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:1.25rem}
  .bundle{background:#fff;border:1px solid rgba(0,0,0,.08);border-radius:1rem;padding:1rem}
  .bundle img{width:100%;height:auto;border-radius:.75rem;margin-bottom:.65rem}
  .bundle h4{margin:.25rem 0 .5rem 0}

  .explore-list{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:1.25rem}
  .explore-card{background:#fff;border:1px solid rgba(0,0,0,.08);border-radius:1rem;padding:1rem}
  .explore-card img{width:100%;height:auto;border-radius:.75rem;margin-bottom:.65rem}

  .note{font-size:.9rem;color:#555;margin-top:.5rem}
  .section[id] { scroll-margin-top: 96px; } /* adjust to your header height */
  
  /* Force square, top-left crop for Explore cards */
  .explore-list{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:1.25rem}
  .explore-card{background:#fff;border:1px solid rgba(0,0,0,.08);border-radius:1rem;padding:1rem}
  .explore-card .thumb{aspect-ratio:1/1;width:100%;overflow:hidden;border-radius:.75rem;background:#f6f6f6;margin-bottom:.65rem}
  .explore-card .thumb img{width:100%;height:100%;object-fit:cover;object-position:left top;display:block}

  @media (max-width:900px){
    .hero,.hero.reverse{grid-template-columns:1fr}
    .cards{grid-template-columns:1fr}
    .bundles-list{grid-template-columns:1fr}
    .explore-list{grid-template-columns:1fr}
  }
</style>

<section class="hero">
  <img src="/assets/images/stores/sysadmin-superbundle.png"
       alt="Neon zine collage posters in multiple colorways — You Are Your Own Sysadmin mega bundle preview.">
  <div>
    <h1>🔥 Limited Collector’s Edition Posters — Only 50 with Exclusives</h1>
    <p><strong>Six neon zine collages × six colorways = 36 instant-download posters.</strong><br>
    Each file is 5400×7200 px, 300 dpi — perfect for printing, framing, or plastering across your favorite wall.</p>
    <p>For the first 50 buyers only, this drop also includes two retired designs:<br>
    🐾 <em>Mad Cat</em> + 🐾 <em>Bad Dog</em>. Once they’re gone, they’re gone.</p>
    <a class="btn" href="https://moxiecolor.gumroad.com/l/you-are-your-own-sysadmin?utm_source=site&utm_medium=shop&utm_campaign=sysadmin_drop&utm_content=hero_btn"
       data-gumroad-overlay-checkout="true">Get the Collector’s Edition →</a>
    <ul class="benefits">
      <li>✅ Instant digital download — print today, hang tonight</li>
      <li>✅ All colorways included — change your vibe anytime</li>
      <li>✅ Limited Collector’s Edition — first 50 include Mad Cat + Bad Dog</li>
      <li>✅ Secure checkout via Gumroad</li>
    </ul>
  </div>
</section>

<section class="hero reverse">
  <div>
    <h2>🧪 ProtoNext Vol. 1–3 Bundle — <em>The Foundation Set</em></h2>
    <p>Three volumes of acrylic+ink prints pulled from sold-out originals — curated into a print-ready bundle for instant download.</p>
    <ul class="benefits">
      <li>✅ 3 volumes × 6 prints each — gallery-ready files</li>
      <li>✅ Instant download — print today, frame tonight</li>
      <li>✅ Works as a coordinated wall set or gifts</li>
    </ul>
    <a class="btn" href="https://moxiecolor.gumroad.com/l/the-foundation-set?utm_source=site&utm_medium=shop&utm_campaign=protonext_foundation&utm_content=hero_btn"
       data-gumroad-overlay-checkout="true">Get the Foundation Set →</a>
  </div>

  <img src="/assets/images/stores/protonext-thebundle-thumbnail.png"
       alt="ProtoNext Foundation Set — printable wall art bundle preview.">
</section>

<hr>


<section class="section" id="freebies">
  <h2>🎁 Freebies to Try</h2>
  <p>Get a taste of the Moxie vibe before diving into the full collection.</p>
  
  <div class="cards">
    <article class="card">
      <img src="/assets/images/portfolio/shes-had-enough/shes-had-enough-wallpaper-square.svg"
           alt="Free poster and device wallpapers — She’s Had Enough pattern.">
      <h3>“She’s Had Enough” — Free Poster + Wallpapers</h3>
      <p>Bold, patterned wall art for screens or walls. Try the vibe free.</p>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/shes-had-enough?utm_source=site&utm_medium=shop&utm_campaign=freebies&utm_content=card_shes_had_enough_btn"
         data-gumroad-overlay-checkout="true">Download Free →</a>
    </article>

    <article class="card">
      <img src="/assets/images/stores/permission-slip-thumbnail.png"
           alt="Permission Slip — Root Access poster thumbnail.">
      <h3>“Permission Slip — Root Access” (Pay What You Like)</h3>
      <p>You are your own sysadmin. Hang it above your desk as a reminder.</p>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/permission-slip?utm_source=site&utm_medium=shop&utm_campaign=freebies&utm_content=card_permission_slip_btn"
         data-gumroad-overlay-checkout="true">Grab It Now →</a>
    </article>
    
    <article class="card">
      <img src="/assets/images/stores/Word Search Trivia Square.png"
           alt="Word Search Trivia sample puzzle page preview.">
      <h3>🧩 Word Search Trivia — Free Sample Puzzle</h3>
      <p>Try before you buy: one full puzzle pulled from the Word Search Trivia book. Print it, solve it, share it.</p>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/word-search-trivia-sample?utm_source=site&utm_medium=shop&utm_campaign=freebies&utm_content=card_wordsearch_sample_btn"
         data-gumroad-overlay-checkout="true">Download Free →</a>
    </article>
  </div>
</section>

<hr>

<section class="section">
  <h2>✨ Theme Bundles</h2>
  <p>If you’ve got a favorite vibe, grab it as a set.</p>

  <!-- Neon row -->
  <div class="bundles-list">
    <div class="bundle">
      <img src="/assets/images/stores/sysadmin-neon-bow-tie.png"
           alt="Neon Bow Tie collage bundle — multiple colorways preview.">
      <h4>🎀 Neon Bow Tie Bundle</h4>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/neon-bow-tie?utm_source=site&utm_medium=shop&utm_campaign=sysadmin_drop&utm_content=bundle_bow_tie_btn"
         data-gumroad-overlay-checkout="true">Buy Bow Tie →</a>
    </div>

    <div class="bundle">
      <img src="/assets/images/stores/sysadmin-neon-kiss.png"
           alt="Neon Kiss collage bundle — multiple colorways preview.">
      <h4>💋 Neon Kiss Bundle</h4>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/neon-kiss?utm_source=site&utm_medium=shop&utm_campaign=sysadmin_drop&utm_content=bundle_kiss_btn"
         data-gumroad-overlay-checkout="true">Buy Kiss →</a>
    </div>

    <div class="bundle">
      <img src="/assets/images/stores/sysadmin-good-pets.png"
           alt="Neon Good Pets collage bundle — cat and dog designs, multiple colorways preview.">
      <h4>🐾 Neon Good Pets Bundle</h4>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/neon-good-pets?utm_source=site&utm_medium=shop&utm_campaign=sysadmin_drop&utm_content=bundle_good_pets_btn"
         data-gumroad-overlay-checkout="true">Buy Good Pets →</a>
    </div>
  </div>

  <!-- ProtoNext row -->
  <div class="bundles-list" style="margin-top:1.25rem">
    <div class="bundle">
      <img src="/assets/images/stores/protonext-the-inked-series.png"
           alt="ProtoNext Vol. 1 — The Inked Series preview.">
      <h4>🖤 ProtoNext Vol. 1 — The Inked Series</h4>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/the-inked-series"
         data-gumroad-overlay-checkout="true">Get Vol. 1 →</a>
    </div>

    <div class="bundle">
      <img src="/assets/images/stores/protonext-the-layered-set.png"
           alt="ProtoNext Vol. 2 — The Layered Set preview.">
      <h4>🧩 ProtoNext Vol. 2 — The Layered Set</h4>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/the-layered-set"
         data-gumroad-overlay-checkout="true">Get Vol. 2 →</a>
    </div>

    <div class="bundle">
      <img src="/assets/images/stores/protonext-the-deep-drift.png"
           alt="ProtoNext Vol. 3 — The Deep Drift preview.">
      <h4>🌊 ProtoNext Vol. 3 — The Deep Drift</h4>
      <a class="btn"
         href="https://moxiecolor.gumroad.com/l/the-deep-drift"
         data-gumroad-overlay-checkout="true">Get Vol. 3 →</a>
    </div>
  </div>
</section>

<hr>

<section class="section">
  <h2>🌐 Explore More</h2>
  <p>These aren’t the main event, but they’re fun side quests:</p>

  <div class="explore-list">
    <div class="explore-card">
      <div class="thumb">
        <img src="/assets/images/portfolio/shes-had-enough/shes-had-enough-wallpaper-square.svg"
             alt="Gumroad storefront preview.">
      </div>
      <h4>More Digital Downloads</h4>
      <p>Posters, prompts, and printables if you love to browse.</p>
      <a class="btn" href="https://moxiecolor.gumroad.com/?utm_source=site&utm_medium=shop&utm_campaign=explore&utm_content=explore_gumroad_card">See all on Gumroad →</a>
    </div>

    <div class="explore-card">
      <div class="thumb">
        <img src="/assets/images/stores/Spoonflower3.png"
             alt="Spoonflower fabric & wallpaper preview.">
      </div>
      <h4>Fabric & Wallpaper</h4>
      <p>Turn designs into tablecloths, cushions, or entire walls.</p>
      <a class="btn" href="https://www.spoonflower.com/profiles/moxiecolor?utm_source=site&utm_medium=shop&utm_campaign=explore&utm_content=explore_spoonflower_card">Shop Spoonflower →</a>
    </div>

    <div class="explore-card">
      <div class="thumb">
        <img src="/assets/images/stores/Word Search Trivia Square.png"
             alt="Word Search Trivia paperback cover.">
      </div>
      <h4>Puzzle Book (Amazon)</h4>
      <p>125 puzzles × 25 categories — for word nerds and brain breakers.</p>
      <a class="btn" href="https://www.amazon.com/dp/B0D8N1T5NQ?utm_source=site&utm_medium=shop&utm_campaign=explore&utm_content=explore_amazon_card" rel="nofollow sponsored">Buy on Amazon →</a>
      <div class="note">Disclosure: This is an Amazon affiliate link. If you purchase, I may earn a small commission at no extra cost to you.</div>
    </div>
  </div>
</section>

<div class="cta-row">
  <a class="btn light" href="#top">↑ Back to top</a>
</div>


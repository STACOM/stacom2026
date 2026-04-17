---
layout: single
title: Accepted Papers
permalink: /papers/
author: stacom
classes:
  - wide
header:
  overlay_image: /images/strasbourg_02.jpg
  overlay_filter: 0.5
  overlay_color: "#1a2340"
  caption: ""
sidebar:
  - nav: "keydates"
  - image: "/images/miccai2026.png"
    image_alt: "MICCAI 2026"
    image_caption: "[MICCAI 2026](https://conferences.miccai.org/2026/en/)"
  - nav: "sidelinks"
---

<style>
/* ── Hero ── */

/* Apply to the whole page */

.site-title {
/* Hide the existing text */
  font-size: 0 !important;
  line-height: 0 !important;
  
  /* Create the container for the logo */
  display: inline-block !important;
  width: 320px;  /* Slightly wider for the MICCAI logo */
  height: 80px;  /* Adjust height to fit the nav bar */
  
  /* Link the image */
  background: url("../images/miccai2026.png") no-repeat center left !important;
  background-size: contain !important;
  
  /* REMOVED the filter so it shows in full color */
  vertical-align: middle;
  margin-right: 15px;
}

/* ── Narrow sidebar ── */
.sidebar.sticky {
  width: 200px !important;
  min-width: 200px !important;
}

/* ── Main content: remove justify, improve reading ── */
.page__content p {
  text-align: justify !important;
  font-size: 0.95em;
  line-height: 1.75;
  color: #333;
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  letter-spacing: 0.01em; /* Slight spacing helps justification legibility */
}
.page__content {
  font-size: 0.95em;
}

/* ── Sidebar headings ── */
.nav__list .nav__sub-title {
  font-size: 0.7em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  color: #1a2340;
  border-bottom: 1.5px solid #dde4ed;
  padding-bottom: 5px;
  margin-bottom: 8px;
}
.nav__list .nav__items li a {
  font-size: 0.8em;
  padding: 2px 0;
  color: #555 !important;
  display: block;
}
.nav__list .nav__items li a[href="#"],
.nav__list .nav__items li a[href=""] {
  pointer-events: none;
  color: #bbb !important;
  font-style: italic;
}
.nav__list .nav__items li a[href*="miccai.org"] {
  color: #185fa5 !important;
  font-weight: 600;
  font-style: normal;
  pointer-events: auto;
}

/* ── Stat bar ── */
.stat-bar {
  display: flex;
  flex-wrap: wrap;
  margin: 24px 0 28px;
  border: 0.5px solid #e0e4ea;
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
}
.stat-item {
  flex: 1;
  min-width: 100px;
  padding: 14px 12px;
  text-align: center;
  border-right: 0.5px solid #e0e4ea;
}
.stat-item:last-child { border-right: none; }
.stat-num {
  font-size: 1.5em;
  font-weight: 700;
  color: #1a2340;
  line-height: 1;
  margin-bottom: 4px;
}
.stat-label {
  font-size: 0.68em;
  color: #999;
  text-transform: uppercase;
  letter-spacing: 0.4px;
}

/* ── Section eyebrow ── */
.section-eyebrow {
  font-size: 0.7em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #185fa5;
  margin: 0 0 4px !important;
}
.page__content h2 {
  margin-top: 4px !important;
  font-size: 1.3em;
}

/* ── Challenge cards ── */
.challenge-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin: 14px 0 24px;
}
@media (max-width: 700px) {
  .challenge-grid { grid-template-columns: 1fr; }
}
.challenge-card {
  border: 0.5px solid #dde4ed;
  border-radius: 8px;
  padding: 16px 18px;
  background: #fff;
  transition: box-shadow 0.15s;
}
.challenge-card:hover {
  box-shadow: 0 2px 10px rgba(26,35,64,0.08);
}
.challenge-tag {
  display: inline-block;
  background: #e6f1fb;
  color: #0c447c;
  font-size: 0.7em;
  font-weight: 700;
  border-radius: 20px;
  padding: 2px 10px;
  margin-bottom: 8px;
  letter-spacing: 0.2px;
}
.challenge-card h3 {
  font-size: 0.95em !important;
  margin: 0 0 7px 0 !important;
  border: none !important;
}
.challenge-card h3 a {
  color: #1a2340 !important;
  text-decoration: none;
}
.challenge-card h3 a:hover { color: #185fa5 !important; }
.challenge-card p {
  font-size: 0.82em !important;
  color: #555 !important;
  margin: 0 0 10px 0 !important;
  line-height: 1.55 !important;
  text-align: justify !important; /* Change this from left */


}
.challenge-link {
  font-size: 0.78em;
  color: #185fa5;
  text-decoration: none;
  font-weight: 600;
}
.challenge-link:hover { text-decoration: underline; }

/* ── Footer ── */
.page__footer {
  background: #1a2340 !important;
  color: #7a9cbf !important;
}
.page__footer a { color: #9fbae8 !important; }
.page__footer-copyright { color: #7a9cbf !important; }



</style>

## Regular papers

<div class="coming-soon-block">
  <div class="cs-sub">
    The list of accepted papers will be published following the notification deadline. In the meantime, please review our <a href="/stacom2026/submission/">Submission Guidelines</a> for detailed formatting and policy information.
  </div>
</div>



<script>
(function() {
  // Find the big title in the hero image
  var title = document.querySelector('.page__hero--overlay .page__title');
  if (title) {
    // Change the big text
    title.innerHTML = 'STACOM 2026';
    
    // Create the smaller "Submission" tagline underneath
    var tag = document.createElement('p');
    tag.className = 'hero-tagline';
    tag.style.cssText = "font-size: 1.1em; color: rgba(255,255,255,0.85); font-weight: 400; margin-top: 0;";
    tag.innerHTML = '17th edition &nbsp;&middot;&nbsp; Papers';
    
    title.parentNode.insertBefore(tag, title.nextSibling);
  }
})();
</script>
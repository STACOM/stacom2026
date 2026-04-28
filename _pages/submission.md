---
layout: single
title: Submission
permalink: /submission/
author: stacom
classes:
  - wide
header:
  overlay_image: /images/strasbourg_04.jpg
  overlay_filter: 0.5
  overlay_color: "#1a2340"
  caption: ""
sidebar:
  - nav: "keydates"
  - image: "/images/miccai2026-logo-france.png"
    image_alt: "MICCAI 2026"
    image_caption: "[MICCAI 2026](https://conferences.miccai.org/2026/en/)"
  - nav: "sidelinks"
---


<style>

.site-title {
/* Hide the existing text */
  font-size: 0 !important;
  line-height: 0 !important;
  
  /* Create the container for the logo */
  display: inline-block !important;
  width: 320px;  /* Slightly wider for the MICCAI logo */
  height: 80px;  /* Adjust height to fit the nav bar */
  
  /* Link the image */
  background: url("../images/miccai2026-logo-france.png") no-repeat center left !important;
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

.topic-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
  gap: 12px;
  margin: 20px 0 32px;
}
.topic-card {
  background: #fff;
  border: 0.5px solid #e0e4ea;
  border-left: 3px solid #185fa5;
  border-radius: 0 8px 8px 0;
  padding: 12px 16px;
  font-size: 0.88em;
  color: #333;
  line-height: 1.5;
}
.section-eyebrow {
  font-size: 0.7em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #185fa5;
  margin: 0 0 4px !important;
}

.rules-list {
  list-style: none;
  padding: 0;
  margin: 16px 0 28px;
}
.rules-list li {
  display: flex;
  gap: 12px;
  align-items: flex-start;
  padding: 10px 0;
  border-bottom: 0.5px solid #f0f0f0;
  font-size: 0.88em;
  color: #333;
  line-height: 1.5;
}
.rules-list li:last-child { border-bottom: none; }
.rule-num {
  flex-shrink: 0;
  width: 22px;
  height: 22px;
  border-radius: 50%;
  background: #e6f1fb;
  color: #185fa5;
  font-size: 0.75em;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 1px;
}

.submission-rules {
  list-style: none;
  padding: 0;
  margin: 20px 0;
}

.submission-rules li {
  display: flex;
  align-items: flex-start;
  margin-bottom: 14px;
  font-size: 0.92em;
  line-height: 1.6;
  color: #444;
  /* Ensures natural word spacing even inside flex containers */
  justify-content: flex-start; 
}

.submission-rules .badge {
  background: #f0f4f8;
  color: #185fa5;
  font-weight: 700;
  font-size: 0.75em;
  min-width: 24px;
  height: 24px;
  border-radius: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 15px; /* Creates consistent space after the number */
  margin-top: 2px;
  flex-shrink: 0;
}

/* Ensure bold text and links don't have artificial extra margins */
.submission-rules strong, 
.submission-rules a {
  margin: 0 4px; /* Natural spacing around special elements */
  display: inline;
}

.submission-rules a {
  color: #185fa5;
  text-decoration: underline;
  text-underline-offset: 3px;
}


</style>

## Scope

We accept regular papers describing new methods in the following (not limited) topics:

<div class="topic-grid">
  <div class="topic-card">Statistical analysis of cardiac morphology and morphodynamics</div>
  <div class="topic-card">Computational modeling and simulation of the heart and great vessels</div>
  <div class="topic-card">Personalisation of cardiac model, electrophysiology and mechanics</div>
  <div class="topic-card">Quantitative cardiac image analysis</div>
  <div class="topic-card">Sharing and reusing cardiac model repositories</div>
  <div class="topic-card">Translational studies of cardiac image analysis in clinical practice</div>
</div>

## Submission guidelines

<ul class="submission-rules">
  <li><span class="badge">1</span> Papers are limited to <strong>8 pages</strong> (text, tables, figures) + up to 2 pages for references.</li>
  <li><span class="badge">2</span> Initial submissions must be <strong>anonymised</strong>. Author names and affiliations are added in the final version.</li>
  <li><span class="badge">3</span> Use the official <a href="http://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines" target="_blank">LNCS templates and guidelines</a>.</li>
  <li><span class="badge">4</span> Camera-ready (proceeding) versions of accepted papers may be up to <strong>12 pages</strong>.</li>
  <li><span class="badge">5</span> Supplementary materials (video, animations) may be submitted as a single <strong>ZIP file</strong>.</li>
  <li><span class="badge">6</span> Selected papers will be published in a Lecture Notes in Computer Science proceeding published by Springer.</li>
</ul>

## Submission portal

<div class="coming-soon-block">
  <div class="cs-title">Submission portal opening soon</div>
  <div class="cs-sub">The submission portal will be announced here once key dates are confirmed.<br>Questions? Contact us at <a href="mailto:stacom@inria.fr">stacom@inria.fr</a></div>
</div>


<script>
(function() {
  var title = document.querySelector('.page__hero--overlay .page__title');
  if (title) {
    // 1. Change the main text to STACOM 2026
    title.innerHTML = 'STACOM 2026';
    
    // 2. Create and inject the tagline
    var tag = document.createElement('p');
    tag.className = 'hero-tagline';
    tag.innerHTML = '17th edition &nbsp;&middot;&nbsp; Submission';
    title.parentNode.insertBefore(tag, title.nextSibling);
  }
})();
</script>

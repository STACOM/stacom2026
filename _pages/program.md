---
layout: single
title: Program
permalink: /program/
author: stacom
classes:
  - wide
header:
  overlay_image: /images/strasbourg_03.jpg
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

.section-eyebrow {
  font-size: 0.72em;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #185fa5;
  margin-bottom: -4px !important;
}
.program-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin: 16px 0 28px;
}
.program-meta-item {
  display: flex;
  align-items: center;
  gap: 8px;
  background: #fff;
  border: 0.5px solid #e0e4ea;
  border-radius: 8px;
  padding: 10px 16px;
  font-size: 0.85em;
  color: #333;
}
.program-meta-item strong {
  color: #1a2340;
}

</style>

## Program

<div class="coming-soon-block">
  <div class="cs-title">Full program coming soon</div>
  <div class="cs-sub">
    The detailed schedule will be published once papers have been accepted.<br>
    Questions? Contact us at <a href="mailto:stacom@inria.fr">stacom@inria.fr</a>
  </div>
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
    tag.innerHTML = '17th edition &nbsp;&middot;&nbsp; Program';
    title.parentNode.insertBefore(tag, title.nextSibling);
  }
})();
</script>
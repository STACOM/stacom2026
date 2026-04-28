---
layout: single
title: Organisers
permalink: /contact/
author: stacom
classes:
  - wide
header:
  overlay_image: /images/strasbourg_05.jpg
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

.org-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 16px;
  margin: 24px 0;
}
.org-card {
  background: #fff;
  border: 0.5px solid #e0e4ea;
  border-radius: 10px;
  padding: 20px 16px;
  text-align: center;
  transition: box-shadow 0.15s;
}
.org-card:hover {
  box-shadow: 0 2px 12px rgba(0,0,0,0.08);
}
.org-avatar {
  width: 52px;
  height: 52px;
  border-radius: 50%;
  background: #e6f1fb;
  color: #185fa5;
  font-size: 16px;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 12px;
}
.org-name {
  font-size: 0.9em;
  font-weight: 600;
  color: #1a1a2e;
  margin-bottom: 4px;
  line-height: 1.3;
}
.org-affil {
  font-size: 0.78em;
  color: #666;
  line-height: 1.4;
}
.contact-block {
  margin-top: 32px;
  padding: 16px 20px;
  background: #f7f9fc;
  border-left: 3px solid #185fa5;
  border-radius: 0 6px 6px 0;
  font-size: 0.9em;
  color: #444;
}
.contact-block a {
  color: #185fa5;
  font-weight: 500;
}
</style>
 
<div class="org-grid">
  <div class="org-card">
    <div class="org-avatar">AY</div>
    <div class="org-name">Alistair Young</div>
    <div class="org-affil">King's College London, United Kingdom</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">MS</div>
    <div class="org-name">Maxime Sermesant</div>
    <div class="org-affil">Inria, France</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">OC</div>
    <div class="org-name">Oscar Camara</div>
    <div class="org-affil">Universitat Pompeu Fabra, Spain</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">EP</div>
    <div class="org-name">Esther Puyol Antón</div>
    <div class="org-affil">King's College London / HeartFlow, Inc.</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">QT</div>
    <div class="org-name">Qian Tao</div>
    <div class="org-affil">Delft University of Technology, Netherlands</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">CM</div>
    <div class="org-name">Charlène Mauger</div>
    <div class="org-affil">King's College London, United Kingdom</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">RP</div>
    <div class="org-name">Rasmus Paulsen</div>
    <div class="org-affil">Danmarks Tekniske Universitet, Denmark</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">MV</div>
    <div class="org-name">Marta Varela</div>
    <div class="org-affil">St George's University of London, United Kingdom</div>
  </div>
  <div class="org-card">
    <div class="org-avatar">YM</div>
    <div class="org-name">YingLiang Ma</div>
    <div class="org-affil">University of East Anglia, United Kingdom</div>
  </div>
</div>
<div class="contact-block">
  For enquiries, please contact us at <a href="mailto:stacom@inria.fr">stacom@inria.fr</a>
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
    tag.innerHTML = '17th edition &nbsp;&middot;&nbsp; Organisers';
    title.parentNode.insertBefore(tag, title.nextSibling);
  }
})();
</script>
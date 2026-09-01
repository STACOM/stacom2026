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

/* ---- Pretty schedule ---- */
.schedule {
  border-radius: 14px;
  overflow: hidden;
  border: 1px solid #e0e4ea;
  box-shadow: 0 2px 10px rgba(26,35,64,0.06);
  margin: 24px 0 40px;
  background: #fff;
}
.schedule-row {
  display: flex;
  align-items: flex-start;
  gap: 20px;
  padding: 16px 22px;
  border-bottom: 1px solid #eef0f4;
}
.schedule-row:last-child {
  border-bottom: none;
}
.schedule-row.highlight {
  background: linear-gradient(90deg, rgba(24,95,165,0.06), rgba(24,95,165,0));
}
.schedule-row.section-label {
  background: #1a2340;
  color: #fff;
  padding: 10px 22px;
}
.schedule-row.section-label .schedule-title {
  color: #fff;
  font-weight: 700;
  letter-spacing: 0.3px;
  text-transform: uppercase;
  font-size: 0.78em;
}
.schedule-time {
  flex: 0 0 118px;
  font-weight: 700;
  color: #185fa5;
  font-size: 0.92em;
  padding-top: 2px;
  white-space: nowrap;
}
.schedule-content {
  flex: 1;
}
.schedule-title {
  font-weight: 600;
  color: #1a2340;
  margin: 0;
}
.schedule-sub {
  color: #5a6270;
  font-size: 0.92em;
  margin-top: 2px;
}
.schedule-talks {
  margin: 6px 0 0;
  padding-left: 18px;
  color: #333;
}
.schedule-talks li {
  margin-bottom: 6px;
  line-height: 1.35;
}
.badge {
  display: inline-block;
  font-size: 0.7em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  color: #185fa5;
  background: #eaf2fb;
  border-radius: 6px;
  padding: 2px 8px;
  margin-left: 8px;
  vertical-align: middle;
}

/* ---- Poster grid ---- */
.poster-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px 24px;
  margin: 18px 0 32px;
}
@media (max-width: 700px) {
  .poster-grid { grid-template-columns: 1fr; }
}
.poster-item {
  display: flex;
  gap: 10px;
  align-items: baseline;
  background: #fff;
  border: 1px solid #eef0f4;
  border-radius: 8px;
  padding: 10px 14px;
  font-size: 0.9em;
  line-height: 1.35;
}
.poster-num {
  flex: 0 0 auto;
  font-weight: 700;
  color: #fff;
  background: #185fa5;
  border-radius: 50%;
  width: 22px;
  height: 22px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.78em;
}
.poster-title {
  color: #1a2340;
}

.contact-note {
  text-align: center;
  color: #5a6270;
  margin-top: 28px;
  font-size: 0.95em;
}
.contact-note a {
  color: #185fa5;
  font-weight: 600;
}

</style>

## Program

<div class="program-meta">
  <div class="program-meta-item">📍 <strong>Location:</strong>&nbsp;Curie B</div>
</div>

<div class="schedule">
  <div class="schedule-row">
    <div class="schedule-time">08:00–08:05</div>
    <div class="schedule-content"><p class="schedule-title">Opening welcome</p></div>
  </div>
  <div class="schedule-row highlight">
    <div class="schedule-time">08:05–08:40</div>
    <div class="schedule-content">
      <p class="schedule-title">Keynote: Limited Resources, Unlimited Impact: Multimodal AI for Healthcare <span class="badge">Keynote</span></p>
      <p class="schedule-sub">Chen (Cherise) Chen, University of Sheffield</p>
    </div>
  </div>

  <div class="schedule-row section-label">
    <div class="schedule-content"><p class="schedule-title">Oral Presentations <span style="font-weight:400; text-transform:none; letter-spacing:0;">— 5 min mini-talk, 3 min questions</span></p></div>
  </div>
  <div class="schedule-row">
    <div class="schedule-time">08:40–10:00</div>
    <div class="schedule-content">
      <ol class="schedule-talks">
        <li>Physiology-Aware Graph Attention for Early Ventricular Reentry Prediction</li>
        <li>Physics-Informed Implicit Neural Representations for Improved Myocardial Perfusion MRI Quantification</li>
        <li>Same Branches, Different Trees: A Bifurcation Connectedness Metric for Coronary Artery Segmentation and FFR-CT Decision Agreement</li>
        <li>Continuous Volumetric Cardiac Motion Modelling for Analytical Derivatives from Cine MRI</li>
        <li>Automated Detection and Shape Analysis of Mitral Valve Prolapse and Annular Disjunction in the UK Biobank</li>
        <li>Beyond In-Distribution Metrics: A Systematic Out-of-Distribution Evaluation of Congenital Heart Disease Segmentation</li>
        <li>MoE-based Feature Adapter for Prompt-free Binary Coronary Artery Segmentation in X-ray Angiography Videos</li>
        <li>Conditional 3D Shape Synthesis of the Left Atrial Appendage via Discrete Latent Diffusion</li>
        <li>Multi-Stage Vascular Deformation Mapping in Extracranial Carotid Aneurysms</li>
        <li>GRC-ProbNet: Uncertainty-aware feature extraction for cardiovascular disease classification</li>
        <li>A Neural Implicit Cardiac Atlas with Clinically Readable Subject Embeddings</li>
        <li>Bi-PT: Bidirectional Cross-Attention Point Transformers for Four-Chamber Heart Reconstruction from Sparse Cardiac MRI Data</li>
      </ol>
    </div>
  </div>

  <div class="schedule-row">
    <div class="schedule-time">10:00–10:30</div>
    <div class="schedule-content"><p class="schedule-title">☕ Coffee break</p></div>
  </div>
  <div class="schedule-row">
    <div class="schedule-time">10:30–10:40</div>
    <div class="schedule-content">
      <p class="schedule-title">Sponsorship presentation: HeartFlow <span class="badge">Sponsor</span></p>
      <p class="schedule-sub">Esther Puyol-Antón</p>
    </div>
  </div>
  <div class="schedule-row">
    <div class="schedule-time">10:40–11:15</div>
    <div class="schedule-content"><p class="schedule-title">Poster teasers</p><p class="schedule-sub">1 min each, 28 speakers</p></div>
  </div>
  <div class="schedule-row highlight">
    <div class="schedule-time">11:15–12:15</div>
    <div class="schedule-content"><p class="schedule-title">Poster session</p><p class="schedule-sub">See full list of accepted papers below</p></div>
  </div>
  <div class="schedule-row">
    <div class="schedule-time">12:15–12:30</div>
    <div class="schedule-content"><p class="schedule-title">🏆 Closing remarks and Prizes</p></div>
  </div>
</div>

### Poster session — full list of accepted papers

<div class="poster-grid">
<div class="poster-item"><span class="poster-num">1</span><span class="poster-title">FDW-Net: Frequency-Decoupled Wavelet Network for Atrial Segmentation in Cardiac MRI</span></div>
<div class="poster-item"><span class="poster-num">2</span><span class="poster-title">MR-JEPA: A General Purpose Video Foundation Model for Cardiac MRI</span></div>
<div class="poster-item"><span class="poster-num">3</span><span class="poster-title">Generative Brownian Bridge Diffusion In Motion Space For Enhanced Myocardial Strain Analysis</span></div>
<div class="poster-item"><span class="poster-num">4</span><span class="poster-title">No Image, No Problem: End-to-End Multi-Task Cardiac Analysis from Undersampled k-Space</span></div>
<div class="poster-item"><span class="poster-num">5</span><span class="poster-title">MoE-based Feature Adapter for Prompt-free Binary Coronary Artery Segmentation in X-ray Angiography Videos</span></div>
<div class="poster-item"><span class="poster-num">6</span><span class="poster-title">Conditional 3D Shape Synthesis of the Left Atrial Appendage via Discrete Latent Diffusion</span></div>
<div class="poster-item"><span class="poster-num">7</span><span class="poster-title">Learning from Acquisition: Metadata-driven Multimodal Pre-training for Cardiac MRI</span></div>
<div class="poster-item"><span class="poster-num">8</span><span class="poster-title">Cardiac MRI Through-Plane Super-Resolution Guided by Reference and Memory</span></div>
<div class="poster-item"><span class="poster-num">9</span><span class="poster-title">IVUS Plaque Characterization Descriptors Carry FFR Information Beyond Morphology in Borderline Lesions</span></div>
<div class="poster-item"><span class="poster-num">10</span><span class="poster-title">Silent Failures of Right-Ventricular Ejection Fraction at High Segmentation Overlap: Evidence from Multi-Vendor Cardiac MRI</span></div>
<div class="poster-item"><span class="poster-num">11</span><span class="poster-title">TSPFN: A Temporal Tabular Foundation Model for Physiological Time Series Classification</span></div>
<div class="poster-item"><span class="poster-num">12</span><span class="poster-title">Automated Reconstruction of Patient-Specific 3D Bi-Atrial Meshes from Sparse 2D Cine CMR</span></div>
<div class="poster-item"><span class="poster-num">13</span><span class="poster-title">Beyond Volume Overlap: Surface Matching for Topology-Aware Coronary Artery Segmentation</span></div>
<div class="poster-item"><span class="poster-num">14</span><span class="poster-title">TT3D: Triangular Transport for 3D Left Ventricle Reconstruction.</span></div>
<div class="poster-item"><span class="poster-num">15</span><span class="poster-title">Same Branches, Different Trees: A Bifurcation Connectedness Metric for Coronary Artery Segmentation and FFR-CT Decision Agreement</span></div>
<div class="poster-item"><span class="poster-num">16</span><span class="poster-title">Beyond the Left Atrium: Joint Generative Modeling of Bi-Atrial Anatomy</span></div>
<div class="poster-item"><span class="poster-num">17</span><span class="poster-title">Physics-Informed Implicit Neural Representations for Improved Myocardial Perfusion MRI Quantification</span></div>
<div class="poster-item"><span class="poster-num">18</span><span class="poster-title">ORION-CMR: On-scanner Reporting with Integrated Foundation Model for End-to-End Cardiac MRI Analysis and Interpretation</span></div>
<div class="poster-item"><span class="poster-num">19</span><span class="poster-title">Bi-PT: Bidirectional Cross-Attention Point Transformers for Four-Chamber Heart Reconstruction from Sparse Cardiac MRI Data</span></div>
<div class="poster-item"><span class="poster-num">20</span><span class="poster-title">ECG-Based Prediction of Patient-Specific Myocardial Conduction Velocity with Electroanatomical Mapping Supervision</span></div>
<div class="poster-item"><span class="poster-num">21</span><span class="poster-title">SynSeq: End-to-End SYNTAX Score Prediction from Coronary Angiography Videos</span></div>
<div class="poster-item"><span class="poster-num">22</span><span class="poster-title">GeodVessel: A Geodesic Cost-Map Framework for Refining Coronary Vessel Connectivity</span></div>
<div class="poster-item"><span class="poster-num">23</span><span class="poster-title">Physiology-Aware Graph Attention for Early Ventricular Reentry Prediction</span></div>
<div class="poster-item"><span class="poster-num">24</span><span class="poster-title">3D Left Ventricular Modelling and Quantification from 2D Echocardiography Using Automated View Positioning</span></div>
<div class="poster-item"><span class="poster-num">25</span><span class="poster-title">Beyond MSE: Rician Likelihood Denoising for Self-Supervised Cardiac T2 and T1ρ MRI</span></div>
<div class="poster-item"><span class="poster-num">26</span><span class="poster-title">A Neural Implicit Cardiac Atlas with Clinically Readable Subject Embeddings</span></div>
<div class="poster-item"><span class="poster-num">27</span><span class="poster-title">GRC-ProbNet: Uncertainty-aware feature extraction for cardiovascular disease classification</span></div>
<div class="poster-item"><span class="poster-num">28</span><span class="poster-title">Integrated CT-derived left atrial digital twins reveal complementary thrombogenic and arrhythmogenic substrates in atrial fibrillation</span></div>
<div class="poster-item"><span class="poster-num">29</span><span class="poster-title">Multi-Stage Vascular Deformation Mapping in Extracranial Carotid Aneurysms</span></div>
<div class="poster-item"><span class="poster-num">30</span><span class="poster-title">Myocardial Strain Drift Correction in Deep Learning Based Ultrasound Tracking</span></div>
<div class="poster-item"><span class="poster-num">31</span><span class="poster-title">MyoUV: Learning Canonical UV Surface Fields for Sparse SAX Myocardial Reconstruction</span></div>
<div class="poster-item"><span class="poster-num">32</span><span class="poster-title">Uncertainty Quantification in Cardiac Model Personalisation from Ultrafast Ultrasound</span></div>
<div class="poster-item"><span class="poster-num">33</span><span class="poster-title">Cardiac Shape-Derived Endophenotypes and Covariant Correction using Statistical Motion Atlases</span></div>
<div class="poster-item"><span class="poster-num">34</span><span class="poster-title">ViPS-FSL: Virtual-Patient Densification via Latent Space Co-Translation for Robust Few-Shot Cardiac MRI Segmentation</span></div>
<div class="poster-item"><span class="poster-num">35</span><span class="poster-title">Beyond In-Distribution Metrics: A Systematic Out-of-Distribution Evaluation of Congenital Heart Disease Segmentation</span></div>
<div class="poster-item"><span class="poster-num">36</span><span class="poster-title">Spatiotemporal Distillation via Recurrent Bottlenecks for Aortic Tracking</span></div>
<div class="poster-item"><span class="poster-num">37</span><span class="poster-title">Automated Detection and Shape Analysis of Mitral Valve Prolapse and Annular Disjunction in the UK Biobank</span></div>
<div class="poster-item"><span class="poster-num">38</span><span class="poster-title">Characterising cardiac tissue properties with graph neural networks</span></div>
<div class="poster-item"><span class="poster-num">39</span><span class="poster-title">Deep Learning Helix Angle Estimation via Rule-based Pre-training and cDTI Fine-tuning</span></div>
<div class="poster-item"><span class="poster-num">40</span><span class="poster-title">Continuous Volumetric Cardiac Motion Modelling for Analytical Derivatives from Cine MRI</span></div>
</div>

<p class="contact-note">Questions? Contact us at <a href="mailto:stacom@inria.fr">stacom@inria.fr</a></p>


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
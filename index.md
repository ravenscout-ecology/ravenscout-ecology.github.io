---
layout: splash
title: "RavenScout Ecological Consulting"
header:
  overlay_image: /assets/images/header-bg.jpg
  overlay_filter: 0.3 # Darkens image slightly so text is readable
  content: >
    <img src="/assets/images/logo.png" alt="RavenScout Logo" style="max-width: 400px; width: 80%; display: block; margin: 0 auto;">
    <br>
    <p style="color: white; font-size: 1.2rem; font-weight: 300;">Putting Science Into Practice</p>
excerpt: "RavenScout Ecological Consulting Inc. provides professional wildlife monitoring and ecological assessment services across the Yukon."
---

<div style="max-width: 900px; margin: 0 auto; text-align: center; font-size: 1.1em; line-height: 1.6;">
  <p>RavenScout Ecological Consulting Inc. provides professional wildlife monitoring and ecological assessment services across the Yukon. We specialize in rigorous, science-based field work, analysis, and reporting that delivers actionable results for land management and conservation decisions.</p>
  
  <p>Our team combines advanced academic training with extensive field experience in bioacoustic monitoring, camera trapping, and environmental data collection. We work with industry, government, and conservation organizations to deliver high-quality ecological data and clear, practical reporting.</p>
</div>

<h2 style="text-align: center; margin-top: 3em;">Our Team</h2>

{% capture anna_bio %}
**Owner/Operator** Master of Science, University of Alberta
{% endcapture %}

{% capture sejer_bio %}
**Biologist** Master of Science, University of Lethbridge  
Professional Biologist (ASPB)  
PhD Candidate, University of Alberta (2022-2027)
{% endcapture %}

{% include feature_row id="team_row" type="left" %}

<div class="grid__wrapper">
  <div class="grid__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="/assets/images/anna.jpg" alt="Anna Jacobsen" style="border-radius: 5px;">
      </div>
      <h3 class="archive__item-title">Anna Jacobsen, MSc</h3>
      <div class="archive__item-excerpt">{{ anna_bio | markdownify }}</div>
    </article>
  </div>
  
  <div class="grid__item">
    <article class="archive__item">
      <div class="archive__item-teaser">
        <img src="/assets/images/sejer.jpg" alt="Sejer Meyhoff" style="border-radius: 5px;">
      </div>
      <h3 class="archive__item-title">Sejer Meyhoff, MSc PBiol</h3>
      <div class="archive__item-excerpt">{{ sejer_bio | markdownify }}</div>
    </article>
  </div>
</div>

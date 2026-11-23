---
layout: profile
permalink: /
title: "Home"
description: "Yuxiao Li | Ph.D. researcher in scientific machine learning, nanophotonics, and optical neural networks at Northeastern University."
redirect_from:
  - /about/
  - /about.html
---

<section class="intro" aria-labelledby="intro-title">
  <div>
    <div class="eyebrow">Hello, I'm</div>
    <h1 id="intro-title">Yuxiao Li</h1>
    <div class="role">Ph.D. Student in Electrical Engineering · <a href="https://www.northeastern.edu/" target="_blank" rel="noopener noreferrer">Northeastern University</a></div>
    <p class="lead">I am a Ph.D. researcher advised by <strong>Prof. Yongmin Liu</strong>. My work focuses on <strong>scientific machine learning, nanophotonic inverse design, and optical computing</strong>, especially physics-aware neural models for electromagnetic systems.</p>
    <p class="muted">I am part of the <a href="https://ymllab.sites.northeastern.edu/our-team/" target="_blank" rel="noopener noreferrer">Liu Lab</a> at Northeastern University. In 2026, I worked as a Machine Learning Engineering Intern at <strong>Mitsubishi Electric Research Laboratories (MERL)</strong> in Cambridge, MA.</p>
    <div class="internship">
      <div>
        <strong>Seeking Summer 2027 Internship Opportunities</strong>
        <span>Interested in machine learning, scientific AI, computational photonics, and optical computing. <a href="mailto:li.yuxiao@northeastern.edu?subject=Summer%202027%20Internship%20Opportunity">Get in touch ↗</a></span>
      </div>
    </div>
    <div class="link-line" aria-label="Academic profiles and contact">
      <a href="https://scholar.google.com/citations?user=13Al7_kAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>
      <a href="https://github.com/YuxiaoLee" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a href="https://www.linkedin.com/in/yuxiao-li-44387524a/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a href="{{ '/cv/' | relative_url }}">CV</a>
      <a href="mailto:li.yuxiao@northeastern.edu">Email</a>
    </div>
  </div>
  <div class="portrait-wrap">
    <img class="headshot" src="https://ymllab.sites.northeastern.edu/files/2024/06/abdd3e00b2cfaadb7c89cfe705656cf1.jpg" alt="Portrait of Yuxiao Li from Yongmin Liu's laboratory website" width="166" height="166" decoding="async">
  </div>
</section>

<section class="section" id="about">
  <h2>Research Interests</h2>
  <ul class="interest-list">
    <li>Physics-aware machine learning</li>
    <li>Coupling-aware metasurface modeling</li>
    <li>Generative inverse design</li>
    <li>Optical neural networks and holography</li>
  </ul>
</section>

<section class="section" id="research">
  <div class="section-header"><h2>Research</h2><a class="inline-link" href="{{ '/research/' | relative_url }}">More research ↗</a></div>
  <div class="item-list">
    <article class="item"><div class="item-date">2025 — Present</div><div class="item-copy"><h3>Coupling-aware metasurface modeling</h3><p>Multimodal graph neural networks that combine geometry and isolated-cell field priors for near-field prediction in spatially varying metasurfaces. Evaluated across a range of array sizes and unseen unit-cell configurations.</p></div></article>
    <article class="item"><div class="item-date">2024 — Present</div><div class="item-copy"><h3>Free-space optical neural networks</h3><p>Optical generative modeling, diffractive systems, and SLM-based experiments with phase-only patterns and camera-measured outputs.</p></div></article>
    <article class="item"><div class="item-date">2022 — Present</div><div class="item-copy"><h3>Optical inverse design</h3><p>Physics-guided optimization and generative models for nanophotonic structures, including multilayer optical designs and on-demand narrowband spectral responses.</p></div></article>
  </div>
</section>

<section class="section" id="experience">
  <div class="section-header"><h2>Industry Experience</h2></div>
  <div class="item-list">
    <article class="item">
      <div class="item-date">Jan – May 2026</div>
      <div class="item-copy">
        <div class="merl-row">
          <a href="https://www.merl.com/" class="merl-logo" target="_blank" rel="noopener noreferrer" aria-label="MERL research laboratory website">
            <img src="https://confcats-siteplex.s3.us-east-1.amazonaws.com/acc26/large_MERL_Logo_c4ece51c4a.png" alt="Mitsubishi Electric Research Laboratories logo" loading="lazy" width="135" height="95">
          </a>
          <div class="merl-description">
            <h3>Machine Learning Engineering Intern</h3>
        <div class="meta">Mitsubishi Electric Research Laboratories (MERL) · Cambridge, MA</div>
        <p>Developed schema-guided DistilBERT and LoRA surrogates for permanent-magnet motor performance prediction across multiple design schemas. Explored continual adaptation with a shared backbone and lightweight task-specific adapters.</p>
        <a class="sub-link" href="https://www.merl.com/publications/TR2026-157" target="_blank" rel="noopener noreferrer">Related publication ↗</a>
          </div>
        </div>
      </div>
    </article>
    <article class="item">
      <div class="item-date">Jan – Feb 2021</div>
      <div class="item-copy">
        <h3>R&amp;D Engineer Assistant</h3>
        <div class="meta">Chengquan Lanchuang Measurement &amp; Control Technology Co., Ltd. · Xi'an, China</div>
        <p>Worked on MATLAB-based noise suppression, IQ signal classification, and signal-envelope extraction; designed and debugged an MC1496 circuit board.</p>
      </div>
    </article>
  </div>
</section>

<section class="section" id="papers">
  <div class="section-header"><h2>Publications</h2><a class="inline-link" href="{{ '/publications/' | relative_url }}">Publication details ↗</a></div>
  <div class="paper-list">
  {% for p in site.data.papers %}
    {% if p.type == "Journal & Conference" %}
      {% include paper-row.html paper=p %}
    {% endif %}
  {% endfor %}
  </div>
  <div class="section-subhead"><h3>Preprint</h3></div>
  <div class="paper-list">
  {% for p in site.data.papers %}
    {% if p.type == "Preprint" %}
      {% include paper-row.html paper=p %}
    {% endif %}
  {% endfor %}
  </div>
</section>

<div class="cta-line">I am open to collaborations and <strong>Summer 2027 internship opportunities</strong>. <a href="mailto:li.yuxiao@northeastern.edu">Contact me ↗</a></div>

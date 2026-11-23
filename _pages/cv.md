---
layout: profile
permalink: /cv/
title: "Curriculum Vitae"
description: "Yuxiao Li: educational background, industry research, research projects, selected publications, and technical skills."
redirect_from:
  - /resume
---

<header class="page-header">
  <h1>Curriculum Vitae</h1>
  <p>Ph.D. researcher in scientific machine learning, electromagnetic surrogate modeling, and optical neural networks. <a href="https://scholar.google.com/citations?user=13Al7_kAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar ↗</a></p>
</header>

<div class="page-content">
  <section class="cv-block" style="border-top:0;padding-top:0">
    <h2>Education</h2>
    <div class="education-row"><h3>Northeastern University</h3><p>Ph.D. in Electrical Engineering · In progress</p><p>Advisor: Prof. Yongmin Liu · Boston, MA</p></div>
    <div class="education-row"><h3>Northeastern University</h3><p>M.S. in Electrical and Computer Engineering · January 2024</p><p>Machine Learning, Computer Vision, and Algorithms · Boston, MA</p></div>
    <div class="education-row"><h3>Xidian University</h3><p>B.E. in Electrical and Information Engineering · June 2022</p><p>Xi'an, China</p></div>
  </section>

  <section class="cv-block">
    <h2>Industry Research Experience</h2>
    <h3>Machine Learning Engineering Intern · Mitsubishi Electric Research Laboratories (MERL)</h3>
    <div class="cv-date">Cambridge, MA · January–May 2026</div>
    <ul>
      <li>Built a schema-guided DistilBERT surrogate for cogging torque and back-EMF prediction across three permanent-magnet motor datasets (~27,700 FEA samples).</li>
      <li>Achieved average R² 0.926 versus 0.889 for ViT-based models; weighted RMSE improved from 0.00066 to 0.00058.</li>
      <li>Used task-specific LoRA adapters on a frozen backbone to support changing design schemas without retraining earlier tasks.</li>
      <li>Reduced added checkpoint storage per schema by approximately 85× (249.37 to 2.92 MiB) and achieved 100% schema-routing accuracy on evaluated shuffled inputs.</li>
    </ul>
  </section>

  <section class="cv-block">
    <h2>Academic Research</h2>
    <h3>Doctoral Researcher · Coupling-Aware Metasurface Modeling</h3><div class="cv-date">Northeastern University · September 2025–Present</div>
    <ul><li>Developed multimodal graph neural networks combining geometry and isolated unit-cell field priors.</li><li>Reduced held-out MSE by 73% on a silicon benchmark (0.0478 to 0.0127); tested Maxwell-residual fine-tuning and unseen unit-cell parameters.</li></ul>
    <h3 style="margin-top:22px">Doctoral Researcher · Free-Space Optical Neural Networks</h3><div class="cv-date">Northeastern University · September 2024–Present</div>
    <ul><li>Studied multilayer metasurface-based free-space optical neural networks for generative modeling and hologram synthesis.</li><li>Conducted SLM experiments with learned phase-only patterns and camera-recorded outputs.</li></ul>
    <h3 style="margin-top:22px">Researcher · Optical Inverse Design</h3><div class="cv-date">Northeastern University · September 2022–June 2023</div>
    <ul><li>Combined genetic algorithms for material-sequence optimization with neural-adjoint optimization of layer thicknesses.</li></ul>
  </section>

  <section class="cv-block">
    <h2>Additional Engineering Experience</h2>
    <h3>R&amp;D Engineer Assistant · Chengquan Lanchuang</h3><div class="cv-date">Xi'an, China · January–February 2021</div>
    <ul><li>Developed MATLAB workflows for noise suppression and IQ classification; designed and debugged an MC1496 circuit board.</li></ul>
  </section>

  <section class="cv-block">
    <h2>Technical Skills</h2>
    <div class="skills-table">
      <strong>Programming</strong><span>Python, MATLAB, C/C++, Verilog HDL</span>
      <strong>Machine Learning</strong><span>PyTorch, GNNs, Transformers, DistilBERT, LoRA, CVAEs, continual learning</span>
      <strong>Simulation &amp; Experiments</strong><span>Electromagnetic simulation, FEA-based surrogates, CST Studio Suite, spatial light modulators, optical holography</span>
    </div>
  </section>

  <section class="cv-block">
    <h2>Teaching &amp; Publications</h2>
    <p>Teaching: EECE 5644 — Introduction to Machine Learning and Pattern Recognition, Northeastern University. <a href="{{ '/teaching/' | relative_url }}">Materials ↗</a></p>
    <p>For selected journal, conference, and preprint publications, see the <a href="{{ '/publications/' | relative_url }}">Publications page ↗</a> or <a href="https://scholar.google.com/citations?user=13Al7_kAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar ↗</a>.</p>
  </section>
  <div class="cta-line">Open to Summer 2027 internship opportunities in scientific machine learning and optical computing. <a href="mailto:li.yuxiao@northeastern.edu">Email me ↗</a></div>
</div>

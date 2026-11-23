---
layout: profile
permalink: /research/
title: "Research"
description: "Research by Yuxiao Li on coupling-aware metasurface modeling, generative photonic inverse design, optical neural networks, and transferable neural surrogates."
---

<header class="subhero">
  <div class="shell"><div class="eyebrow">01 / Research portfolio</div><h1>Research &amp; projects<span style="color:#6780e5">.</span></h1><p>I work at the intersection of machine learning and physical optics — designing models that understand electromagnetic interactions and photonic systems that process information.</p></div>
</header>

<section class="interior-section">
  <div class="shell">
    <article class="deep-card" id="coupling">
      <div class="project-art art-gnn">{% include research-art.html kind="gnn" %}</div>
      <div class="deep-body">
        <div class="index">01 — PHYSICS-AWARE ARTIFICIAL INTELLIGENCE</div>
        <h2>Coupling-aware metasurface modeling</h2>
        <p>Spatially varying metasurfaces exhibit near-field interactions between neighboring meta-atoms, often beyond the locally periodic approximation.</p>
        <p>I develop multimodal graph neural networks combining <strong>meta-atom geometry</strong> and <strong>isolated unit-cell electromagnetic fields</strong> to predict complex, coupling-aware near fields. Related work explores Maxwell-informed regularization and generalization to new array sizes and unseen structural combinations.</p>
        <div class="tag-list"><span>Graph Neural Networks</span><span>Maxwell Equations</span><span>Near Fields</span><span>Aperiodic Metasurfaces</span></div>
        <p class="note">Ongoing research direction.</p>
      </div>
    </article>
    <article class="deep-card" id="generative">
      <div class="project-art art-generative">{% include research-art.html kind="generative" %}</div>
      <div class="deep-body">
        <div class="index">02 — GENERATIVE DESIGN</div>
        <h2>Generative nanophotonic inverse design</h2>
        <p>Inverse photonic design can be nonunique: more than one structure may generate the requested optical response. A single deterministic prediction may therefore miss valid alternatives.</p>
        <p>My work integrates <strong>conditional variational autoencoders</strong> and <strong>tandem networks</strong> to generate candidate nanophotonic structures for target single- and double-notch spectral responses, followed by forward-model screening of their optical behavior.</p>
        <div class="tag-list"><span>CVAE</span><span>Tandem Networks</span><span>Inverse Design</span><span>Narrowband Filters</span></div>
        <a class="text-link" href="https://arxiv.org/abs/2507.14761" target="_blank" rel="noopener noreferrer">Read the preprint <span class="arrow" aria-hidden="true">↗</span></a>
      </div>
    </article>
    <article class="deep-card" id="optical">
      <div class="project-art art-optical">{% include research-art.html kind="optical" %}</div>
      <div class="deep-body">
        <div class="index">03 — OPTICS FOR MACHINE LEARNING</div>
        <h2>Optical neural networks &amp; generative optics</h2>
        <p>Diffractive optical components can encode and transform incoming light before digital processing, creating opportunities for new computational architectures.</p>
        <p>My interests span <strong>free-space optical neural networks</strong>, experimental <strong>spatial-light-modulator (SLM)</strong> systems, and optical generative models where the propagation physics and learning objectives are designed together.</p>
        <div class="tag-list"><span>Optical Neural Networks</span><span>SLM</span><span>Diffractive Optics</span><span>Generative Models</span></div>
        <a class="text-link" href="https://doi.org/10.1063/5.0215752" target="_blank" rel="noopener noreferrer">Read related review <span class="arrow" aria-hidden="true">↗</span></a>
      </div>
    </article>
    <article class="deep-card" id="surrogates">
      <div class="project-art art-surrogate">{% include research-art.html kind="surrogate" %}</div>
      <div class="deep-body">
        <div class="index">04 — ENGINEERING MACHINE LEARNING</div>
        <h2>Adaptable neural surrogates</h2>
        <p>Physics simulations are valuable but expensive, and engineering design tasks often change their input parameterization over time.</p>
        <p>I investigate flexible <strong>neural surrogate models</strong> that represent structured design information and adapt efficiently to new schemas, including Transformer-based approaches and low-rank adaptation in electric-machine design.</p>
        <div class="tag-list"><span>Scientific ML</span><span>Transformers</span><span>LoRA</span><span>Engineering Design</span></div>
        <p class="note">Ongoing research direction.</p>
      </div>
    </article>
    <p class="note">Illustrations above are conceptual diagrams; they are not experimental measurements. Research projects are separated from peer-reviewed publications.</p>
  </div>
</section>

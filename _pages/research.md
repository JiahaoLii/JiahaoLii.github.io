---
title: "Research"
permalink: /research/
author_profile: false
---

<style>
.research-page {
  font-size: 1.08rem;
  line-height: 1.75;
}

.research-page h1 {
  font-size: 1.85rem;
  line-height: 1.35;
  margin-top: 0;
  margin-bottom: 1rem;
  font-weight: 700;
  color: #333333;
}

.research-intro {
  margin-bottom: 1.8rem;
  color: #555555;
}

.research-card {
  display: flex;
  align-items: stretch;
  gap: 2rem;
  margin: 1.8rem 0;
  padding: 1.25rem 1.35rem;
  border-left: 5px solid #d8d8d8;
  border-bottom: 1px solid #eeeeee;
  background: #ffffff;
  transition: box-shadow 0.2s ease, transform 0.2s ease, border-left-color 0.2s ease;
}

.research-card:hover {
  border-left-color: #005a3c;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.06);
  transform: translateY(-2px);
}

.research-image {
  flex: 0 0 34%;
  max-width: 360px;
}

.research-image img {
  width: 100%;
  height: 215px;
  display: block;
  object-fit: cover;
  border-radius: 6px;
}

.research-image img.contain-img {
  object-fit: contain;
  background: #f7f7f7;
}

.research-text {
  flex: 1;
  min-width: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.research-text h2 {
  margin-top: 0;
  margin-bottom: 0.55rem;
  font-size: 1.28rem;
  font-weight: 700;
  line-height: 1.35;
  color: #005a3c;
}

.research-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-bottom: 0.75rem;
}

.research-tag {
  display: inline-block;
  padding: 0.16rem 0.55rem;
  font-size: 0.82rem;
  line-height: 1.4;
  border-radius: 999px;
  border: 1px solid #d7e7df;
  background: #f4faf7;
  color: #005a3c;
}

.research-text p {
  margin-bottom: 0;
  color: #444444;
  line-height: 1.75;
}

.future-box {
  margin-top: 2rem;
  padding: 1.2rem 1.35rem;
  border-left: 5px solid #005a3c;
  background: #f8fbfa;
  border-bottom: 1px solid #eeeeee;
}

.future-box h2 {
  margin-top: 0;
  margin-bottom: 0.6rem;
  font-size: 1.28rem;
  color: #005a3c;
}

.future-box p {
  margin-bottom: 0;
  color: #444444;
  line-height: 1.75;
}

@media (max-width: 768px) {
  .research-card {
    flex-direction: column;
    gap: 1rem;
    padding: 1rem;
  }

  .research-image {
    max-width: 100%;
    flex: 0 0 auto;
  }

  .research-image img {
    height: auto;
  }
}
</style>

<div class="research-page">

<h1>Research</h1>

<p class="research-intro">
My research lies at the intersection of photonics and artificial intelligence, with a focus on programmable photonic devices, inverse design, and AI-assisted electromagnetic modeling.
</p>

<div class="research-card">
  <div class="research-image">
    <img src="/images/research-program.jpg" alt="Programmable photonic devices">
  </div>
  <div class="research-text">
    <h2>Programmable Photonic Devices</h2>
    <div class="research-tags">
      <span class="research-tag">MEMS</span>
      <span class="research-tag">THz Metadevices</span>
      <span class="research-tag">Opto-Logic</span>
    </div>
    <p>
      I work on MEMS-tunable metadevice platforms for programmable spectral responses and opto-logic operation. By independently controlling electrostatically actuated elements, these devices can produce tunable resonances and EIT-like spectral features, enabling reconfigurable terahertz functionality within a compact platform.
    </p>
  </div>
</div>

<div class="research-card">
  <div class="research-image">
    <img class="contain-img" src="/images/research-inverse.jpg" alt="Inverse Design for Metasurfaces">
  </div>
  <div class="research-text">
    <h2>Inverse Design for Photonic Devices</h2>
    <div class="research-tags">
      <span class="research-tag">Inverse Design</span>
      <span class="research-tag">Optimization</span>
    </div>
    <p>
      I am interested in inverse design methods for metasurfaces and photonic devices. Instead of relying only on forward parameter sweeping, inverse design starts from a target optical or electromagnetic response and searches for suitable physical structures, device states, or operating conditions.
    </p>
  </div>
</div>

<div class="research-card">
  <div class="research-image">
    <img src="/images/research-AI.jpg" alt="AI-assisted electromagnetic field modeling">
  </div>
  <div class="research-text">
    <h2>AI-Assisted Electromagnetic Field Modeling</h2>
    <div class="research-tags">
      <span class="research-tag">AI for Science</span>
      <span class="research-tag">Physics-Inspired Learning</span>
    </div>
    <p>
      My machine-learning work focuses on electromagnetic field prediction and reconstruction. I aim to incorporate physics-inspired knowledge into neural networks to improve generalization, reduce the dependence on purely data-driven modeling, and make electromagnetic prediction more efficient and robust.
    </p>
  </div>
</div>

<div class="future-box">
  <h2>Future Interests</h2>
  <p>
    I am interested in extending these methods toward optical neural networks, and AI-assisted inverse design for integrated photonic devices.
  </p>
</div>

</div>

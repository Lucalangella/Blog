---
layout: page
title: "Liminality"
---

<style>
  body { background: #0a0a0a; color: #f0f0f0; }

  .hero {
    padding: 80px 0 60px;
    border-bottom: 1px solid #1e1e1e;
    margin-bottom: 64px;
  }

  .hero-label {
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: #555;
    margin-bottom: 24px;
  }

  .hero-title {
    font-size: clamp(48px, 8vw, 96px);
    font-weight: 700;
    letter-spacing: -0.03em;
    line-height: 1;
    margin: 0 0 24px;
    background: linear-gradient(135deg, #ffffff 0%, #888 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero-slogan {
    font-size: clamp(16px, 2vw, 20px);
    color: #666;
    font-weight: 400;
    max-width: 480px;
    line-height: 1.6;
    margin: 0;
  }

  .articles-label {
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: #555;
    margin-bottom: 32px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2px;
    background: #1a1a1a;
    border-radius: 20px;
    overflow: hidden;
  }

  .card {
    background: #0f0f0f;
    padding: 0;
    text-decoration: none;
    color: inherit;
    display: flex;
    flex-direction: column;
    transition: background 200ms ease;
  }

  .card:hover {
    background: #141414;
  }

  .card:hover .card-arrow {
    transform: translate(3px, -3px);
  }

  .card-cover {
    width: 100%;
    aspect-ratio: 16/9;
    object-fit: cover;
    display: block;
  }

  .card-body {
    padding: 24px;
    flex: 1;
    display: flex;
    flex-direction: column;
    gap: 8px;
  }

  .card-number {
    font-size: 11px;
    letter-spacing: 0.15em;
    color: #444;
  }

  .card-title {
    font-size: 20px;
    font-weight: 600;
    letter-spacing: -0.02em;
    margin: 0;
    line-height: 1.3;
  }

  .card-desc {
    font-size: 14px;
    color: #666;
    margin: 0;
    line-height: 1.6;
    flex: 1;
  }

  .card-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 16px;
    border-top: 1px solid #1e1e1e;
    margin-top: 8px;
  }

  .card-tag {
    font-size: 11px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #444;
  }

  .card-arrow {
    font-size: 16px;
    color: #555;
    transition: transform 200ms ease;
  }
</style>

<div class="hero">
  <p class="hero-label">Est. 2025 &mdash; Luca Langella</p>
  <h1 class="hero-title">Liminality</h1>
  <p class="hero-slogan">Exploring the space between physical and digital experiences &mdash; where design, computation, and perception converge.</p>
</div>

<p class="articles-label">Selected writing</p>

<div class="grid">

  <a class="card" href="https://lucalangella.github.io/Blog/articles/liminality-vision/">
    <img class="card-cover" src="https://lucalangella.github.io/Blog/images/covers/liminality-vision.jpg" alt="Liminality: Between Worlds" />
    <div class="card-body">
      <span class="card-number">01</span>
      <h2 class="card-title">Liminality: Between Worlds</h2>
      <p class="card-desc">Why the space in-between is the most interesting place to design for.</p>
      <div class="card-footer">
        <span class="card-tag">Essay</span>
        <span class="card-arrow">&#8599;</span>
      </div>
    </div>
  </a>

  <a class="card" href="https://lucalangella.github.io/Blog/articles/spatial-experiments/">
    <img class="card-cover" src="https://lucalangella.github.io/Blog/images/covers/spatial-experiments.jpg" alt="Spatial Experiments" />
    <div class="card-body">
      <span class="card-number">02</span>
      <h2 class="card-title">Spatial Experiments</h2>
      <p class="card-desc">Prototyping ideas in 3D interfaces, Vision Pro, and beyond.</p>
      <div class="card-footer">
        <span class="card-tag">Lab</span>
        <span class="card-arrow">&#8599;</span>
      </div>
    </div>
  </a>

  <a class="card" href="https://lucalangella.github.io/Blog/articles/design-systems/">
    <img class="card-cover" src="https://lucalangella.github.io/Blog/images/covers/design-systems.jpg" alt="Design Systems for Liminality" />
    <div class="card-body">
      <span class="card-number">03</span>
      <h2 class="card-title">Design Systems for Liminality</h2>
      <p class="card-desc">Building reusable patterns for hybrid, ambient experiences.</p>
      <div class="card-footer">
        <span class="card-tag">Systems</span>
        <span class="card-arrow">&#8599;</span>
      </div>
    </div>
  </a>

</div>

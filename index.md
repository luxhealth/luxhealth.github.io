---
layout: base
description: Lux Health brings the top, full-stack software solution to independent provider clinics.
title: Best-In-Class, Full-Stack Solution for Independent Provider Clinics
amp_link: /
---

<!-- <section style="width: 100%; text-align: center; padding: 32px 0; position: relative; z-index: 100;">
</section> -->

<main class="constrain-to-1760" style="background: black;">
  <a href="/healthcare-partners" class="hero-badge" style="position: absolute; top: 40%; left: 50%; transform: translate(-50%, -50%);">
    Looking for our previous home page? Click here
  </a>
  <div id="floating-lines-container" style="position: relative; inset: 0; width: 100%; height: 100vh; overflow: hidden; z-index: 0;">
    <h1 style="margin: 0; position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); font-weight: black; font-size: 72px; color: rgba(0,0,0,0.25); text-align: center; width: 100%; pointer-events: none;">
      Lux Health
    </h1>
  </div> 
</main>

<script type="module">
  import FloatingLines from './assets/js/l.js';

  const container = document.getElementById('floating-lines-container');

  if (container) {
    FloatingLines(container, {
      enabledWaves: ['top', 'middle', 'bottom'],
      lineCount: [10, 15, 20],
      lineDistance: [8, 6, 4],
      bendRadius: 5.0,
      bendStrength: -0.5,
      interactive: true,
      parallax: true
    });
  }
</script>

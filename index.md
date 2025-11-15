---
layout: base
description: Lux Health brings the top, full-stack software solution to independent provider clinics.
title: Best-In-Class, Full-Stack Solution for Independent Provider Clinics
amp_link: /
---

<section style="width: 100%; text-align: center;padding: 32px 0; ">
  <a href="/healthcare-partners" class="hero-badge">
    Looking for our previous home page? Click here
  </a>
</section>

<main class="constrain-to-1760" style="background: black;">
  <div id="floating-lines-container" style="width: 100%; height: 60vh; position: relative; overflow: hidden;"></div> 
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

---
layout: default
title: Home
---

<section id="hero" class="hero">
  <img src="{{ '/assets/img/HeroImage.JPG' | relative_url }}" alt="" class="hero-bg" aria-hidden="true">
  <div class="hero-overlay"></div>
  <div class="hero-inner">
    <div class="hero-grid">
      <div class="hero-content">
        <h1>Gavin Prescott<br><em>Robotics &amp; Autonomous Systems</em></h1>
        <div class="hero-card">
          <p>MS in Robotics &amp; Autonomous Systems &mdash; Boston University, expected 2028</p>
          <p>BA in Anthropology &mdash; St. Lawrence University, 2023</p>
        </div>
        <div class="cta-row">
          <a href="#work" class="btn btn-primary">View Work</a>
          <a href="#about" class="btn btn-ghost">About Me</a>
          <a href="{{ site.resume_path | relative_url }}" class="btn btn-ghost">Resume</a>
          <a href="#contact" class="btn btn-ghost">Contact Me</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="work" class="work-section">
  <!--
    Rotating work banner — 5 slides, 6s each, 30s loop.
    To add the Arctos arm as a 6th slide:
      1. add another <img class="banner-slide"> below
      2. in style.css bump the animation to 36s, add a :nth-child(6) delay of 30s,
         and change the keyframe hold values from 20%/22% to 16.7%/18.7%
  -->
  <a href="{{ '/projects/' | relative_url }}" class="work-banner">
    <div class="banner-slides">
      <img class="banner-slide" src="{{ '/assets/img/banner/bagatelle.jpg' | relative_url }}" alt="" aria-hidden="true">
      <img class="banner-slide" src="{{ '/assets/img/banner/mearm.jpg' | relative_url }}" alt="" aria-hidden="true">
      <img class="banner-slide" src="{{ '/assets/img/banner/coolsculpt.jpg' | relative_url }}" alt="" aria-hidden="true">
      <img class="banner-slide" src="{{ '/assets/img/banner/warbird.jpg' | relative_url }}" alt="" aria-hidden="true">
      <img class="banner-slide" src="{{ '/assets/img/banner/truss.jpg' | relative_url }}" alt="" aria-hidden="true">
    </div>
    <div class="banner-veil"></div>
    <div class="banner-caption">
      <div class="banner-caption-inner">
        <div class="banner-card">
          <p>My Work</p>
        </div>
        <span class="banner-cta">View all projects</span>
      </div>
    </div>
  </a>
</section>

<section id="about">
  <div class="container">
    <p class="section-label"><span class="placeholder">[PLACEHOLDER]</span></p>
    <h2><span class="placeholder">[PLACEHOLDER]</span></h2>
    <p class="lede"><span class="placeholder">[PLACEHOLDER — one or two sentences framing the two paths below]</span></p>

    <div class="door-grid">

      <a href="{{ '/about/technical/' | relative_url }}" class="door-card">
        <img class="door-photo" src="{{ '/assets/img/HeroImage.JPG' | relative_url }}" alt="">
        <div class="door-body">
          <p class="door-label"><span class="placeholder">[PLACEHOLDER]</span></p>
          <h3>Technical &amp; Project Experience</h3>
          <p><span class="placeholder">[PLACEHOLDER — what a reader finds down this path]</span></p>
          <span class="door-cta">Read more</span>
        </div>
      </a>

      <a href="{{ '/about/personal/' | relative_url }}" class="door-card">
        <img class="door-photo" src="{{ '/assets/img/headshot.jpg' | relative_url }}" alt="">
        <div class="door-body">
          <p class="door-label"><span class="placeholder">[PLACEHOLDER]</span></p>
          <h3>A More Personal Look</h3>
          <p><span class="placeholder">[PLACEHOLDER — what a reader finds down this path]</span></p>
          <span class="door-cta">Read more</span>
        </div>
      </a>

    </div>
  </div>
</section>

<section id="experience">
  <div class="container">
    <p class="section-label"><span class="placeholder">[PLACEHOLDER]</span></p>
    <h2><span class="placeholder">[PLACEHOLDER]</span></h2>
    <div class="experience-list">

      <article class="experience-item">
        <!--
          Preserved GIS research data (uncomment / restore when writing this card):
          - Author:  Dr. Shinu Anna Abraham
          - Paper:   "Recent Developments in the Archaeology of Long-Distance Connections Across the Ancient Indian Ocean"
          - Journal: Annual Review of Anthropology, vol. 52, pp. 115–135 (2023)
          - DOI:     https://doi.org/10.1146/annurev-anthro-101819-110124
          - Maps:    https://www.annualreviews.org/content/journals/10.1146/annurev-anthro-101819-110124#supplementary_data
        -->
        <h3><span class="placeholder">[PLACEHOLDER]</span></h3>
        <p class="experience-meta"><span class="placeholder">[PLACEHOLDER]</span></p>
        <p><span class="placeholder">[PLACEHOLDER]</span></p>
        <div class="tags">
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
        </div>
        <p class="pub-note"><span class="placeholder">[PLACEHOLDER]</span></p>
        <a href="#" class="project-link"><span class="placeholder">[PLACEHOLDER]</span></a>
      </article>

      <article class="experience-item">
        <h3><span class="placeholder">[PLACEHOLDER]</span></h3>
        <p class="experience-meta"><span class="placeholder">[PLACEHOLDER]</span></p>
        <p><span class="placeholder">[PLACEHOLDER]</span></p>
        <div class="tags">
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
        </div>
      </article>

    </div>
  </div>
</section>

<section id="skills">
  <div class="container">
    <p class="section-label"><span class="placeholder">[PLACEHOLDER]</span></p>
    <h2><span class="placeholder">[PLACEHOLDER]</span></h2>
    <div class="skills-grid">

      <div class="skill-cat">
        <h3><span class="placeholder">[PLACEHOLDER]</span></h3>
        <div class="skill-list">
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
        </div>
      </div>

      <div class="skill-cat">
        <h3><span class="placeholder">[PLACEHOLDER]</span></h3>
        <div class="skill-list">
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
        </div>
      </div>

      <div class="skill-cat">
        <h3><span class="placeholder">[PLACEHOLDER]</span></h3>
        <div class="skill-list">
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
        </div>
      </div>

      <div class="skill-cat">
        <h3><span class="placeholder">[PLACEHOLDER]</span></h3>
        <div class="skill-list">
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
          <span class="tag placeholder">[PLACEHOLDER]</span>
        </div>
      </div>

    </div>
  </div>
</section>

<section id="contact" class="contact">
  <div class="container">
    <p class="section-label">Get in touch</p>
    <h2>Let's make something move.</h2>
    <p class="lede">I'm looking for internships and co-ops in robotics, mechatronics, and embedded systems. If you're building something in that space, I'd like to hear about it.</p>
    <div class="contact-grid">

      <button type="button" class="contact-card contact-copy" data-copy="Gavin.j.prescott@gmail.com">
        <p class="contact-label">Email</p>
        <p class="contact-value">Gavin.j.prescott@gmail.com</p>
        <span class="contact-cue contact-cue-copy">Copy address</span>
      </button>

      <a href="https://www.linkedin.com/in/gavin-prescott/" class="contact-card" target="_blank" rel="noopener">
        <p class="contact-label">LinkedIn</p>
        <p class="contact-value">gavin-prescott</p>
        <span class="contact-cue">Connect</span>
      </a>

      <a href="https://github.com/gavinprescott" class="contact-card" target="_blank" rel="noopener">
        <p class="contact-label">GitHub</p>
        <p class="contact-value">gavinprescott</p>
        <span class="contact-cue">See the code</span>
      </a>

      <a href="{{ '/assets/Resume_Gavin_Prescott_Robotics_Engineer_2026.pdf' | relative_url }}" class="contact-card contact-card-accent">
        <p class="contact-label">Resume</p>
        <p class="contact-value">PDF &middot; Updated 2026</p>
        <span class="contact-cue">Download</span>
      </a>

    </div>
  </div>
</section>

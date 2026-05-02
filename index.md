---
layout: home
title: Home
description: "Software engineer and CS student at KAIST. Building things at the intersection of ML and systems."
---

<section class="hero wrapper">
  <div class="hero-text">
    <h1 class="hero-headline">Software engineer building things that matter.</h1>
    <p class="hero-sub">
      I'm Yersultan — a recent graduate in Computer Science (KAIST, South Korea) interested in HCI, Machine Learning,
      and NLP. I like turning research ideas into working software.
    </p>
    <p class="hero-sub">
      Currently, AI &amp; Systems Engineer at <a href="https://www.stonelab.kr/" target="_blank" rel="noopener"><strong>Stonelab Inc.</strong></a>
    </p>
    <div class="hero-links">
      <a href="/projects" class="primary">View Projects</a>
      <a href="/cv">CV</a>
      <a href="https://github.com/edoszhan" target="_blank" rel="noopener">GitHub</a>
      <a href="mailto:yersultanofficial@gmail.com">Email</a>
      <a href="https://www.linkedin.com/in/edoszhan/">Linkedin</a>
    </div>
  </div>
  <img
    class="hero-photo"
    src="{{ '/assets/fun.jpg' | relative_url }}"
    alt="Yersultan Doszhan"
    width="210"
    height="210"
  >
</section>

<section class="latest wrapper">
  <h2 class="latest-heading">Latest</h2>
  <div class="latest-grid">

    <div class="latest-card">
      {% assign featured = site.posts.first %}
      {% if featured %}
        {% assign featured_cat = featured.categories | first | downcase %}
        <div class="latest-card-meta">{{ featured_cat }} · {{ featured.date | date: "%B %-d, %Y" | downcase }}</div>
        <a class="latest-card-title" href="{{ featured.url | relative_url }}">{{ featured.title }}</a>
        {% if featured.description %}
          <p class="latest-card-excerpt">{{ featured.description }}</p>
        {% endif %}
      {% endif %}
    </div>

    <div class="latest-card latest-card--empty">
      <!-- space reserved for next featured item -->
    </div>

  </div>
</section>

---
layout: page
title: Projects
description: "Software and research projects by Yersultan Doszhan."
---

<div class="projects-header">
  <h1>Projects</h1>
  <p>Things I've built — research prototypes, tools, and side projects.</p>
</div>

<div class="project-list">

<h2 class="projects-section-title">Highlights</h2>

  <div class="project-entry">
    <h2 class="project-entry-title">Neuma</h2>
    <p class="project-entry-desc">AI emotional wellness companion that helps users reflect on their thoughts and understand how their emotions evolve over time. Combines conversational AI with structured emotion tracking, historical context, and tool-assisted retrieval to generate personalized reflections and surface recurring emotional patterns.</p>
    <div class="project-entry-media">
      <figure class="project-media-item project-media-item--highlight">
        <img src="{{ '/assets/projects/highlights/neuma.png' | relative_url }}" alt="Neuma mental-health assistant interface preview" loading="lazy">
        <button class="project-media-zoom" type="button" aria-label="Expand Neuma screenshot" data-lightbox-src="{{ '/assets/projects/highlights/neuma.png' | relative_url }}" data-lightbox-alt="Neuma mental-health assistant interface preview" title="Expand image">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path d="M8 3H3v5M3 3l7 7M16 3h5v5M21 3l-7 7M8 21H3v-5M3 21l7-7M16 21h5v-5M21 21l-7-7"/>
          </svg>
        </button>
      </figure>
    </div>
    <div class="project-entry-tags">
      <span class="proj-tag">FastAPI</span>
      <span class="proj-tag">Valkey</span>
      <span class="proj-tag">OpenRouter</span>
      <span class="proj-tag">TypeScript</span>
      <span class="proj-tag">AWS</span>
    </div>
  </div>

  <div class="project-entry">
    <h2 class="project-entry-title">
      <a href="https://github.com/edoszhan/nomada" target="_blank" rel="noopener">
        Nomada <span class="project-arrow">↗</span>
      </a>
    </h2>
    <p class="project-entry-desc">AI-powered onboarding platform for digital nomads that consolidates travel planning, local setup, workspaces, accommodation, and connectivity into one personalized experience. Uses LLMs and user preferences to generate tailored destination recommendations and onboarding plans, reducing the fragmented research normally required when moving to a new city.</p>
    <div class="project-entry-media">
      <figure class="project-media-item project-media-item--highlight">
        <img src="{{ '/assets/projects/highlights/nomada.png' | relative_url }}" alt="Nomada AI onboarding platform title screen" loading="lazy">
        <button class="project-media-zoom" type="button" aria-label="Expand Nomada screenshot" data-lightbox-src="{{ '/assets/projects/highlights/nomada.png' | relative_url }}" data-lightbox-alt="Nomada AI onboarding platform title screen" title="Expand image">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path d="M8 3H3v5M3 3l7 7M16 3h5v5M21 3l-7 7M8 21H3v-5M3 21l7-7M16 21h5v-5M21 21l-7-7"/>
          </svg>
        </button>
      </figure>
    </div>
    <div class="project-entry-tags">
      <span class="proj-tag">NestJS</span>
      <span class="proj-tag">PostgreSQL</span>
      <span class="proj-tag">n8n</span>
    </div>
  </div>

<h2 class="projects-section-title projects-section-title--spaced">More projects</h2>

  <div class="project-entry">
    <h2 class="project-entry-title">
      <a href="https://github.com/edoszhan/typefare" target="_blank" rel="noopener">
        Typefare <span class="project-arrow">↗</span>
      </a>
    </h2>
    <p class="project-entry-desc">A multiplayer, fast-typing competition platform with a unique twist. Features practice mode, global leaderboards, a discussion forum, and profile-based progress tracking.</p>
    <div class="project-entry-tags">
      <span class="proj-tag">Next.js</span>
      <span class="proj-tag">TypeScript</span>
      <span class="proj-tag">Go</span>
      <span class="proj-tag">PostgreSQL</span>
      <span class="proj-tag">AWS</span>
    </div>
  </div>

  <div class="project-entry">
    <h2 class="project-entry-title">
      <a href="{{ '/assets/projects/presentations/rummsd-presentation.pdf' | relative_url }}" target="_blank" rel="noopener">
        RuMMSD: Russian Multimodal Sarcasm Detection <span class="project-arrow">↗</span>
      </a>
    </h2>
    <p class="project-entry-desc">Built the first comprehensive Russian multimodal sarcasm detection dataset (398 samples) and evaluated state-of-the-art models (GPT-4o, CLIP, Claude-3-haiku). Designed multimodal classifiers using text, images, and generated captions, achieving up to 94% accuracy — competitive with top English benchmarks.</p>
    <div class="project-entry-tags">
      <span class="proj-tag">Python</span>
      <span class="proj-tag">PyTorch</span>
      <span class="proj-tag">NLP</span>
      <span class="proj-tag">Multimodal</span>
      <span class="proj-tag">GPT-4o</span>
      <span class="proj-tag">CLIP</span>
    </div>
  </div>

  <div class="project-entry">
    <h2 class="project-entry-title">
      <a href="{{ '/assets/projects/presentations/lamp-paper.pdf' | relative_url }}" target="_blank" rel="noopener">
        LAMP — Language Model on the Map <span class="project-arrow">↗</span>
      </a>
    </h2>
    <p class="project-entry-desc">Replicated and improved the LAMP framework by integrating LLMs with geospatial data. Built a vector-database-powered RAG system using the Yelp dataset, enabling more truthful, spatially aware point-of-interest recommendations compared to baseline LLM performance.</p>
    <div class="project-entry-tags">
      <span class="proj-tag">Python</span>
      <span class="proj-tag">LangChain</span>
      <span class="proj-tag">Qdrant</span>
      <span class="proj-tag">RAG</span>
    </div>
  </div>

  <div class="project-entry">
    <h2 class="project-entry-title">
      <a href="https://github.com/edoszhan/roomie" target="_blank" rel="noopener">
        Roomie <span class="project-arrow">↗</span>
      </a>
    </h2>
    <p class="project-entry-desc">Mobile app that matches highly compatible roommates using a dual lifestyle-preference survey and a custom "Roomie" persona system. Led matching logic and survey structure to generate personalized compatibility scores and recommendations.</p>
    <div class="project-entry-tags">
      <span class="proj-tag">Flutter</span>
      <span class="proj-tag">Firebase</span>
    </div>
  </div>

  <div class="project-entry">
    <h2 class="project-entry-title">
      <a href="{{ '/assets/projects/presentations/navigo-presentation.pdf' | relative_url }}" target="_blank" rel="noopener">
        Navigo — Junction Asia 2023 <span class="project-arrow">↗</span>
      </a>
    </h2>
    <p class="project-entry-desc">Track winner at Junction Asia (Asia's largest hackathon). Built a tourism web app with GeoGuessr-inspired gamification to boost revenue for local businesses in Busan. Contributed client-side interface and Google Maps integration. Awarded the Mayor of Busan Award.</p>
    <div class="project-entry-tags">
      <span class="proj-tag">React.js</span>
      <span class="proj-tag">Express.js</span>
      <span class="proj-tag">GCP</span>
    </div>
  </div>

</div>

<dialog class="project-lightbox" aria-label="Expanded project screenshot">
  <button class="project-lightbox-close" type="button" aria-label="Close expanded screenshot">Close</button>
  <img class="project-lightbox-image" alt="">
</dialog>

<script>
  (() => {
    const lightbox = document.querySelector('.project-lightbox');
    const lightboxImage = lightbox?.querySelector('.project-lightbox-image');
    if (!lightbox || !lightboxImage) return;

    document.querySelectorAll('.project-media-zoom').forEach((button) => {
      button.addEventListener('click', () => {
        lightboxImage.src = button.dataset.lightboxSrc;
        lightboxImage.alt = button.dataset.lightboxAlt;
        lightbox.showModal();
      });
    });

    lightbox.querySelector('.project-lightbox-close').addEventListener('click', () => {
      lightbox.close();
    });

    lightbox.addEventListener('click', (event) => {
      if (event.target === lightbox) lightbox.close();
    });
  })();
</script>

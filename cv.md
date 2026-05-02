---
layout: page
title: CV
description: "Curriculum vitae of Yersultan Doszhan — software engineer."
---

<div class="cv-wrapper">

  <div class="cv-section">
    <h2>Education</h2>
    <div class="cv-entry">
      <div class="cv-entry-header">
        <span class="cv-entry-org">Korea Advanced Institute of Science and Technology (KAIST)</span>
        <span class="cv-entry-period">Aug 2021 – Feb 2026</span>
      </div>
      <div class="cv-entry-role"><span>B.S. Computer Science, Minor in Artificial Intelligence</span><span class="cv-entry-location">Daejeon, South Korea</span></div>
    </div>
  </div>

  <div class="cv-section">
    <h2>Work Experience</h2>

    <div class="cv-entry">
      <div class="cv-entry-header">
        <span class="cv-entry-org">StoneLab Inc.</span>
        <span class="cv-entry-period">Feb 2026 – Present</span>
      </div>
      <div class="cv-entry-role"><span>AI &amp; Systems Engineer</span><span class="cv-entry-location">Seoul, South Korea</span></div>
      <ul>
        <li>Designed the GEPA optimizer pipeline for autonomous prompt improvement: a three-LM system (student, judge, reflection) that rewrites and evaluates persona reply instructions against 15 objectives (DSPy, LiteLLM).</li>
        <li>Building and iterating on Neuma, an AI mental health assistant — contributing to both backend API infrastructure and the LLM evaluation/optimization pipeline (AWS, Python).</li>
      </ul>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-header">
        <span class="cv-entry-org">HealthTech Startup</span>
        <span class="cv-entry-period">Oct 2025 – Jan 2026</span>
      </div>
      <div class="cv-entry-role"><span>Backend &amp; ML Infra Engineer</span><span class="cv-entry-location">Astana, Kazakhstan</span></div>
      <ul>
        <li>Architected a production backend for clinical workflow automation (roles, auth, orchestration, audit logging) across two clinics (NestJS, PostgreSQL).</li>
        <li>Delivered admin console workflows for follow-up task assignment and status transitions, cutting operator steps by 40% via structured state transitions and validation (Next.js, TypeScript).</li>
        <li>Implemented event-driven follow-ups/CRM automation for 500+ active patients (Redis, BullMQ).</li>
      </ul>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-header">
        <span class="cv-entry-org">LemonCloud Co. Ltd.</span>
        <span class="cv-entry-period">Jun 2025 – Sep 2025</span>
      </div>
      <div class="cv-entry-role"><span>Backend Engineer Intern, AI Team</span><span class="cv-entry-location">Seoul, South Korea</span></div>
      <ul>
        <li>Built a multi-repo RAG pipeline for code Q&amp;A: repo ingestion → embedding/indexing → retrieval → context assembly for LLM agents across large TypeScript codebases (OpenSearch).</li>
        <li>Reduced context size by 3× via AST-based chunking; offline A/B-tested on representative tasks with a pass/fail completion rubric to confirm comparable or better outcomes while improving latency/cost.</li>
        <li>Implemented REST APIs for agent operations (ingest/index, search, chat/run, feedback logging) and added 50+ Jest tests to harden reliability and regressions (TypeScript/Node, Jest).</li>
      </ul>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-header">
        <span class="cv-entry-org">ICU Company &amp; Korehalal Trip Ltd.</span>
        <span class="cv-entry-period">Dec 2024 – Mar 2025</span>
      </div>
      <div class="cv-entry-role"><span>Backend &amp; Data Engineer Intern</span><span class="cv-entry-location">Seoul, South Korea</span></div>
      <ul>
        <li>Built a serverless Laravel API for generating travel itineraries, and improved latency by 30% through batched geolocation lookups (AWS Lambda, API Gateway).</li>
        <li>Developed preprocessing pipeline with spatial indexing to reduce nearest-location lookup time by 40% for recommendation features (Python, FAISS).</li>
      </ul>
    </div>
  </div>

  <div class="cv-section">
    <h2>Leadership Experience</h2>
    <div class="cv-entry">
      <div class="cv-entry-header">
        <span class="cv-entry-org">KISA — KAIST International Students Association</span>
        <span class="cv-entry-period">Jan 2022 – Jan 2025</span>
      </div>
      <div class="cv-entry-role">Vice-President &amp; Head of Finance Division</div>
      <ul>
        <li>Successfully froze dormitory fee increases through data-driven reporting and lobbied for increased graduate student stipends.</li>
        <li>Managed budgeting and logistics for cultural events reaching 2,000+ students and oversaw profitable merchandise projects across two terms.</li>
        <li>Secured additional Korean language classes (Levels 3 &amp; 4) and successfully advocated for inclusive vegetarian options in school cafeterias.</li>
        <li>Spearheaded the launch of the new KISA website and developed digital course resource systems to streamline international student onboarding.</li>
      </ul>
    </div>
  </div>

  <div class="cv-section">
    <h2>Skills</h2>
    <div class="cv-skills">
      <div class="cv-skills-row">
        <span class="cv-skills-label">Languages</span>
        <div class="cv-skills-items">
          <span class="tag">Python</span>
          <span class="tag">TypeScript/JS</span>
          <span class="tag">Go</span>
          <span class="tag">SQL</span>
          <span class="tag">C++</span>
        </div>
      </div>
      <div class="cv-skills-row">
        <span class="cv-skills-label">Backend</span>
        <div class="cv-skills-items">
          <span class="tag">FastAPI</span>
          <span class="tag">Django</span>
          <span class="tag">NestJS</span>
          <span class="tag">Express</span>
          <span class="tag">PostgreSQL</span>
          <span class="tag">Redis</span>
          <span class="tag">MySQL</span>
        </div>
      </div>
      <div class="cv-skills-row">
        <span class="cv-skills-label">Cloud &amp; DevOps</span>
        <div class="cv-skills-items">
          <span class="tag">AWS</span>
          <span class="tag">Docker</span>
          <span class="tag">Git</span>
          <span class="tag">Terraform</span>
          <span class="tag">GitHub Actions</span>
        </div>
      </div>
      <div class="cv-skills-row">
        <span class="cv-skills-label">AI &amp; LLM</span>
        <div class="cv-skills-items">
          <span class="tag">PyTorch</span>
          <span class="tag">Transformers</span>
          <span class="tag">HuggingFace</span>
          <span class="tag">LangChain</span>
          <span class="tag">DSPy</span>
          <span class="tag">OpenAI API</span>
          <span class="tag">FAISS</span>
        </div>
      </div>
    </div>
  </div>

  <div class="cv-download-bar">
    <a class="btn-download" href="https://drive.google.com/file/d/1SEE_Z2ZcvZxfBT4y3z51fty-p2yr_1Hz/view?usp=drive_link" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" aria-hidden="true">
        <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
        <polyline points="7 10 12 15 17 10"/>
        <line x1="12" y1="15" x2="12" y2="3"/>
      </svg>
      CV (English)
    </a>
  </div>

</div>

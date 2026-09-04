---
layout: about
title: home
permalink: /
subtitle: "Empirical research on AI monitoring, evaluation, and model behavior."

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<section class="home-hero">
  <div>
    <p class="eyebrow">UDBHAV CHITRANSH</p>
    <h1>AI monitoring, evaluation, and model behavior.</h1>
    <p class="home-dek">I build small empirical studies to understand what models do, what their reasoning reveals, and which signals remain useful under intervention. I am especially interested in monitoring and control for increasingly autonomous agents.</p>
  </div>
  <aside class="profile-card">
    <img class="profile-photo" src="{{ '/assets/img/udbhav-profile.jpg' | relative_url }}" alt="Portrait of Udbhav">
    <p class="eyebrow">INDEPENDENT RESEARCH</p>
    <p><a href="{{ '/research/' | relative_url }}">Research</a><br><a href="mailto:udbhavchitransh@gmail.com">Email</a><br><a href="https://github.com/udsea">GitHub</a></p>
  </aside>
</section>

<section class="home-section">
  <header class="home-section-header">
    <p class="eyebrow">SELECTED WORK</p>
    <h2>Research artifacts</h2>
  </header>
  <div class="home-work-list">
    <article class="home-work">
      <p class="home-work-meta">CONTROL / 2026</p>
      <div>
        <h3><a href="{{ '/projects/actionlens/' | relative_url }}">ActionLens</a></h3>
        <p>Pre-execution control for shell and file actions, testing whether lightweight environment evidence can make oversight more useful than transcript review alone.</p>
      </div>
    </article>
    <article class="home-work">
      <p class="home-work-meta">EVALUATION / 2026</p>
      <div>
        <h3><a href="{{ '/projects/format-sensitivity-eval/' | relative_url }}">Format-Sensitivity Eval</a></h3>
        <p>A compact replication study of how forced-choice and free-form response formats can change observed safety behavior.</p>
      </div>
    </article>
    <article class="home-work">
      <p class="home-work-meta">MONITORING / 2026</p>
      <div>
        <h3><a href="{{ '/projects/sentinel/' | relative_url }}">Sentinel</a></h3>
        <p>An evaluation harness for coding agents that keeps task success, behavioral monitors, traces, and executable grading artifacts separate.</p>
      </div>
    </article>
    <article class="home-work">
      <p class="home-work-meta">CAUSAL REASONING / 2026</p>
      <div>
        <h3><a href="{{ '/projects/causalbench-llm/' | relative_url }}">CausalBench-LLM</a></h3>
        <p>A synthetic benchmark for testing causal reasoning with known intervention effects and deterministic evaluation.</p>
      </div>
    </article>
  </div>
  <p class="home-section-link"><a href="{{ '/research/' | relative_url }}">View the research index</a></p>
</section>

<section class="home-section home-about">
  <header class="home-section-header">
    <p class="eyebrow">ABOUT</p>
    <h2>Outside the lab</h2>
  </header>
  <p>When I am not doing research, I am usually reading, taking photographs, watching anime, or training a diffusion model I definitely did not need to train.</p>
</section>

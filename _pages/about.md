---
layout: about
title: home
permalink: /

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
    <h1>Udbhav Chitransh</h1>
    <p class="home-dek">I study how we can obtain reliable evidence about the behavior of capable AI systems, particularly when those systems can reason about and adapt to evaluation and oversight.</p>
  </div>
  <aside class="profile-card">
    <img class="profile-photo" src="{{ '/assets/img/udbhav-profile.jpg' | relative_url }}" alt="Portrait of Udbhav">
    <p><a href="{{ '/research/' | relative_url }}">Research</a><br><a href="https://github.com/udsea">GitHub</a><br><a href="mailto:udbhavchitransh@gmail.com">Email</a></p>
  </aside>
</section>

<section class="home-section">
  <header class="home-section-header">
    <h2>Research</h2>
  </header>
  <div class="home-work-list">
    <article class="home-work">
      <p class="home-work-meta">Research note / 2026</p>
      <div>
        <h3>Do Thoughts Cause Lies?</h3>
        <p>Causal interventions on reasoning and deceptive behavior.</p>
      </div>
    </article>
    <article class="home-work">
      <p class="home-work-meta">Research project / 2026</p>
      <div>
        <h3>Watcher&rsquo;s Echo</h3>
        <p>Can agents learn about their monitors from repeated feedback, or are they merely learning to adapt to feedback in general?</p>
      </div>
    </article>
    <article class="home-work">
      <p class="home-work-meta">Project / 2026</p>
      <div>
        <h3>HackTrace</h3>
        <p>Studying how reward-hacking strategies emerge, propagate, and can be attributed in agentic systems.</p>
      </div>
    </article>
  </div>
  <p class="home-section-link"><a href="{{ '/research/' | relative_url }}">View the research index</a></p>
</section>

<section class="home-section home-about">
  <header class="home-section-header">
    <h2>About</h2>
  </header>
  <p>When I am not doing research, I am usually reading, taking photographs, watching anime, or training a diffusion model I definitely did not need to train.</p>
</section>

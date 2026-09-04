---
layout: default
title: projects
permalink: /projects/
description: Earlier public projects on AI monitoring, evaluation, control, and causal reasoning.
nav: false
nav_order: 3
---

<section class="projects-index">
  <header class="projects-index-header">
    <p class="eyebrow">SELECTED WORK</p>
    <h1>{{ page.title }}</h1>
    <p>{{ page.description }}</p>
  </header>

{% assign sorted_projects = site.projects | sort: 'importance' %}

  <div class="projects-list">
    {% for project in sorted_projects %}
      <article class="project-entry">
        <div class="project-entry-meta">
          {% if project.category %}{{ project.category | upcase }}{% endif %}
          {% if project.year %}<br>{{ project.year }}{% endif %}
        </div>
        <div>
          <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
          {% if project.description %}<p>{{ project.description }}</p>{% endif %}
          {% if project.tags %}<p class="entry-tags">{{ project.tags | join: ' / ' }}</p>{% endif %}
        </div>
      </article>
    {% endfor %}
  </div>
</section>

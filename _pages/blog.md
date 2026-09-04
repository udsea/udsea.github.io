---
layout: default
permalink: /blog/
title: notes
nav: true
nav_order: 5
pagination:
  enabled: true
  collection: posts
  permalink: /page/:num/
  per_page: 5
  sort_field: date
  sort_reverse: true
  trail:
    before: 1
    after: 3
---

<section class="notes-index">
  <header class="notes-index-header">
    <p class="eyebrow">PUBLIC THINKING</p>
    <h1>{{ site.blog_name }}</h1>
    <p>{{ site.blog_description }}</p>
  </header>

{% if page.pagination.enabled %}
{% assign postlist = paginator.posts %}
{% else %}
{% assign postlist = site.posts %}
{% endif %}

  <div class="notes-list">
    {% for post in postlist %}
      {% assign read_time = post.content | number_of_words | divided_by: 180 | plus: 1 %}
      <article class="note-entry">
        <div class="note-entry-meta">{{ post.date | date: '%b %Y' }}<br>{{ read_time }} min read</div>
        <div>
          <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
          {% if post.description %}<p>{{ post.description }}</p>{% endif %}
          {% if post.tags %}<p class="entry-tags">{{ post.tags | join: ' / ' }}</p>{% endif %}
        </div>
      </article>
    {% endfor %}
  </div>

{% if page.pagination.enabled %}{% include pagination.liquid %}{% endif %}

</section>

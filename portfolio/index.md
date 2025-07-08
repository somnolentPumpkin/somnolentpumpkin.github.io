---
layout: page
title: Portfolio
permalink: /portfolio/
---

Here are some of my projects:

<section class="portfolio-list">
  {% for item in site.portfolio %}
  <article class="portfolio-item">
    <h3><a href="{{ item.url | relative_url }}">{{ item.title }}</a></h3>
    <p>{{ item.description }}</p>
  </article>
  {% endfor %}
</section>

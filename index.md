---
layout: page
title: Home
permalink: /
---

Welcome, I'm glad you could make it.

This site is where I share my technical and creative work. It's a space for sharing ideas, documenting projects, and staying connected to the things that matter to me.

Whether you're interested in essays, fiction, or what I've been building, I hope you'll find something worth exploring.

---

## ✍️ Writing

I publish essays, personal thoughts, and fiction. Some are thoughtful, some experimental, all written with care.

Each piece is part of an ongoing process of learning, creating, and understanding.

## 📰 Latest Post
<div class="latest-post">
  {% assign latest_post = site.posts | first %}
  {% if latest_post %}
    <h3><a href="{{ latest_post.url | relative_url }}">{{ latest_post.title }}</a></h3>
    <p class="post-date">{{ latest_post.date | date: "%B %-d, %Y" }}</p>
    <p>{{ latest_post.excerpt | strip_html | truncatewords: 40 }}</p>
    <p><a href="{{ latest_post.url | relative_url }}">Read more →</a></p>
  {% else %}
    <p>No blog posts yet.</p>
  {% endif %}
</div>

 👉 [See more blog posts](/blog/)

---



## 🛠️ Portfolio

This is a selection of my creative and professional projects. Some are polished tools or finished pieces, others are experiments in progress.

I work across mediums, and many projects include code, game development, or storytelling.

🎨 [View the portfolio](/portfolio/)

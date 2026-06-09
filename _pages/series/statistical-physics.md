---
title: "Series: Self-learning Statistical Biophysics"
permalink: /series/statistical-physics/
layout: page
---

<ul>
{% assign series_posts = site.posts | where: "series", "Statistical Physics" | sort: "series_index" %}
{% for post in series_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%Y-%m-%d" }}</li>
{% endfor %}
</ul>
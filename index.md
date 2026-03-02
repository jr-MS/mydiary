---
layout: default
title: Home
---

# Daily Notes

A daily book/art diary (CN/EN). New entry every day at 23:00 (Beijing time).

## Latest

<ul>
{% for post in site.posts limit:10 %}
  <li><a href="{{ post.url | relative_url }}">{{ post.date | date: "%Y-%m-%d" }} — {{ post.title }}</a></li>
{% endfor %}
</ul>

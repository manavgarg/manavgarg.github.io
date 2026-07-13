---
layout: default
title: Writing
permalink: /writing/
---

# Writing

Notes on distributed systems, AI infrastructure, and whatever else survives a
second draft.

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <span class="date">{{ post.date | date: "%b %-d, %Y" }}</span>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>

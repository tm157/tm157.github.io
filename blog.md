---
layout: default
title: Writings
permalink: /writings/
---

# Writings

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <span class="post-date">{{ post.date | date: "%b %Y" }}</span>
    <a href="{{ post.url | relative_url }}" class="post-title-link">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

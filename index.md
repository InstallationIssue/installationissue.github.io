---
title: Welcome
layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

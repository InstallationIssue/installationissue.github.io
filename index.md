---
title: Welcome
layout: default
---

## Welcome to {{ site.title }} by {{ site.author }}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

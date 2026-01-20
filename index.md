---
title: Welcome
layout: default
---
<h1>Welcome to {{ site.title }}</h1>
<div class="index">
  {% for post in site.posts %}
    {% include excerpt.html url=post.url title=post.title excerpt=post.excerpt %}
  {% endfor %}
<div>

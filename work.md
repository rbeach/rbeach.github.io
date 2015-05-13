---
layout: default
title: Portfolio
permalink: /work/
---

<div class="posts">
  {% for post in site.projects %}
    <article class="post">
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="color">{{ post.color }}</div>
    </article>
  {% endfor %}
</div>
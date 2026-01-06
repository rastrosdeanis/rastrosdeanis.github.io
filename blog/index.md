---
layout: blank
title: Blog
---

# Blog

Aqui ficam os textos, rastros e fragmentos.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>


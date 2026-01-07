---
layout: blank
title: Blog
---

<div class="reading-field">

  <h1 class="site-title">
    Blog
  </h1>

  <p class="free-text">
    Aqui ficam os textos, rastros e fragmentos.
  </p>

  <ul class="post-list">
    {% for post in site.posts %}
      <li class="post-item">
        <a href="{{ post.url | relative_url }}">
          {{ post.title }}
        </a>
      </li>
    {% endfor %}
  </ul>

</div>

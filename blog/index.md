---
layout: default
title: Blog
---

# Blog

Aqui ficam os textos, rastros e fragmentos.

---

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})**  
  <span style="font-size: 0.8rem; color: #aaa;">
    {{ post.date | date: "%d/%m/%Y" }}
  </span>
{% endfor %}

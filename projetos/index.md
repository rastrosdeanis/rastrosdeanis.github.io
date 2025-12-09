---
layout: default
title: Projetos
---

# Projetos

Uma coleção de trabalhos, experimentos e rastros visuais.

---

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px;">

{% for item in site.static_files %}
  {% if item.path contains '/projetos/' and item.extname != '.md' %}
  <div>
    <img src="{{ item.path }}" style="width: 100%; border: 1px solid #333;">
  </div>
  {% endif %}
{% endfor %}

</div>

---
layout: default
title: Home
---

# Projects

<ul>
  {% for p in site.projects %}
    <li>
      <a href="{{ p.url }}">{{ p.title }}</a>
      {% if p.description %} — {{ p.description }}{% endif %}
    </li>
  {% endfor %}
</ul>

---
layout: page
title: Link
permalink: /link/
---

<nav class="externallink">
  <ul class="externallink-list">
  {% for el in site.data.externallink %}
    <li class="externallink-item">
      <a href="{{ el.url }}">{{ el.title | escape }}</a>
    </li>
  {% endfor %}
  </ul>
</nav>


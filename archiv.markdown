---
layout: default
title: Archiv
---

<h1>Kategorien</h1>
<ul>
  {% for category in site.categories %}
    <li><a href="/kategorie/{{ category[0] | slugify }}/">{{ category[0] }}</a> ({{ category[1].size }})</li>
  {% endfor %}
</ul>


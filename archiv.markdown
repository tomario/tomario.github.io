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
<p>&nbsp;</p>
<h1>Stichwort</h1>
<ul>
  {% for tag in site.tags %}
    <li><a href="/stichwort/{{ tag[0] | slugify }}/">{{ tag[0] }}</a> ({{ tag[1].size }})</li>
  {% endfor %}
</ul>

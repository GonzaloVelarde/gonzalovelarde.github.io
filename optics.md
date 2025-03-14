---
layout: default
title: "Optics"
category: optics
permalink: /optics/
---
<h1>Posts sobre Óptica</h1>
<ul>
  {% for post in site.categories[page.category] %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small></li>
  {% endfor %}
</ul>

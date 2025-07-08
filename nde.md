---
layout: page
title: "NDE"
permalink: /nde/
---

<h1>Posts in Category: NDE</h1>

<ul>
  {% for post in site.categories.nde %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

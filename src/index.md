---
title: Home
layout: base.njk
tags: navItem
---

This is the home page. 
<ul>
  {%- for post in collections.post %}
  <li>
  <a href="{{ post.url }}">
  {{ post.data.title }}
  </a>
  </li>
  {%- endfor %}
</ul>
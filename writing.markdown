---
layout: default
title: writing
permalink: /writing/
---
### WRITING

<ul>
  {% for post in site.posts %}
    <li>
      <p><a href="{{ post.url }}">{{ post.title }}</a></p>
    </li>
  {% endfor %}
</ul>

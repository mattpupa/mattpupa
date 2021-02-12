---
layout: default
title: writing
permalink: /writing/
---
<br>
### ABOUT ME

<ul>
  {% for post in site.posts %}
    <li>
      <p><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: '%B %d, %Y' }}</p>
    </li>
  {% endfor %}
</ul>

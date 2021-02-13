---
layout: default
title: writing
permalink: /writing/
---
<br>
### WRITING

<ul>
  {% for post in posts %}
    <li>
      <p><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: '%B %d, %Y' }}</p>
    </li>
  {% endfor %}
</ul>

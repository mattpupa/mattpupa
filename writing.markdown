---
layout: default
title: writing
permalink: /writing/
---
<br>
### WRITING

<ul>
  {% for post in site.posts %}
    <li>
      <p><a href="mattpupa{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: '%B %d, %Y' }}</p>
    </li>
  {% endfor %}
</ul>

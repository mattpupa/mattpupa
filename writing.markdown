---
layout: default
title: writing
permalink: /writing/
---
<br>
<br>
<h3>WRITING</h3>

<ul>
  {% for post in site.posts %}
    <li>
      <p><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: '%B %d, %Y' }}</p>
    </li>
  {% endfor %}
</ul>

---
layout: default
title: Journal
---
<h1>Journal</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%b %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>


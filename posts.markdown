---
layout: default
title: Posts
permalink: /posts/
---
# Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%B %-d %Y" }})
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
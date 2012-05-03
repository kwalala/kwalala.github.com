---
layout: page
title: A blog
tagline: 
---
{% include JB/setup %}

He is a proper geek.  I am less so.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


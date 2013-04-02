---
layout: page
title: ...thoughts on data analysis
---
{% include JB/setup %}

My attempt to build a Jekyll's blog...

Posts list

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
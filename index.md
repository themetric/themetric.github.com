---
layout: page
title: Home
tagline: the metric gear always turns
order: 1
---
{% include JB/setup %}

## Posts 
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>





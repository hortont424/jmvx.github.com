---
layout: page
title: Julia
---
{% include JB/setup %}

This is my personal page.

<ul class="posts">
  {% for post in site.tags.personal %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




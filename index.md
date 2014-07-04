---
layout: page
title: "CloudCoder Blog"
---

# About

This is a blog about the <a href="http://cloudcoder.org">CloudCoder</a> open source programming exercise system.  The <a href="http://cloudcoder.org/people.html">weirdos</a> responsible for CloudCoder write stuff in this blog to talk about what is going on with CloudCoder.

# Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

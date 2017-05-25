---
layout: individual
title: Blog
seotitle: JoyofPL Blog | Joy of Professional Learning
permalink: /blog/
img: blog-hero
---

{% for post in site.posts %}
<div class="post-area">
  <a href="{{ post.url | prepend: site.baseurl }}" class="bold">{{ post.title }}</a>
  <p class="post-date">{{ post.date | date_to_long_string }}</p>
  <p>
    {{ post.content | strip_html | truncatewords: 50 }}
  </p>
</div>
{% endfor %}

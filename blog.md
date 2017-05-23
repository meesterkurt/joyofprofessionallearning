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
  <p>We are so excited to be hosting our first @joyofpl workshop on creating professional learning for Back to School. We have invited coaches, principals, curriculum coordinators, professional development coordinators and other school leaders to join us to first experience professional learning  then design a professional learning plan aligned to district wide goals. We have used this personalized planning design for back to school professional learning with school leaders around the world. The plan extends to year long learning events through thoughtful consideration of the whole school mission. Registration is open: <a href="https://conference.iste.org/2017/program/search/detail_session.php?id=108675817">Recipes for Designing Professional Learning </a>
  <p> We are also hosting the iTools Academy workshop and a Learning with Apple Distinguished Educators: Enhancing Creativity and Content Creation playground. <a href="https://conference.iste.org/2017/program/search/detail_session.php?id=108635050">ISTE Workshops </a>
   <p> Meet our team and hear more about how we use Apple Technology to create content and enhance creativity. Learn about our consulting services for professional learning.
    {{ post.content | strip_html | truncatewords: 50 }}
  <p>
<div>
{% endfor %}

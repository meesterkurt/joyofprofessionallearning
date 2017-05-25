---
layout: individual
title: Blog
seotitle: JoyofPL Blog | Joy of Professional Learning
permalink: /blog/
img: blog-hero
---

{% for post in site.posts %}
<div class="post-area">
  <a href="{{ post.url | prepend: site.baseurl }}" class="bold">{{ post.ISTE2017 }}</a>
  <p class="post-date">{{ post.May | date_to_long_string }}</p>
  <p>We are so excited to be hosting our first @joyofpl workshop on creating professional learning for Back to School. We have invited coaches, principals, curriculum coordinators, professional development coordinators and other school leaders to join us to first experience professional learning  then design a professional learning plan aligned to district wide goals. We have used this personalized planning design for back to school professional learning with school leaders around the world. The plan extends to year long learning events through thoughtful consideration of the whole school mission. 
      <div>
    <div>
  <div>
<div>
<p>Registration is open: <a href="https://conference.iste.org/2017/program/search/detail_session.php?id=108675817">Recipes for Designing Professional Learning</a>
 <div>
    <div>
  <div>
<div>
  <p> We are also hosting the iTools Academy workshop and a Learning with Apple Distinguished Educators: Enhancing Creativity and Content Creation playground. <a href="https://conference.iste.org/2017/program/search/detail_presenter.php?id=108114820">ISTE Workshops</a>  Meet our team and hear more about how we use Apple Technology to create content and enhance creativity.
    {{ post.content | strip_html | truncatewords: 50 }}
  <p>
      <div>
    <div>
  <div>
<div>
{% endfor %}
      <div>
    <div>
  <div>
<div>
{% for post in site.posts %}
<div class="post-area">
  <a href="{{ post.url | prepend: site.baseurl }}" class="bold">{{ post.New Book for Leaders }}</a>
  <p class="post-date">{{ post.June | date_to_long_string }}</p>
  <p>Our new book for leaders was released this week.
Our newest edition to the Joy of Professional Learning Book Series is in the store! This book challenged our team to think about leaders as learners and how our experiences as coaches can inspire leadership teams to embrace new ways to enhance workflow and save time. How we can include our leaders are learners too.
Thank you Camilla Gagliolo Cheryl Davis Johan Andersson Marjan Van de Vrie Jason Kathman Katie Willis Morrow and Kurt Klynen for your hard work, vision, and practical ideas.
As Seth Godin wrote this week, 
 "The tension we face any time we're about to cross a threshold. The tension of this might work vs. this might not work... Tension is the hallmark of a great educational experience." 
"...adult learners on their way to levelling up actively seek out this tension, because it works. It pushes us over the chasm to the other side."
We have arrived.
      <div>
    <div>
  <div>
<div>
<p>Grab a copy of our new book for leaders: <a href="https://itunes.apple.com/us/book/the-joy-of-professional-learning-strategies-for-leaders/id1235488390?mt=11">Recipes for Designing Professional Learning</a>
 <div>
    {{ post.content | strip_html | truncatewords: 50 }}
      <div>
    <div>
  <div>
<div>
{% endfor %}

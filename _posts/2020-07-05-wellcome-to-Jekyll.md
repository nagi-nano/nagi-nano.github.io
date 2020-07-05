---
layout: post
title:  "Welcome to Jekyll!"
food: Pizza
---

# Welcome

**Hello world**, this is my first Jekyll blog post.

I hope you like it!

<h1>{{ page.food }}</h1>

... which is shown in the screenshot below:
![My helpful screenshot](/assets/puppy-5124948_1920.jpg)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

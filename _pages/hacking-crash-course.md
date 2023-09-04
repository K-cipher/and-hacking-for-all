---
layout: posts
title: Hacking Crush Course
permalink: /hacking-crash-course/
---


{% for post in site.posts %}
  {% if post.categories contains 'hacking-crash-course' %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  {% endif %}
{% endfor %}

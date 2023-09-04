---
layout: single
title: Hacking Crush Course
permalink: /hacking-crash-course/
---
# Hello Friend


{% for post in site.posts %}
  {% if post.categories contains 'hacking-crush-course' %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  {% endif %}
{% endfor %}

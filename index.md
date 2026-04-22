---
layout: default
title: Home
---


# Welcome to this page!

My name is Kayvon, and I will be posting some writing entries onto this page.

# Entries

{% for post in site.posts reversed %}
  <li>
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
  <a href="{{ post.url }}">{{ post.title }}</a><br>
  
</li>
{% endfor %}




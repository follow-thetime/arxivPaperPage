---
layout: page
title: navigator
---

{% for post in site.posts %}
  <li><a href="{{post.url}}">{{post.title}}
{%endfor%}

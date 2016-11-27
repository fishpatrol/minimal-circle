---
title: "Writing"
layout: "archive"
permalink: "/writing/"
---
This is the index page for Writing posts.


  {% for post in site.posts %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><em>{{ post.excerpt }}</em></p>
  {% endfor %}

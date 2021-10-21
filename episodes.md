---
title: Episodes
layout: default
---

# {{ title }}

{% include navigation.html %}

<ul>
  {% for post in site.posts %}
    <li><a href="{{ site.url }}/bardstest{{ post.url }}">{{ post.title }}, {{ post.date }}</a></li>
  {% endfor %}
</ul>

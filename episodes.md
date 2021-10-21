---
title: Episodes
layout: default
---

{% include navigation.html %}

# Campaign Log

## Episodes

<ul>
  {% for post in site.posts %}
    <li><a href="{{ site.url }}/oopsallbards{{ post.url }}">{{ post.title }}, {{ post.date | date: "%b %-d, %Y"}}</a></li>
  {% endfor %}
</ul>

---
title: Home Page
---

# Welcome

{% include navigation.html %}

## Players

<ul>
  {% for player in site.players %}
    <li><a href="{{ site.url }}/bardstest{{ player.url }}">{{ player.name }}</a></li>
  {% endfor %}
</ul>

## Episodes

Read the [campaign log](_pages/blog.html)

## Other Campaign Info

- [NPCs](google.com)
- [Locations](google.com)

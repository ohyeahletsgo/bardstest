---
title: Home Page
---

# Welcome

Home page

## Players

<ul>
  {% for player in site.players %}
    <li><a href="{{ site.url }}/bardstest{{ player.url }}">{{ player.name }}</a></li>
  {% endfor %}
</ul>

## Episodes

Read the [campaign log](episodes.md)

## Other Campaign Info

- [NPCs](google.com)
- [Locations](google.com)

---
title: Home Page
---

{% include navigation.html %}

## Players

<ul>
  {% for player in site.players %}
    <li><a href="{{ site.url }}/bardstest{{ player.url }}">{{ player.name }}</a></li>
  {% endfor %}
</ul>

- [Calista](_players/calista.md)
- [Davos](_players/davos.md)
- [Shim](_players/shim.md)
- [Terrence](_players/terrence.md)

## Episodes

Read the [campaign log](_pages/blog.html)

## Other Campaign Info

- [NPCs](google.com)
- [Locations](google.com)

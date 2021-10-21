---
title: Home Page
---

# Oops! All Bards!

The only DnD campaign, overflowing with bards and daddy issues.

## Players

<ul>
  {% for player in site.players %}
    <li><a href="{{ site.url }}{{ player.url }}">{{ player.name }}</a></li>
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

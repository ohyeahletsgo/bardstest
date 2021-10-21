---
title: Home Page
---

# Welcome

Home page of the _**Oops! All Bards**_ DnD campaign

## Players

<ul>
  {% for player in site.players %}
    <li><a href="{{ site.url }}/oopsallbards{{ player.url }}">{{ player.name }}</a></li>
  {% endfor %}
</ul>

## Episodes

Read the [campaign log](episodes.md)

## Other Campaign Info

- [NPCs](npcs.md)
- [Locations](locations.md)

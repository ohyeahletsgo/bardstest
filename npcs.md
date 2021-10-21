---
layout: default
---

# NPCs

{% include navigation.html %}

## List of NPCs

<ul>
  {% for npc in site.npcs %}
    <li><a href="{{ site.url }}/oopsallbards{{ npc.url }}">{{ npc.name }}</a></li>
  {% endfor %}
</ul>

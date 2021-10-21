---
layout: default
---

# Locations

{% include navigation.html %}

## List of Locations

<ul>
  {% for location in site.locations %}
    <li><a href="{{ site.url }}/bardstest{{ location.url }}">{{ location.name }}</a></li>
  {% endfor %}
</ul>

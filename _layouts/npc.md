---
layout: default
---

{% include navigation.html %}
<ul>
  <li><a href="/bardstest/npcs.html" {% if page.url == "/bardstest/npcs.html" %}class="active"{% endif %}>Back to NPCs</a></li>
</ul>

<h1>{{ page.name }}</h1>

<p>{{ page.location }}</p>

{{ content }}

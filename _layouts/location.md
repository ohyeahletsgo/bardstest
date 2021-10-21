---
layout: default
---

{% include navigation.html %}
<ul>
  <li><a href="/bardstest/locations.html" {% if page.url == "/bardstest/locations.html" %}class="active"{% endif %}>Back to Locations</a></li>
</ul>

<h1>{{ page.name }}</h1>

<p>{{ page.localization }}</p>

{{ content }}

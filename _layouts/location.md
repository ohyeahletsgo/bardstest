---
layout: default
---

{% include navigation.html %}
<ul>
  <li><a href="/oopsallbards/locations.html" {% if page.url == "/oopsallbards/locations.html" %}class="active"{% endif %}>Back to Locations</a></li>
</ul>

<h1>{{ page.name }}</h1>

<p>{{ page.localization }}</p>

{{ content }}

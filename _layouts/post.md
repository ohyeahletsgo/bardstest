---
layout: default
---

{% include navigation.html %}

<ul>
  <li><a href="/bardstest/episodes.html" {% if page.url == "/bardstest/episodes.html" %}class="active"{% endif %}>Back to Campaign Log</a></li>
</ul>

<h1>{{ page.title }}</h1>  

<p> > {{ page.date | date: "%b %-d, %Y"}}</P>

{{ content }}  

{% include navlinks.html %}

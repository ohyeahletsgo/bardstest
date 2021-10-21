---
layout: default
---

{% include navigation.html %}

<ul>
  <li><a href="/oopsallbards/episodes.html" {% if page.url == "/oopsallbards/episodes.html" %}class="active"{% endif %}>Back to Campaign Log</a></li>
</ul>

<h1>{{ page.title }}</h1>  

<p> > {{ page.date | date: "%b %-d, %Y"}}</P>

{{ content }}  

{% include navlinks.html %}

---
layout: default
---

{% include navigation.html %}

<h1>{{ page.title }}</h1>  

<p> > {{ page.date | date: "%b %-d, %Y"}}</P>

{{ content }}  

{% include navlinks.html %}

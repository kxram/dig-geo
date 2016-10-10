---
layout: page
title: Veranstaltungen
order: 1
---

{% for event in site.posts %}
<h2>{{ event.title }}</h2>
<em>{{ event.zeit }}, {{ event.ort }}</em>
{{ event.excerpt }}
<a href="{{ site.baseurl }}{{ event.url }}">Weiterlesen >></a>
{% endfor %}

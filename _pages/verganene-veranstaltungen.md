---
title: Vergangene Veranstaltungen
permalink: vergangene-veranstaltungen
order: 1
layout: page
show_in_sidebar: true
---


{% assign events = site.posts | where: "category", "workshops" %}
{% for event in events %}
<h2>{{ event.title }}</h2>
<em>{{ event.zeit }} — {{ event.ort }}</em>
{{ event.excerpt }}
<a href="{{ site.baseurl }}{{ event.url }}">Weiterlesen >></a>
{% if forloop.last == false %} <hr> {% endif %}
{% endfor %}

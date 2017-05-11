# Ankündigungen

{% include ankuendigungen.md %}

---

# Über andere

Wir sind ein Netzwerk von akademisch arbeitenden Geograph\*innen, Geowissenschaftler\*innen, Kartograph\*innen und Medienwissenschaftler\*innen, derzeit aus 13 Universitäten im deutschsprachigen Raum.

[Mehr lesen...]({{ site.baseurl }}/unsere-forschung)

---

# Berichte

{% assign berichte = (site.posts | where: "category", "workshops") %}
  {% for node in berichte %}
[{{ node.title }}]({{ site.baseurl }}{{ node.url }})
  {% endfor %}


{% assign announcements = site.posts | where: "category", "news" %}
{% for announcement in announcements %}
## {{ announcement.title }}

*Geschrieben am {% assign m = announcement.date | date: "%-m" %} {{ announcement.date | date: "%-d" }}. {% case m %}
  {% when '1' %}Januar
  {% when '2' %}Februar
  {% when '3' %}M&auml;rz
  {% when '4' %}April
  {% when '5' %}Mai
  {% when '6' %}Juni
  {% when '7' %}Juli
  {% when '8' %}August
  {% when '9' %}September
  {% when '10' %}Oktober
  {% when '11' %}November
  {% when '12' %}Dezember
{% endcase %} {{ announcement.date | date: "%Y" }}*

{{ announcement.content }}
{% if forloop.last == false %} <hr> {% endif %}
{% endfor %}

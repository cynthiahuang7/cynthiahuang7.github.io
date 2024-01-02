---
layout: base
title: Notes
permalink: /notes/
---

{% for note in site.notes %}
  - [{{ note.title }}]({{ note.url }})
  {% if note.excerpt %}
    {{ note.excerpt }}
  {% endif %}
{% endfor %}
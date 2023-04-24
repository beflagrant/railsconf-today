---
layout: page
title: Events
---

<ul>
  {% for event in collections.events.resources %}
    <li>
      <a href="{{ event.relative_url }}">{{ event.data.title }}</a>
    </li>
  {% endfor %}
</ul>
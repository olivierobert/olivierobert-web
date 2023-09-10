---
layout: page
title: Notes
---

<ul>
  {% for note in collections.posts.notes %}
    <li>
      <a href="{{ note.relative_url }}">{{ note.data.title }}</a>
    </li>
  {% endfor %}
</ul>

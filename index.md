---
layout: nav
title: Problems
---

{% for folder in site.data.problems %}

### {{ folder.name }}

<ul>
  {% for problem in folder.problems %}
    <li>
      <a href="./problems/{{folder.url}}/{{ problem.url }}">{{ problem.name }}</a>
    </li>
  {% endfor %}
</ul>

{% endfor %}

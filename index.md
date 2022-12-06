---
layout: default
title: Graphs
---

{% for chapter in site.data.chapters %}
### {{ chapter.chapter }} &nbsp; &nbsp;  {{ chapter.name }}
{% assign filtered_graphs = site.graphs | where: "chapter", chapter.chapter %}
<ul>
  {% for graph in filtered_graphs %}
    <li>
      <a href="./{{ graph.url }}">{{ graph.name }}</a>
    </li>
  {% endfor %}
</ul>
{% endfor %}

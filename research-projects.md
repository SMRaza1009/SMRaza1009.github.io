---
layout: default
title: Research Projects
navbar_title: Research Projects
container_class: container-xl
---

# Research Projects

{% assign projects = site.showcase | where: "show", true | sort: "date" | reverse %}

{% for item in projects %}
<div class="card mt-3">
  <div class="card-body">
    <h4>{{ item.title }}</h4>
    {{ item.content | markdownify }}
  </div>
</div>
{% endfor %}

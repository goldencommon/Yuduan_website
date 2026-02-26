---
layout: default
title: Research
---

# Research

{% for item in site.data.research %}
<div class="entry">
  <h3>{{ item.title }}</h3>
  <p class="meta">{{ item.status }} | {{ item.collaborators }}</p>
  <ul>
    {% for d in item.details %}
      <li>{{ d }}</li>
    {% endfor %}
  </ul>
</div>
{% endfor %}

## Work in progress

I am currently developing projects in development and labor economics with an empirical focus.

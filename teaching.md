---
layout: default
title: Teaching
---

# Teaching

{% for item in site.data.teaching %}
<div class="entry">
  <h3>{{ item.role }} - {{ item.school }}</h3>
  <p class="meta">{{ item.location }} | {{ item.dates }}</p>
  <p><strong>Courses:</strong></p>
  <ul>
    {% for c in item.courses %}
      <li>{{ c }}</li>
    {% endfor %}
  </ul>
</div>
{% endfor %}

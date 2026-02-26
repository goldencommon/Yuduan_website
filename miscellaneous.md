---
layout: default
title: Miscellaneous
---

# Miscellaneous

{% for block in site.data.misc %}
<div class="entry">
  <h3>{{ block.title }}</h3>
  <ul>
    {% for item in block.items %}
      <li>{{ item }}</li>
    {% endfor %}
  </ul>
</div>
{% endfor %}

## Notes

This page can include presentations, conference participation, scholarships, or other updates.

---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">
{% assign sorted_cats = site.categories.moosefood | sort: 'title' %}
{% for post in sorted_cats %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

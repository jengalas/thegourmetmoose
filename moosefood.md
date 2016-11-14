---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">
{% assign sorted_posts = site.categories.moosefood | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

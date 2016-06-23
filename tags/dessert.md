---
layout: archive
permalink: /tags/dessert
---

# Course: Dessert

<div class="tiles">
{% assign sorted_posts = site.tags.dessert | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

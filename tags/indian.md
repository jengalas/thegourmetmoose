---
layout: archive
permalink: /tags/indian
---

# Cuisine: Indian

<div class="tiles">
{% assign sorted_posts = site.tags.Indian | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

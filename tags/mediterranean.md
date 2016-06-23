---
layout: archive
permalink: /tags/mediterranean
---

# Cuisine: Mediterranean

<div class="tiles">
{% assign sorted_posts = site.tags.Mediterranean | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

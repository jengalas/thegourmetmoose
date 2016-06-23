---
layout: archive
permalink: /tags/eastern-european
---

# Cuisine: Eastern European

<div class="tiles">
{% assign sorted_posts = site.tags.Eastern-European | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

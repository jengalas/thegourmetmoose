---
layout: archive
permalink: /tags/south-american
---

# Cuisine: South American

<div class="tiles">
{% assign sorted_posts = site.tags.South-American | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

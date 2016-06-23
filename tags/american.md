---
layout: archive
permalink: /tags/american
---

# Cuisine: American

<div class="tiles">
{% assign sorted_posts = site.tags.American | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

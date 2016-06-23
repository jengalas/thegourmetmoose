---
layout: archive
permalink: /tags/british
---

# Cuisine: British

<div class="tiles">
{% assign sorted_posts = site.tags.British | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

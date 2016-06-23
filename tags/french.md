---
layout: archive
permalink: /tags/french
---

# Cuisine: French

<div class="tiles">
{% assign sorted_posts = site.tags.French | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

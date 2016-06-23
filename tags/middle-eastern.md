---
layout: archive
permalink: /tags/middle-eastern
---

# Cuisine: Middle Eastern

<div class="tiles">
{% assign sorted_posts = site.tags.Middle-Eastern | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

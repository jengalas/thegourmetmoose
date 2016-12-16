---
layout: archive
permalink: /tags/german
---

# Cuisine: German

<div class="tiles">
{% assign sorted_posts = site.tags.German | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

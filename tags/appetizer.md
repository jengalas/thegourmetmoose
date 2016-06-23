---
layout: archive
permalink: /tags/appetizer
---

# Course: Appetizer

<div class="tiles">
{% assign sorted_posts = site.tags.appetizer | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

---
layout: archive
permalink: /tags/salad
---

# Course: Salad

<div class="tiles">
{% assign sorted_posts = site.tags.salad | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

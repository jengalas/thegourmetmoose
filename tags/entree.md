---
layout: archive
permalink: /tags/entree
---

# Course: Entrée

<div class="tiles">
{% assign sorted_posts = site.tags.entree | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

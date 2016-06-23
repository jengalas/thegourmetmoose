---
layout: archive
permalink: /recipes-to-try/
---

# Recipes we'd like to try

<div class="tiles">
{% assign sorted_posts = site.categories.recipes-to-try | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

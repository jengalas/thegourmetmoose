---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">
{% capture page_title %}{{ page.title | downcase }}{% endcapture %}
{% assign sorted_posts = page_title | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

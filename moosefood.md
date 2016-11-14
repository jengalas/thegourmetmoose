---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">
{% for post in site.posts %}
{% capture page_title %}{{ page.title | downcase }}{% endcapture %}
{% endfor %}
{% assign sorted_posts = page_title | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

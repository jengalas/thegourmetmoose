---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">
{% capture lowercase_moosefood %}{% for page in site.categories.moosefood %}{{ page.title | downcase }}{% endfor %}{% endcapture %}
{% assign sorted_posts = lowercase_moosefood | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

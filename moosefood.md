---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">
{% capture lowercase_moosefood %}{% for post in site.categories.moosefood %}{{ post | downcase }}#{{ post }}{% endfor %}{% endcapture %}
{% assign sorted_posts = lowercase_moosefood | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

---
layout: archive
permalink: /recipes-to-try/
---

# Recipes we'd like to try

<div class="tiles">
{% for post in site.categories.recipes-to-try %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

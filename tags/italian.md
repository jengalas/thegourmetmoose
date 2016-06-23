---
layout: archive
permalink: /tags/italian
---

# Cuisine: Italian

<div class="tiles">
{% assign sorted_posts = site.tags.Italian | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

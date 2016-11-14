---
layout: archive
permalink: /moosefood/
---

# Recipes we like

<div class="tiles">

{% for post in site.categories.moosefood %}
{% capture page_title %}{{ post.title }}{% endcapture %}
{% endfor %}
{% assign sorted_posts = page_title | sort: 'title' %}
{% for post in sorted_posts %}
{{ page_title }}
  {% include archive-single.html type="grid" %}
}
}
{% endfor %}
</div><!-- /.tiles -->

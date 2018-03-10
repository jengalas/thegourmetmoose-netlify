---
layout: archive
permalink: /tags/irish
---

# Cuisine: Irish

<div class="tiles">
{% assign sorted_posts = site.tags.Irish | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

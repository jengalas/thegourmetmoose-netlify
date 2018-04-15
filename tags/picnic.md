---
layout: archive
permalink: /tags/picnic
---

# Cuisine: Picnic

<div class="tiles">
{% assign sorted_posts = site.tags.picnic | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

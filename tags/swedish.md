---
layout: archive
permalink: /tags/swedish
---

# Cuisine: Swedish

<div class="tiles">
{% assign sorted_posts = site.tags.Swedish | sort: 'title' %}
{% for post in sorted_posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div><!-- /.tiles -->

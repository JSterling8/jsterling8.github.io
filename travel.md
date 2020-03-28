---
layout: archive
title: Travel
permalink: /travel
---

<div class="tiles">
{% for post in site.posts %}
	{% if post.categories contains 'travel' %}
	  {% include post-grid.html %}
  {% endif %}
{% endfor %}
</div><!-- /.tiles -->

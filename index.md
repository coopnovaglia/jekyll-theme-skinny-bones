---
layout: home
permalink: /
image:
  feature: banner.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->


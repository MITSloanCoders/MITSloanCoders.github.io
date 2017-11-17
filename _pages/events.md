---
layout: page
permalink: /events/
title: "Latest Events"
---

<div class="tiles">
{% for post in site.categories.events %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

---
layout: page
permalink: /commercial/
title: commercial
description: commercial work
---

<ul class="post-list">
{% for commercial in site.commercial reversed %}
    <li>
      <u><h3><a class="article-title" href="{{ commercial.url | prepend: site.baseurl }}">{{ commercial.title }}</a></h3></u>
      <h4>{{ commercial.description }}</h4>
      <h4>Client: {{ commercial.client }}</h4>
    </li>
{% endfor %}
</ul>
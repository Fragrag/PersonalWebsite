---
layout: page
permalink: /articles/
title: articles
description: 
---

<ul class="post-list">
{% for article in site.articles reversed %}
    <li>
      <u><h3><a class="article-title" href="{{ article.url | prepend: site.baseurl }}">{{ article.title }}</a></h3></u>
      <h4>{{ article.description }}</h4>
      <h5>{{ article.tech }}</h5>
    </li>
{% endfor %}
</ul>
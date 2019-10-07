---
layout: page
permalink: /articles/
title: articles
description: Showcase your writing, short stories, or poems. Replace this text with your description.
---

<ul class="post-list">
{% for article in site.articles reversed %}
    <li>
        <h2><a class="article-title" href="{{ article.url | prepend: site.baseurl }}">{{ article.title }}</a></h2>
        <p class="post-meta">{{ article.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
---
title: "News"
layout: textlay
excerpt: "McGraw Lab at Northwestern University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p><em>{{ article.date }}</em> {{ article.headline | markdownify | strip}}</p>
{% endfor %}

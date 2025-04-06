---
title: "News"
layout: textlay
excerpt: "McGraw Lab at Northwestern University."
sitemap: false
permalink: /allnews.html
---

# News
<!--  News page with all news articles-->
<!-- [ ] working -->

{% for article in site.data.news %}
_{{ article.date }}_. &nbsp; {{ article.headline | strip}}
{% endfor %}

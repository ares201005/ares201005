---
title: "News"
layout: textlay
excerpt: "Zhang Lab at LANL."
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}
</div>

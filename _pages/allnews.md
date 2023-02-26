---
title: "News"
layout: textlay
excerpt: "Applied Computer Group NCA-UFMA"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

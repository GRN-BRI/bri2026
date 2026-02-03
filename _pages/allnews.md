---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<div style="margin-bottom: 30px; border-bottom: 1px solid #eee; padding-bottom: 20px;">
<h4 style="margin-bottom: 10px; color: #333;">{{ article.date }}</h4>
<div style="font-style: normal;">
{{ article.headline }}
</div>
</div>
{% endfor %}

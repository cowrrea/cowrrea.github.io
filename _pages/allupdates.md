---
title: "Updates"
layout: gridlay
sitemap: false
permalink: /allupdates.html
---

## Updates

<div class="section-card" markdown="0">
<div class="updates-timeline">
{% for article in site.data.updates %}
<div class="updates-item">
<span class="updates-date">{{ article.date }}</span>
<span class="updates-headline">{{ article.headline }}</span>
</div>
{% endfor %}
</div>
</div>

---
title: "Output"
layout: gridlay
sitemap: false
permalink: /output/
---

## Output

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">

<h3>Presentations</h3>

<h4>⤳ Talks</h4>
{% bibliography --query @misc[type = Talk] %}

<h3>Edited volumes</h3>
{% bibliography --query @book[title ^= Proceedings] %}

<h3>Unpublished Manuscripts</h3>
<p><em>Feel free to contact me for any unpublished materials!</em></p>
{% bibliography --query @unpublished or @thesis %}

</div>

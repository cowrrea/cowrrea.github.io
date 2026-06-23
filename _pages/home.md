---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<h2 class="home-hero">{{ site.name }}</h2>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

Hi! I am a first-year PhD student in the <a href="https://www.umass.edu/linguistics/" target="_blank">Department of Linguistics at the University of Massachusetts Amherst</a>. I am primarily interested in theoretical syntax.

Before coming to UMass, I got my B.A. in Linguistics with honors at the <a href="https://linguistics.uchicago.edu" target="_blank">University of Chicago</a> in 2025, where I wrote my undergraduate thesis titled "Obviation as dependent case: Evidence from Blackfoot pronominal enclitics", advised by <a href="https://home.uchicago.edu/karlos/" target="_blank">Karlos Arregi</a>.


### Updates

<div class="updates-timeline">
{% for article in site.data.updates limit:5 %}
<div class="updates-item">
<span class="updates-date">{{ article.date }}</span><br>
<span class="updates-headline">{{ article.headline }}</span>
</div>
{% endfor %}
</div>

<p style="margin-top: var(--space-4);"><a href="{{ site.url }}{{ site.baseurl }}/allupdates.html">See all updates &rarr;</a></p>

<!-- <div class="chip-container" markdown="0">
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Quantum Electrodynamics</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Path Integrals</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Superfluidity</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Parton Model</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Quantum Computing</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Nanotechnology</a>
</div> -->

<!-- <div class="callout callout-success" markdown="0">
<div class="callout-title"><i class="fa-solid fa-award callout-icon"></i> Nobel Prize in Physics, 1965</div>
<p>Awarded the Nobel Prize jointly with Julian Schwinger and Shin'ichiro Tomonaga for fundamental work in quantum electrodynamics, with deep-ploughing consequences for the physics of elementary particles.</p>
</div>

<div class="banner-frame" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" alt="Feynman diagrams" loading="lazy">
<div class="banner-caption">Examples of Feynman diagrams. Feynman R., <em>The theory of positrons. Phys. Rev.</em> (1949)</div>
</div> -->

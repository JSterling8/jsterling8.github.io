---
layout: archive
title: Thoughts
permalink: /thoughts
---


<div class="tiles">

{% for post in site.posts %}
  {% include post-grid.html %}
{% endfor %}

<article class="tile" itemscope itemtype="http://schema.org/Article">
  <a href="https://www.toptal.com/finance/fintech/cryptocurrency-bubble" title="Exploring the Bear Case of the Cryptocurrency Bubble" class="post-teaser"><img src="{{ site.url }}/images/bear/teaser.png" alt="teaser" itemprop="image"></a>
  <p class="entry-date date published"><time datetime="2017-11-12" itemprop="datePublished">November 12, 2017</time></p>
  <h2 class="post-title" itemprop="name"><a href="https://www.toptal.com/finance/fintech/cryptocurrency-bubble" target="_blank">Exploring the Bear Case of the Cryptocurrency Bubble (External Link)</a></h2>
  <p class="post-excerpt" itemprop="description">Shining a light on the problems blighting cryptocurrencies. Written 2 months before the crash from $20k to $6k.</p>
</article>

</div><!-- /.tiles -->

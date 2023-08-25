---
title: Publications
nav:
  order: 2
  tooltip: Published works
---

# <i class="fas fa-book-open"></i>Publications

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" filters="preprint: n"%}

{% include section.html %}

# <i class="fas fa-book-open"></i>Preprints

{% include section.html %}

{% include list.html data="citations" component="citation" style="rich" filters="preprint: y" %}

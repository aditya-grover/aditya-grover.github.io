---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022, 2021, 2020, 2019, 2018, 2016, 2015]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
see [Google Scholar](https://scholar.google.com/citations?user=oOhnPUgAAAAJ&hl=en&authuser=1) for the most updated information.

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

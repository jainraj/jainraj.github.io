---
layout: page
permalink: /publications/
title: Publications
years: [2024, 2023, 2021, 2018, 2017]
nav: true
nav_order: 4
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

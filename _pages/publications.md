---
layout: page
permalink: /publications/
title: Publications
description: 

[//]: # (description: A full list of my papers can be also found in <a href="https://scholar.google.com/citations?user=SCHOLAR_ID&user=Sw5Se_IAAAAJ">[Google Scholar]</a>.)

[//]: # (can be found in my <a href="https://scholar.google.com/citations?user=SCHOLAR_ID&user=Sw5Se_IAAAAJ">Google Scholar</a> page.)
years: [2022,2021,2020,2019]
nav: true
nav_order: 1
---
A full list of my papers can be also found in [Google Scholar]("https://scholar.google.com/citations?user=SCHOLAR_ID&user=Sw5Se_IAAAAJ")

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

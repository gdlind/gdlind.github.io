---
layout: page
permalink: /research/
title: Research
description: Publications by categories in reverse chronological order.
years: [2023, 2022, 2021]
nav: true
nav_order: 1
---
## Publications
<!-- _pages/research.md -->
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[published=true]* %}
</div>

## Working Papers
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[type=Working Paper]* %}
</div>

## Works in Process
<div class="publications">
	{% bibliography -f {{ site.scholar.bibliography }} --group_by none --query @*[type=Work in Process]* %}
</div>
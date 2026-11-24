---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h2 id="conference-papers">Conference Papers</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=conference] --group_by none %}

<h2 id="journal-articles">Journal Articles</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @article --group_by none %}

<h2 id="workshop-papers">Workshop Papers</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=workshop] --group_by none %}

<h2 id="demo-poster">Demo &amp; Poster</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=demo-poster] --group_by none %}

</div>

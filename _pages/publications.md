---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h1>Preprints</h1>

{% bibliography -f preprints %}

<h1>Journal Articles</h1>

{% bibliography -f {{ site.scholar.bibliography }} %}

<h1>Undergraduate Research</h1>

{% bibliography -f reu %}

</div>


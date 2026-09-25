---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Journal and Conference Papers</h2>

{% bibliography --query !@misc %}

<h2>Preprints</h2>

{% bibliography --query @misc %}

</div>

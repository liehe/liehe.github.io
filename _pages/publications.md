---
layout: page
permalink: /publications/
title: Publications
description: "*: equal contribution; †: corresponding author."
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h1>Conference &amp; journal papers</h1>

{% bibliography --group_by year --group_order descending --query @*[category=published]* %}

<h1>Preprints</h1>

{% bibliography --group_by year --group_order descending --query @*[category=preprint]* %}

<h1>Workshop &amp; technical reports</h1>

{% bibliography --group_by year --group_order descending --query @*[category=other]* %}

</div>

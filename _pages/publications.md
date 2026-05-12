---
layout: page
permalink: /publications/
title: publications
description: publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="year">2026</h2>

<h3>International</h3>

{% bibliography --group_by none --query @*[year=2026][venue_type=international] %}

<h3>Domestic</h3>

{% bibliography --group_by none --query @*[year=2026][venue_type=domestic] %}

<h2 class="year">2025</h2>

<h3>International</h3>

{% bibliography --group_by none --query @*[year=2025][venue_type=international] %}

<h3>Domestic</h3>

{% bibliography --group_by none --query @*[year=2025][venue_type=domestic] %}

</div>

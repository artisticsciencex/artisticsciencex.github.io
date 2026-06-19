---
page_id: publications
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<h2>Peer-Reviewed Papers (Full &amp; Short)</h2>

<div class="publications">

{% bibliography --query @*[type_group=paper]* %}

</div>

<h2>Posters, Demos &amp; Extended Abstracts</h2>

<div class="publications">

{% bibliography --query @*[type_group=poster]* %}

</div>

---
layout: page
permalink: /talks/
title: talks
description:
nav: true
nav_order: 2
display_categories:
  - Outreach
  - Conference
---

<!-- _pages/talks.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Conferences

<div class="publications">

  {% bibliography -f talks -q @*[category=conference]%}

</div>

## Outreach

<div class="publications">

 {% bibliography -f talks -q @*[category=outreach]%}

</div>


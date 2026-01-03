---
layout: page
permalink: /talks/
title: talks
description:
nav: true
nav_order: 2
display_categories:
  - Oral
  - Poster
  - Outreach
---

<!-- _pages/talks.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Oral

<div class="publications">

  {% bibliography -f talks -q @*[category=oral]%}

</div>

## Poster

<div class="publications">

  {% bibliography -f talks -q @*[category=poster]%}

</div>

## Outreach

<div class="publications">

 {% bibliography -f talks -q @*[category=outreach]%}

</div>


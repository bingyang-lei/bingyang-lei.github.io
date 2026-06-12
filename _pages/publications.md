---
layout: page
permalink: /publications/
title: Publications
description: Full publication list.
nav: true
nav_order: 2
---

{% if site.bib_search %}
{% include bib_search.liquid %}
{% endif %}

<div class="publications">

{% bibliography %}

</div>

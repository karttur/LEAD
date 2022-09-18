---
layout: page
title: Need
excerpt: "An archive of posts sorted by date."
image: std-trmm-3b43v7-precip_3B43_trmm_2001-2016_A
search_omit: true
---

#### Introduction

Soil is formed over millenia and increasingly recognised as a vital resource. Soil management affects 16 of the 17 Sustainable Development Goals (SDGs) 2030. Soils are the hub for producing food, fodder, fibre and now also fuel for a growing world population. But soil health is declining world-wide. This affects both the soil productivity and generates Greenhouse Gas (GHG) emissions. New methods and policies are required. For producing more food, fodder, fibre and fuel while also preserving, or improving, soil health. The methods for accomplishing this are known: zero (or low) tilling, cover (or dual) crops, agroforestry, use of legumes, adaptive grazing, residue management and exogenous carbon amendments, subsoiling and crop rotation.

#### Regenerative precision farming

With the era of cheap fossil fuels nearing its end, escalating soil health decline and dwindling yield per resource input, the shift to new agricultural management methods is becoming increasingly urgent. Empirical results clearly demonstrate that regenerative precision farming starting from the methods listed above for supporting soil health, bring the same yield as classical mechanised high-input management, but at a much lower cost. And with the added benefit of sequestering atmospheric CO2 and improving soil heath. Farmers adopting regenerative precision farming thus make a larger economic profit while also improving their soils. The bottleneck, or **need** for acquiring regenerative precision farming is information (see the popular article [Why soil measurement is a key challenge for carbon farming](https://www.fwi.co.uk/arable/land-preparation/soils/why-soil-measurement-is-a-key-challenge-for-carbon-farming)). Information on soil and plant health in (near) real time. Put differently: to minimise the input of machinery, fuel and chemicals, farmers must have control of the soil and plant status to restrict costly (and soil destructing) activities to a minimum. Thus can the farmer produce more grain for less pain.

The need for a solution that can provide (near) real time soil information thus already exists today. Escalating climate change and carbon emission/reduction pricing is, however, also driving an emerging market for direct soil carbon credits.

#### Soil carbon credits

Hitherto soil degeneration has not been reflected in the economic market - soils have largely been de-facto regarded as externalities (except when validating farmland and leases). Driven by urgent problems with climate warming and famine, the need to preserve, or even improve, soil health is increasingly recognised. Both by local farmers and by policy makers, as well as the stakeholders in the food chain in between. This has paved the way for a new market of soil health in general and soil carbon credits in particular, driven by 3 needs:

1. farmers need to preserve and improve soil health and productivity,
2. food chain stakeholders (businesses and end consumers) urge to to produce and consume healthy, sustainable and climate neutral food and drinks, and
3. policy makers regulation of carbon emission and GHG emission costs and acquisition credits.

This new market for carbon credits based on soil organic carbon (SOC) requires a cost-effective and robust monitoring and modeling framework. Existing carbon credits for soil sequestration, mainly in North America and Australia, are plagued by regional variations and fears have been raised that the integrity of soil carbon credits is eroding. European countries have not embraced crediting agricultural soil carbon sequestration. Nevertheless, the development of new agricultural technologies promoting SOC formation has captured a large interest and field trials are in place, for instance, in Sweden and Finland.

The European Commission is strongly supporting development of a common European Soil Carbon Credit. That requires a standardised system of certificates, that the Commission envisions being based on a combination of rapid in-situ data collection and remote sensing.

#### Soil carbon and climate

Greenhouse gas (GHG) emissions are jeopardizing the stability of Earth’s climate, threatening the sustainability of both existing ecosystems and subsequently human life as we know it. GHG emissions from soils, primarily driven by the metabolism of the soil organic carbon (SOC) stocks and generating carbon dioxide (CO2) contribute around 5 % of the global GHG emissions with an estimated gross efflux of ∼60 Gt C per year. It is estimated that the accumulated land cultivation has depleted the global soil carbon stock of 116 Pg of carbon.
But agricultural soils can also sequester carbon, with estimates or annual potentials ranging from 100 to 1000 kg C per hectare, depending on soil type and management practices. Reversing the flux of carbon across the soil-atmosphere interface and accumulating more SOC while sequestering GHG (henceforth: carbon or regenerative farming) has major benefits, also for soil fertility and soil health. The recent (2022) IPCC assessment report also points out carbon farming as one of the major pathways for preventing the global temperature rise to exceed 2 centigrades compared to pre-industrial conditions.  

Scientifically validated, cost-efficient and widely applicable, monitoring and modeling frameworks are required in order to identify the effect of different management options and how they affect soil carbon fluxes and stocks. The most promising approach for rapid assessment of soil health and carbon fluxes is soil spectroscopy.

#### Documents

<ul class="post-list">
{% for post in site.categories.need %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

---
layout: page
title: Benefits
excerpt: "An archive of blog posts sorted by date."
image: std-trmm-3b43v7-precip_3B43_trmm_2001-2016_A
search_omit: true
---

### Introduction

The benefits of xSpectre's "_Swiss army knife for soil testing_" are: on demand, rapid and cost-effective soil characterisation in real-time. This information in turn supports, complements or substitutes three distinctive markets:

- Precision farming,
- Soil fertility testing, and
- Soil carbon credits.

### Precision farming

The global [market for precision farming](https://www.marketsandmarkets.com/Market-Reports/precision-farming-market-1243.html?gclid=Cj0KCQjwmouZBhDSARIsALYcouqj1j8QXxHTqP9hHhYNm6kLNdVVkGlyzEVhD9K0IPKtvcj2_DZ4uJQaAvKjEALw_wcB) is expected to grow from USD 8.5 billion in 2022 to USD 15.6 billion by 2030, at a Compound annual growth rate (CAGR) of 7.9%.

This market is driven both by technological and economical factors. The technological factors are linked to the general development summarised as Internet-of-Things (IoT), with developments in all parts of the chain formed by sensors, networks, applications, computer modeling power and actuators (Fig 1). The economic factors are primarily cost savings, in e.g. man-power, machinery, fossil fuel consumption and fertiliser use, rather than increases in yields. A growing economic factor is the development of soil carbon markets promoted by governments worldwide.

xSpectre handheld spectrometer for soil testing  benefit precision farming by 1. improving the accuracy of the models predicting soil conditions that are piloting the actuators, and 2) supplying real time sensor data.   

<figure>
<img src="../../images/geoimagine_architecture_vinnova_v01_20200511.png">
<figcaption> Fig 1. Architecture of Smart farming with spectral data. </figcaption>
</figure>

### Soil fertility testing

The global market for [soil fertility testing](https://www.researchandmarkets.com/reports/5394045/soil-fertility-testing-market-forecast-to-2028) is expected to grow from USD 4.3 billion in 2020 to USD 5.9 billion by 2028, at a CAGR of 4.1%. Sweden has no legal requirements regarding soil fertility testing; the recommendation is a single test per hectare every 7th years. The Swedish market for soil fertility testing in 2022 is this estimated to approximately 15 million USD.

The soil fertility testing referred to here is the classical wet laboratory (physical, chemical, and biological) testing to determine the growth potential of soil, indicating inadequacies of nutrients, potential toxicity caused by excessive fertility, and inhibitions due to non-essential trace minerals. It does not include testing required for a soil carbon market.

New methods for rapid and cost-effective soil characterisation in real-time, with proven accuracy, will lead to a more rapid growth of this market. As no mature system exists, the future potential can not be predicted.

xSpectre's Swiss pocket knife soil testing concept bring benefits for the agricultural consultants that often do the soil testing (see section on [competition](../../competition)) - they can sample a more dense grid of points at very low costs by using spectral modeling for extrapolating wet laboratory results. The relative low cost of xSpectre's spectrometers also opens for individual farmers to directly test soils in real time at negligible marginal costs.

### Soil carbon credits

The market for soil carbon credits is growing, but it is a disparate market that lacks accepted standards. The market for soil testing supporting soil carbon credits is thus neither established nor predictable.

xSpectre's pocket sized soil laboratory could become a tool for standardising Monitoring, Reporting and Validation (MRV) of soil carbon credits. This would bring large benefits to farmers, and other stakeholders in the food production chain.

### Documents

<ul class="post-list">
{% for post in site.categories.benefit %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

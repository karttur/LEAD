---
layout: page
title: Competition
excerpt: "An archive of blog posts sorted by date."
image: std-trmm-3b43v7-precip_3B43_trmm_2001-2016_A
search_omit: true
---

### Introduction

Competitors in the market of supplying soil information include:

- Agriculture consultants,
- Wet laboratories,
- DIY soil test kits,
- Remote sensors on drones and satellites,
- eDNA methods,
- Macrofauna characterisation,
- Scientific field spectrometers, and
- other portable soil multi-sensors

### Agriculture consultants

Agricultural consultants, in Sweden for instance [Hushållningssällskapet](https://hushallningssallskapet.se), [Lovang Lantbrukskonsult AB (Linköping)](http://www.lovanggruppen.se/lantbrukskonsult-kontakt/) and [SOYL Sweden](https://www.soyl.se) offer different advisory services to farms. One of the most prominent services is mapping of soil conditions. This essentially means that the consultant, or the farmer, takes soil samples that are sent for analysis to a wet laboratory. The consultants interpret the laboratory results and interpolates the point data to maps. The latter can be done with or without other covariates (e.g. topography or soil types) and with or without the support of remote sensing data from drones or satellites.

The consultants are both competitors and potential customers of xSpectre's Swiss army knife for soil testing.

### Wet laboratories

The analysis of soil conditions for farm management is today dominated by wet laboratories (even if [NIR soil spectroscopy](../../approach/approach-NIR-general)) is part of the laboratory soil characterisation). The frequency of soil laboratory testing in Sweden is approximately 1 sample per hectare every 7th year. In Sweden this is just a recommendation, other countries have leal requirements, not seldom at a higher resolution in time and space.

A future demand for higher frequency soil sampling can be met by more wet laboratory analysis. But this is a time-consuming and expensive alternative compared to complementing the wet laboratory analysis with spectral in-situ sampling. Thus it is unlikely that xSpectre's soil spectrometer will outcompete wet laboratories, the relation would rather be a mutual benefit.

### DIY soil test kits

One possible alternative solution for better surveillance of soil conditions is Do-It-Yourself soil test kits. These have, however, been around for a long time and should already have become a more widely used solution to be considered as a serious competitor.

### Remote sensing

Using images from drones or satellites for soil mapping over larger areas (from fields to continents) is today commonly done. To map the soil conditions under green vegetation requires that the vegetation part of the spectral signal is removed (unmixed). Varying geometries between the sun, the land surface and the sensor causes further problems. Interpreting remotely sensed images is thus not trivial. Developments in both sensors and in computer modelling power (e.g. Artificial Intelligence) is leading to improved accuracies. If the interpretation is supported by local in-situ sample data, the accuracy of the interpreted remote imagery increase markedly.

Remote sensing is a serious competitor to xSpectre's handheld in-situ soil spectrometer. In-situ versus remote sensing of soil conditions both have advantages and disadvantages. A combination that uses in-situ measurements for calibration of remotely sensed images holds promises for near real-time accurate soil properties mapping.

### eDNA

Soil environmental DNA (eDNA) analysis has grown rapidly over the past decade. Reference databases that link soil conditions to eDNA exist for large regions in e.g. Europa and North America. Soil eDNA sampling and analysis, however, are tedious and expensive. The accuracies for estimating key soil physical and chemical conditions from eDNA are further unclear. Thus eDNA is not a competitor for spectral soil characterisation at the present time. Future development might alter this.

### Macrofauna characterisation

Macrofauna (think: "earthworms") characterisation is a traditional methods for determining holistic soil health. Digital image processing and interpretation has led to methods for estimating the macrofauna using digital photography, rather than collecting and counting individuals. The sampling is, however, tedious and weather dependent, and the uncertainty of the results large. Macrofauna characterisation is thus not an alternative to other methods for rapid soil surveillance.

### Scientific field spectrometers

Scientific grade portable spectrometers for field use have been commercially available for decades. They are, however heavy and bulky, require a backpack and are usually operated by a PC that must be carried along. New developments have led to smaller units, but still requiring carrying cases or back packs. The prices are prohibiting for more widespread use. The difference in cost between using a scientific field spectrometer compared to taking samples for laboratory spectral analysis is small. xSpectres handheld spectrometer is a miniaturised science grade field spectrometer (and cost 1/100th of commercially available field spectrometers). But with a more restricted band width (350 - 1000 nm) compared to the larger scientific field spectrometers (350-2500 nm). New technologies for acquiring spectra in the 1000 - 2500 nm region is paving the way for cheaper sensors that fit into the design of xSpectre's handheld device. Also the existing science grade field spectrometers will take advantage of this development.

### Other portable soil multi-sensors

### Wet laboratories

[Hushållningssällskapet Laboratorium](https://laboratorium.hushallningssallskapet.se/properties/jord/).

### Portable soil mulit-sensors

[Stenon digital spade](https://stenon.io/en/)

### Documents

<ul class="post-list">
{% for post in site.categories.competition %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

---
layout: page
title: xSpectre's pocket soil laboratory
excerpt: "Overview of Karttur´s projects on GitHub"
image: rainfall-delta_3B43_trmm_2001-2016_mk-z-ts-model
search_omit: true
---

### Introduction

LEAD is both a word in itself, but also an abbreviation for Linköping University Entrepreneurship and Development. The latter is an organisation that supports developing research ideas and results to commercial products and services. In this blog [LEAD](https://www.lead.se/en/) is a business incubator.

LEAD anchors the incubation process for startups using the [NABC](https://www.innovation.lu.se/en/our-services/developing-ideas-innovations/nabc-how-test-your-idea) concept:

- Need
- Approach
- Benefit
- Competition

[xSpectre](https://xspectre.com) participated in [LEADs BootUp progam](https://www.lead.se/en/our-offer/our-memberships/bootup/) during spring 2022. We realised that up to this point we had focused too much on the _Approach_. When we got an offer to bring our innovation to LEADs trainee program [Entrepreneurs in Residence](https://www.lead.se/en/entrepreneur-programs/entrepreneurs-in-residence/), we gladly accepted.

This public blog links to online resources that relate to xSpectre's innovation. The blog is organised using the NABC concept. But first a short summary of xSpectre's innovation and business idea.

### Swiss pocket knife for soil testing

Modern agriculture requires both in-depth and up-to-date knowledge of soil properties. The need for relevant information in time and space stems both from the economic requirements for efficiency and yield, but also increasingly from laws and regulations. Increased consumer demand for environmentally and climate-neutral products, new agtech technologies ("smart farming") and more ambitious policy regulations are expected to lead to further needs for measurements and monitoring of agricultural land. xSpectre has developed an approach to easily, quickly and cost- effectively gather local knowledge about soil physical and chemical properties. The solution consists of a handheld spectrometer that is connected to a service for modeling and analysis via a mobile app. The service and the mobile app are packaged as an Internet service (SaaS). Our solution can both replace and / or supplement today's wet chemical analysis methods, but can also be linked to images from drones and satellites for mapping large areas.

### [Need](../need/)

<ul class="post-list">
{% for post in site.categories.need %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

### Approach

<ul class="post-list">
{% for post in site.categories.approach %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

### Benefit

<ul class="post-list">
{% for post in site.categories.benefit %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

### Competition

<ul class="post-list">
{% for post in site.categories.competition %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

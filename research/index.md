---
title: Research
nav:
  order: 1
  tooltip: Publications
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Please provide description of lab's research focus and Interests.

Research Interests:

Molecular mechanisms of neurological disorders, especially myelin formation and maintenance, using data on humans and mouse and fruit fly models.

Molecular organization and structure of the nuclear lamina.

{% include section.html %}

## Highlighted

{% assign highlighted = site.data.citations | where: "highlight", true %}
{% for c in highlighted %}
  {% include citation.html lookup=c.id style="rich" %}
{% endfor %}
{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}

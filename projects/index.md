---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

The following research projects demonstrate iSQARE's commitment to advancing software engineering through developer-centric empirical studies, AI-powered tool development, and real-world impact.

{% include list.html component="card" data="projects" %}

{% comment %}
{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
{% endcomment %}
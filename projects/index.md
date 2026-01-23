---
title: Projects
nav:
  order: 2
  tooltip: Current projects, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

We combine environmental, ecological and genomic tools. Here are some of our current projects, publications, tutorials or field reports.

{% include tags.html tags="project, publication, tutorial, dataset, field" %}

{% include search-info.html %}

{% include section.html %}

## Latest

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="group == 'old'" %}

<!-- {% include list.html component="card" data="projects" filter="!group" style="small" %} -->

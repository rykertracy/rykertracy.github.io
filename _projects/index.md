---
layout: single
title: "Projects"
permalink: /projects/
---

# Projects

A selection of projects I’ve worked on, blending **geoscience** and **data science**:

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }}) — {{ project.description }}
{% endfor %}
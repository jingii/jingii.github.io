---
layout: page
title: Projects
permalink: /projects/
description: Some research projects and course projects I have done.
nav: true
nav_order: 2
display_categories: [Research, Course]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
    {% endfor %}
{%- endif -%}
</div>

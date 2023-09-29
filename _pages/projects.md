---
layout: page
title: Projects
permalink: /projects/
description: Some research projects and course projects I have done.
nav: true
nav_order: 2
display_category1: Research
display_category2: Course
horizontal: false
---

<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  <h2 class="category">{{ page.display_category1 }}</h2>
  <h2 class="category">{{ page.display_category2 }}</h2>
{% endif %}
</div>

  


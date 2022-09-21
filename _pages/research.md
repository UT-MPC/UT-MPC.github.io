---
layout: page
title: Research
permalink: /research/
description: Our research is in the general intersection of software engineering with dynamic, resource constrained networks. We focus on programming abstractions, middleware, models, and tools that ease the programming burden in these complex, dynamic, and unpredictable environments. Here, we provide details of our current and past projects; for more information, please contact us directly.
nav: true
nav_order: 2
display_categories: [Current Projects, Previous Projects]
horizontal: true
---

<!-- pages/research.md -->
<div class="research">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized research -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_research = site.research | where: "category", category -%}
  {%- assign sorted_research = categorized_research | sort: "importance" %}
  <!-- Generate cards for each member -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for research in sorted_research -%}
      {% include research_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for research in sorted_research -%}
      {% include research.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display research without categories -->
  {%- assign sorted_research = site.research | sort: "importance" -%}
  <!-- Generate cards for each member -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for research in sorted_research -%}
      {% include research_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for research in sorted_research -%}
      {% include research.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
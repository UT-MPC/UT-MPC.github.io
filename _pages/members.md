---
layout: page
title: Members
permalink: /members/
description:
nav: true
nav_order: 1
display_categories: [Director, Graduate Students, Alumni]
horizontal: true
---

<!-- pages/members.md -->
<div class="members">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized members -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_members = site.members | where: "category", category -%}
  {%- assign sorted_members = categorized_members | sort: "importance" %}
  <!-- Generate cards for each member -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for member in sorted_members -%}
      {% include members_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for member in sorted_members -%}
      {% include members.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display members without categories -->
  {%- assign sorted_members = site.members | sort: "importance" -%}
  <!-- Generate cards for each member -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for member in sorted_members -%}
      {% include members_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for member in sorted_members -%}
      {% include members.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

---
layout: page
title: Products
permalink: /products/
description: Personal projects, and space for projects still in progress.
nav: true
nav_order: 3
display_categories: [current, future]
horizontal: false
---

<div class="projects">
  {% for category in page.display_categories %}
    {% if category == "current" %}
      {% assign category_heading = "Current projects" %}
    {% elsif category == "future" %}
      {% assign category_heading = "Future projects" %}
    {% else %}
      {% assign category_heading = category %}
    {% endif %}
    <h2 class="category" id="{{ category | slugify }}">{{ category_heading }}</h2>
    {% assign categorized_projects = site.projects | where: "category", category %}
    {% assign sorted_projects = categorized_projects | sort: "importance" %}
    <div class="grid">
      <div class="grid-sizer"></div>
      {% for project in sorted_projects %}
        {% include product_card.liquid %}
      {% endfor %}
    </div>
  {% endfor %}
</div>

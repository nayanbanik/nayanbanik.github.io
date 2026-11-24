---
layout: page
title: hackathons
permalink: /hackathons/
description: Hackathons I have competed in, with the result, my role, and what the team built.
nav: true
nav_order: 3
---

<!-- One card per file in _hackathons/, ordered by the `importance` field (1 = shown first). -->
<div class="projects">
  {% assign sorted_projects = site.hackathons | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>

I also took part in Microsoft's **Hack Together: RAG Hack** in 2024 ([verified badge](https://www.credly.com/badges/0b0167fb-438f-4e96-b9a2-539cf9cd1b31)).

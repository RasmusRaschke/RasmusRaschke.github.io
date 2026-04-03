---
layout: page
title: MyWiki
description: My personal math wiki.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---
This is an attempt at creating my own encyclopedia of everything I learned about mathematics. To organize everything, I use the free software Obsidian. Everything can be found here:
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_obsidian %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>

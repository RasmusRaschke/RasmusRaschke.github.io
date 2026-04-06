---
layout: page
title: MyWiki
description: My personal math wiki.
img: assets/img/mathwiki.png
importance: 1
category: work
related_publications: false
---
This is a little Obsidian vault organized in the style of a wiki. Whenever I have time, I try to write entries about mathematics and adjacent topics of interest to me.
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
{% for repo in site.data.repositories.github_obsidian %}
{% include repository/repo.liquid repository=repo %}
{% endfor %}
</div>

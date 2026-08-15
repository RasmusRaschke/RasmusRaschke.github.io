---
layout: page
title: MyWiki
description: My personal math wiki.
img: assets/img/mathwiki.png
importance: 1
category: personal
related_publications: false
---
This is a little Obsidian vault organized in the style of a wiki. Whenever I have time, I try to write entries about mathematics and adjacent topics of interest to me. The language is quite category-oriented and certainly inspired by the works of Emily Riehl, whose books taught me category theory. Right now, I am in the process of rewriting it, so it is empty for the time being.
Link: [MyWiki](https://github.com/RasmusRaschke/MyWiki.git)
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
{% for repo in site.data.repositories.github_obsidian %}
{% include repository/repo.liquid repository=repo %}
{% endfor %}
</div>

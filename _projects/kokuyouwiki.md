---
layout: page
title: KokuyouWiki
description: My personal Japanese wiki.
img: assets/img/kokuyouwiki.jpg
importance: 1
category: personal
related_publications: false
---
This is a little Obsidian vault organized in the style of a wiki. Whenever I have time, I try to write entries about Japanese grammar I encountered throughout my studies. Inspired by my training in mathematics, many articles may be more linguistic and abstract than needed. Since I do not consider myself fluent enough to guarantee correct example senteces, I excerpt examples from [Imabi](https://imabi.org/) and the well-known Dictionary of Basic/Intermediate/Advanced Japanese Grammar.\\
Link: [黒曜ウイキ](https://github.com/RasmusRaschke/kokuyouwiki.git)
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
{% for repo in site.data.repositories.github_obsidian %}
{% include repository/repo.liquid repository=repo %}
{% endfor %}
</div>

---
layout: page
title: ribodyn
description: RIgid BOdy DYNamics
img: assets/img/ribodyn.png
importance: 1
category: work
related_publications: false
---
This repository contains a program to simulate the dynamics of rigid bodies in three dimensions using Euler-Lagrange and Lagrange-d'Alembert approaches. This makes it possible to simulate rigid bodies influenced by a wide range of non-holonomic affine constraints and conservative as well as dissipative forces.\\
Link: [ribodyn](https://github.com/RasmusRaschke/ribodyn.git)
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
{% for repo in site.data.repositories.github_magsphere %}
{% include repository/repo.liquid repository=repo %}
{% endfor %}
</div>

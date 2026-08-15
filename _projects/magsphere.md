---
layout: page
title: magsphere
description: A program to simulate the dynamics of magnetic spheres in external fields.
img: assets/img/magsphere.jpg
importance: 1
category: work
related_publications: false
---
The repository contains a program designed to simulate the dynamics of a magnetic solid sphere rolling on an incline in an external magnetic field, as well as a python package to analyse the output of the simulation. All contents were created together with Elena Y. Vedmedenko and Tim Matthies for our paper on the dynamics of such systems.\\
Link: [magsphere](https://github.com/RasmusRaschke/magsphere.git)
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
{% for repo in site.data.repositories.github_magsphere %}
{% include repository/repo.liquid repository=repo %}
{% endfor %}
</div>

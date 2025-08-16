---
layout: page
permalink: /data_codes/
title: data+code
description:
nav: true
nav_order: 3
---
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
        src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

### Data products

The [DORCHA](https://solas-sims.github.io/projects/dorcha/) data products, including snapshots, halo catalogs, and merger trees, will be made available [here](https://solas-sims.github.io/data_products/) in the near future. In the meantime please send me an email.

For the dark matter merger trees of the $$\rm{L}10\_\rm{N}2048$$ Genesis box used in [Ventura+24](https://ui.adsabs.harvard.edu/abs/2024MNRAS.529..628V/abstract) and [Ventura+25](https://ui.adsabs.harvard.edu/abs/2025MNRAS.540..483V/abstract) go [here](https://zenodo.org/records/10608236). This run consists of $$2048^3$$ dark matter particles in a cosmological volume of side $$10~h^{-1}\,\rm{Mpc}$$. There are 120 snapshots between $$z=30$$ and $$5$$.  Get in touch if you want the full snapshot data.

### Code

Almost all of my codes are available at my [github profile](https://github.com/s-balu). Please feel free to contact me if you have any questions.

<!-- code for GitHub users -->
<!-- {% if site.data.repositories.github_users %} -->
<!-- <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center"> -->
<!--   {% for user in site.data.repositories.github_users %} {% include repository/repo_user.liquid username=user %} {% endfor %} -->
<!-- </div> -->
<!-- {% endif %} -->
<!---->
<!-- code for GitHub repositories -->
{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %} {% include repository/repo.liquid repository=repo %} {% endfor %}
</div>
{% endif %}

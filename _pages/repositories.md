---
layout: page
permalink: /repositories/
title: Repositories
description: I'm in favor of open source code and reproducible research. That's why I try to put all my research in GitHub repositories.
nav: true
nav_order: 4
---

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}

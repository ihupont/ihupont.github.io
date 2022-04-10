---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Google Scholar does a good job showcasing researchers' academic publications! 

You can check the articles I have co-authored and their citation metrics in [my public Google Scholar profile](https://scholar.google.com/citations?user=jNLffNcAAAAJ&hl=es).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

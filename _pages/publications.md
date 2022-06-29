---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<br>
Google Scholar does a good job showcasing researchers' academic publications! You can check the articles I have co-authored in the past and their citation metrics in [my public Google Scholar profile](https://scholar.google.com/citations?user=jNLffNcAAAAJ&hl=es).

In this section I will focus on presenting in more detail my most recent and impactful work.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

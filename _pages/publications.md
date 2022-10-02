---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<br>
You can check all the articles I have co-authored in my public <b>[Google Scholar profile](https://scholar.google.com/citations?user=jNLffNcAAAAJ&hl=es)</b>. Here below, I present only a small recent selection of them, either because they have some associated material (e.g. a dataset, a repository) or because of their impact with respect to Trustworthy AI.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<br>
You can check all the articles I have co-authored in my public [Google Scholar profile](https://scholar.google.com/citations?user=jNLffNcAAAAJ&hl=es). Below, I present a selection of them, either because they have some associated material (e.g. a dataset, a repository) or because of their impact on Trustworthy AI and Virtual Worlds.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

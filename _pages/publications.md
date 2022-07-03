---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<br>
You can check all the articles I have co-authored in my public <b>[Google Scholar profile](https://scholar.google.com/citations?user=jNLffNcAAAAJ&hl=es)</b>. Here below, I focus on presenting in more detail a selection of my most recent work.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

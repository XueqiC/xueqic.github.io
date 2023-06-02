---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find all of my publications on my [Google Scholar profile](https://scholar.google.com/citations?user=MWnSFPMAAAAJ&hl=en)

{% include base_path %}

Selected Papers
==========

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

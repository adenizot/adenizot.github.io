---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.fr/citations?user=c4C2mSsAAAAJ&hl=fr) and on my HAL [CV](https://cv.hal.science/audrey-denizot).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

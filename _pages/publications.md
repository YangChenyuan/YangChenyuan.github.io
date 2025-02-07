---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=2M-Bb9EAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-paper.html %}
{% endfor %}

<i>* denotes joint first authors</i>
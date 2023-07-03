---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on <a href="https://scholar.google.com/citations?user=nFh-9y0AAAAJ&hl=zh-CN&oi=ao">my Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

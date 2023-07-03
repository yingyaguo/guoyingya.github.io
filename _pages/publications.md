---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---


  You can also find my articles on <a href="https://scholar.google.com/citations?user=nFh-9y0AAAAJ&hl=zh-CN&oi=ao">my Google Scholar profile</a>.


{% include base_path %}

近五年代表作:
---
{% for post in site.publications reversed%}
  {% include archive-single.html %}
{% endfor %}

其余著作:
---

1.流量工程和路由优化
---
{% for post in site.otherpublications2 reversed %}
  {% include archive-single.html %}
{% endfor %}


2.边缘计算和云计算
---
{% for post in site.otherpublications3 reversed %}
  {% include archive-single.html %}
{% endfor %}

3.网络流量预测和分类
---
{% for post in site.otherpublications reversed %}
  {% include archive-single.html %}
{% endfor %}

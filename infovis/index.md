---
layout: archive
title: "信息可视化作品集"
date: 
modified:
excerpt: ""
tags: []
image: 
---

<br/>信息可视化期末专案
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 notes 的列出来-->

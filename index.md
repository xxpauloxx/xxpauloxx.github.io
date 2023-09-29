---
layout: default
title: Hello, World!
---

{% capture current_lang %}{{ site.lang | default: "en" }}{% endcapture %}
<h2>{{ site.data[current_lang].hello }}</h2>

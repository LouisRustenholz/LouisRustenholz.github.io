---
layout: page
permalink: /talks/
title: talks
nav: true
nav_order: 2
---

{% capture talks_md %} {% include talks.md %} {% endcapture %}
      {{ talks_md | markdownify }}

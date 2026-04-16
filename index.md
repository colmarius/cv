---
layout: default
title: Marius Colacioiu
description: Marius Colacioiu's CV
---

{% capture cv %}
{% include_relative README.md %}
{% endcapture %}

{{ cv | markdownify }}

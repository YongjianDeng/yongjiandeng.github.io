---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes/personalIntro.md %}

<!-- {% include_relative includes/news.md %} -->

{% include_relative includes/publications.md %}

{% include_relative includes/services.md %}

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=400&t=n&d=oABR0nOA2tRoY_m6lL__HUjr-WAhdWoBax55Hk3rUH4&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>

<!-- # 💻 NVRLab
### Under construction. -->
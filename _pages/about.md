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

Jiedong Wang(王杰栋) is an undergraduate student at the College of Computer Science, Sichuan University(SCU), advised by Prof.[Hao Wang](https://cshaowang.github.io) of [XLearning](https://pengxi.me/) research group at SCU. 

His research focuses on Multi-view Learning and Continual Learning.

# 🔥 News
- *2025.4*: &nbsp;Two papers about Multi-view learning were accepted by International Joint Conference on Artificial Intelligence(IJCAI 2025)!

# 📝 Publications 
\* Equal contribution $\dagger$ Corresponding author
{% assign papers = site.data.papers %}

{% for paper in papers %}
<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='{{ paper.img }}' alt='sym'>
  </div>
  <div class='paper-box-text'>
  {{ paper.src | markdownify}}
    <a href="{{ paper.link }}" target="_blank">{{ paper.title}}</a>
    <div class="authors">{{ paper.authors | markdownify }}</div>
  </div>
</div>
{% endfor %}

# 🎖 Honors and Awards
- *2023.11*: &nbsp;The 2023 ICPC Asia Hefei Regional Contest, Silver Medal.
- *2024.9*: &nbsp;National Scholarship(Undergraduate, Top 2%).

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js">
</script>
<span id="busuanzi_container_site_pv">    
	总访问量<span id="busuanzi_value_site_pv"></span>次
</span>
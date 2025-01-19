---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019]
nav: true
---

[[Google scholar](https://scholar.google.com.hk/citations?user=KGyu9ZcAAAAJ&hl=en)] | [[DBLP](https://dblp.org/pid/241/4306.html)]

#### Recent papers in top-tier conferences/journals

- Zhongkai Yu, \textbf{\textcolor{blue}{Shengwen Liang}}, Tianyun Ma, Yunke Cai, Ziyuan Nan, Di Huang, Xinkai Song, Yifan Hao, Jie Zhang, Tian Zhi, Yongwei Zhao, Zidong Du, Xing Hu, Qi Guo, and Tianshi Chen. Cambricon-LLM: A Chiplet-Based Hybrid Architecture for On-Device Inference of 70B LLM, 2024 57th IEEE/ACM International Symposium on Microarchitecture (MICRO), Austin, TX, USA, 2024, pp.1474-1488.
- Xiurui Pan, Yuda An, \textbf{\textcolor{blue}{Shengwen Liang}}, Bo Mao, Mingzhe Zhang, Qiao Li, Myoungsoo Jung, and Jie Zhang. Flagger: Cooperative acceleration for large-scale cross-silo federated learning aggregation, 2024 ACM/IEEE 51st Annual International Symposium on Computer Architecture (ISCA). IEEE, 2024, pp.915-930.


#### Papers

<div class="publications">

{% for y in page.years %}
<div>{{y}}</div>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

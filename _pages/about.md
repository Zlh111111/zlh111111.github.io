---
permalink: /
title: ""
excerpt: ""
author_profile: true
lang: en
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

<span class="anchor" id="about-me"></span>

<div class="page-header-with-lang">
  <h2 class="page-title">🤵🏻 About Me</h2>

  <div class="lang-switch">
    <span class="lang-switch__item is-active">English</span>
    <a href="/zh/" class="lang-switch__item">中文</a>
  </div>
</div>


I am currently pursuing a Ph.D. at the School of Automation at Central South University, where I am conducting research on extreme regression modeling under the supervision of [Yun Wang](https://faculty.csu.edu.cn/wangyun1/zh_CN/index.htm). I graduated from the School of Computer Science at Minnan Normal University with a bachelor’s degree and earned my master’s degree from the same school under the supervision of [Hong Zhao](https://fhqxa.github.io//). 

My research interests include **Computer Vision (CV)** and **Time Series Forecasting (TSF)**. My current research focuses on the following topics:
- **Extreme Regression Modeling**
- **Few-Shot Learning (FSL)**
- **Graph Neural Networks (GNNs)**

If you are seeking any form of academic cooperation, please feel free to email me at [linhuazou00@163.com](mailto:linhuazou00@163.com) / [zlh1836065471@163.com](mailto:zlh1836065471@163.com).

# 📝 Academic Service
- Reviewer for *Pattern Recognition (PR)*
- Reviewer for *Neural Networks (NN)*
- Reviewer for *Knowledge-Based Systems (KBS)*
- Reviewer for *Expert Systems with Applications (ESWA)*




# 🔥 News
- *2025.10*: &nbsp;🎉 Our paper “[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](#fcgnn)” is accepted by *IEEE Transactions on Fuzzy Systems (TFS)*. 
- *2025.04*: &nbsp;🎉 Our paper “[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](#fsake)” is accepted by *Expert Systems with Applications (ESWA)*.
- *2025.04*: &nbsp;🎉 Our paper “[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](#macf)” is accepted by *Information Sciences (INS)*.
- *2025.02*: &nbsp;🎉 Our paper “[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](#fspdf)” is accepted by *Knowledge-Based Systems (KBS)*.
- *2024.08*: &nbsp;🎉 Our paper “[基于自适应原型特征类矫正的小样本学习方法](#crapf)” is accepted by *自动化学报 (ACTA AUTOMATICA SINICA, AAS)*.


# 📝 Publications 

<div class='paper-box' id="fcgnn">
  <div class='paper-box-image'>
    <div>
      <div class="badge">TFS 2026</div>
      <img src='images/2026-TSF-FCGNN.png' alt="FCGNN" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](https://ieeexplore.ieee.org/document/11202657)

**Linhua Zou**, Dongqing Li, Cheng Jiang, Yu Wang, Hong Zhao\*

*IEEE Transactions on Fuzzy Systems, 2026, 34(1): 41-52.*

[\[Paper\]](papers/2026-TSF-FCGNN.pdf) [\[Code\]](https://github.com/Zlh111111/FCGNN)

  </div>
</div>

<div class='paper-box' id="fsake">
  <div class='paper-box-image'>
    <div>
      <div class="badge">ESWA 2025</div>
      <img src='images/2025-ESWA-FSAKE.png' alt="FSAKE" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](https://www.sciencedirect.com/science/article/pii/S0957417425014903)

**Linhua Zou**, Jie Jin, Dongqing Li, Hong Zhao\*

*Expert Systems with Applications, 2025, 285: 127868.*

[\[Paper\]](papers/2025-ESWA-FSAKE.pdf) [\[Code\]](https://github.com/Zlh111111/FSAKE)

  </div>
</div>

<div class='paper-box' id="macf">
  <div class='paper-box-image'>
    <div>
      <div class="badge">INS 2025</div>
      <img src='images/2025-INS-MACF.png' alt="MACF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](https://doi.org/10.1016/j.ins.2025.122209)

Zhiping Wu, Dongqing Li, **Linhua Zou**, Hong Zhao\*

*Information Sciences, 2025, 714: 122209.*

[\[Paper\]](papers/2025-INS-MACF.pdf) [\[Code\]](https://github.com/Zlh111111/MACF)

  </div>
</div>

<div class='paper-box' id="fspdf">
  <div class='paper-box-image'>
    <div>
      <div class="badge">KBS 2025</div>
      <img src='images/2025-KBS-FSPDF.png' alt="FSPDF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](https://doi.org/10.1016/j.knosys.2025.113389)

Dongqing Li, Jie Jin, **Linhua Zou**, Hong Zhao\*

*Knowledge-Based Systems, 2025, 317: 113389.*

[\[Paper\]](papers/2025-KBS-FSPDF.pdf) [\[Code\]](https://github.com/Zlh111111/FSPDF)

  </div>
</div>

<div class='paper-box' id="crapf">
  <div class='paper-box-image'>
    <div>
      <div class="badge">自动化学报 2025</div>
      <img src='images/2025-AAS-CRAPF.png' alt="CRAPF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[基于自适应原型特征类矫正的小样本学习方法](https://doi.org/10.16383/j.aas.c240312)

Hong Zhao, Yangqing Zhong, Jie Jin, **Linhua Zou**

*自动化学报, 2025, 51(02): 475-484.*

[\[Paper\]](papers/2025-自动化学报-CRAPF.pdf)

  </div>
</div>

# 📖 Educations

- *2026.09 - now*, PhD student, School of Automation, Central South University, China.
- *2023.09 - 2026.06*, Master, School of Computer Science, Minnan Normal University, China.
- *2019.09 - 2023.06*, Undergraduate, School of Computer Science, Minnan Normal University, China.

# 🎖 Honors and Awards

- *2025.10* National Scholarship for Graduate Students (China)
- *2023.12* Third Prize, Huawei Cup – 20th China Graduate Mathematical Modeling Competition



# 🌍 Visitors

{% include visitor_map.html %}


  

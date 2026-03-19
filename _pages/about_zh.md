---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div style="text-align: right; margin-bottom: 1em;">
  <a href="/">English</a> / <strong>中文</strong>
</div>

<span class='anchor' id='about-me'></span>

# 🧑 关于我

我目前为中南大学自动化学院博士研究生，师从 [王赟](https://faculty.csu.edu.cn/wangyun1/zh_CN/index.htm) 教授，主要从事极值回归建模相关研究。  
我本科毕业于闽南师范大学计算机科学与技术学院，并在该校继续攻读硕士学位，师从 [赵宏](https://fhqxa.github.io//) 教授。

我的研究兴趣包括 **计算机视觉（CV）** 和 **时间序列预测（TSF）**。当前研究主要聚焦于以下方向：

- **极值回归建模**
- **小样本学习（FSL）**
- **图神经网络（GNNs）**

如有学术合作意向，欢迎通过邮箱与我联系：  
[linhuazou00@163.com](mailto:linhuazou00@163.com)

# 📝 学术服务

- *Expert Systems with Applications (ESWA)* 审稿人
- *Pattern Recognition (PR)* 审稿人

# 🔥 新闻动态

- *2025.10*: &nbsp;🎉 论文 “[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](#fcgnn)” 被 *IEEE Transactions on Fuzzy Systems (TFS)* 接收。 
- *2025.04*: &nbsp;🎉 论文 “[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](#fsake)” 被 *Expert Systems with Applications (ESWA)* 接收。
- *2025.04*: &nbsp;🎉 论文 “[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](#macf)” 被 *Information Sciences (INS)* 接收。
- *2025.02*: &nbsp;🎉 论文 “[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](#fspdf)” 被 *Knowledge-Based Systems (KBS)* 接收。
- *2024.08*: &nbsp;🎉 论文 “[基于自适应原型特征类矫正的小样本学习方法](#crapf)” 被 *自动化学报 (ACTA AUTOMATICA SINICA, AAS)* 接收。

# 📝 论文发表

<div class='paper-box' id="fcgnn">
  <div class='paper-box-image'>
    <div>
      <div class="badge">TFS 2026</div>
      <img src='/images/2026-TSF-FCGNN.png' alt="FCGNN" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](https://ieeexplore.ieee.org/document/11202657)

**Linhua Zou**, Dongqing Li, Cheng Jiang, Yu Wang, Hong Zhao\*

*IEEE Transactions on Fuzzy Systems, 2026, 34(1): 41-52.*

[\[论文\]](/papers/2026-TSF-FCGNN.pdf) [\[代码\]](https://github.com/Zlh111111/FCGNN)

  </div>
</div>

<div class='paper-box' id="fsake">
  <div class='paper-box-image'>
    <div>
      <div class="badge">ESWA 2025</div>
      <img src='/images/2025-ESWA-FSAKE.png' alt="FSAKE" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](https://www.sciencedirect.com/science/article/pii/S0957417425014903)

**Linhua Zou**, Jie Jin, Dongqing Li, Hong Zhao\*

*Expert Systems with Applications, 2025, 285: 127868.*

[\[论文\]](/papers/2025-ESWA-FSAKE.pdf) [\[代码\]](https://github.com/Zlh111111/FSAKE)

  </div>
</div>

<div class='paper-box' id="macf">
  <div class='paper-box-image'>
    <div>
      <div class="badge">INS 2025</div>
      <img src='/images/2025-INS-MACF.png' alt="MACF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](https://doi.org/10.1016/j.ins.2025.122209)

Zhiping Wu, Dongqing Li, **Linhua Zou**, Hong Zhao\*

*Information Sciences, 2025, 714: 122209.*

[\[论文\]](/papers/2025-INS-MACF.pdf) [\[代码\]](https://github.com/Zlh111111/MACF)

  </div>
</div>

<div class='paper-box' id="fspdf">
  <div class='paper-box-image'>
    <div>
      <div class="badge">KBS 2025</div>
      <img src='/images/2025-KBS-FSPDF.png' alt="FSPDF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](https://doi.org/10.1016/j.knosys.2025.113389)

Dongqing Li, Jie Jin, **Linhua Zou**, Hong Zhao\*

*Knowledge-Based Systems, 2025, 317: 113389.*

[\[论文\]](/papers/2025-KBS-FSPDF.pdf) [\[代码\]](https://github.com/Zlh111111/FSPDF)

  </div>
</div>

<div class='paper-box' id="crapf">
  <div class='paper-box-image'>
    <div>
      <div class="badge">自动化学报 2025</div>
      <img src='/images/2025-AAS-CRAPF.png' alt="CRAPF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[基于自适应原型特征类矫正的小样本学习方法](https://doi.org/10.16383/j.aas.c240312)

Hong Zhao, Yangqing Zhong, Jie Jin, **Linhua Zou**

*自动化学报, 2025, 51(02): 475-484.*

[\[论文\]](/papers/2025-自动化学报-CRAPF.pdf)

  </div>
</div>

# 📖 教育经历

- *2026.09 - 至今*，博士研究生，中南大学自动化学院，中国。
- *2023.09 - 2026.06*，硕士，闽南师范大学计算机科学与技术学院，中国。
- *2019.09 - 2023.06*，本科，闽南师范大学计算机科学与技术学院，中国。

# 🎖 荣誉奖励

- *2025.10* 研究生国家奖学金
- *2023.12* “华为杯”第二十届中国研究生数学建模竞赛国家三等奖

# 🌍 访客

{% include visitor_map.html %}

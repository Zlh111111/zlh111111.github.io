---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /zh/
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- Language switch buttons -->
<div class="lang-switch" style="text-align:right; margin-bottom: 1em;">
  <span id="btn-en" class="lang-switch__item is-active" onclick="switchLang('en')" style="cursor:pointer;">English</span>
  <span id="btn-zh" class="lang-switch__item" onclick="switchLang('zh')" style="cursor:pointer;">中文</span>
</div>

<!-- ==================== English Content ==================== -->
<div id="content-en">

<span class="anchor" id="about-me"></span>

## 🤵🏻 About Me

I am currently pursuing a Ph.D. at the School of Automation at Central South University, where I am conducting research on extreme regression modeling under the supervision of [Yun Wang](https://faculty.csu.edu.cn/wangyun1/zh_CN/index.htm). I graduated from the School of Computer Science at Minnan Normal University with a bachelor's degree and earned my master's degree from the same school under the supervision of [Hong Zhao](https://fhqxa.github.io//). 

My research interests include **Computer Vision (CV)** and **Time Series Forecasting (TSF)**. My current research focuses on the following topics:
- **Extreme Regression Modeling**
- **Few-Shot Learning (FSL)**
- **Graph Neural Networks (GNNs)**

If you are seeking any form of academic cooperation, please feel free to email me at [linhuazou00@163.com](mailto:linhuazou00@163.com) / [zlh1836065471@163.com](mailto:zlh1836065471@163.com).

## 📝 Academic Service
- Reviewer for *Pattern Recognition (PR)*
- Reviewer for *Neural Networks (NN)*
- Reviewer for *Knowledge-Based Systems (KBS)*
- Reviewer for *Expert Systems with Applications (ESWA)*
- Reviewer for *Computer Vision and Image Understanding (CVIU)*

## 🔥 News
- *2025.10*: &nbsp;🎉 Our paper "[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](#fcgnn)" is accepted by *IEEE Transactions on Fuzzy Systems (TFS)*. 
- *2025.04*: &nbsp;🎉 Our paper "[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](#fsake)" is accepted by *Expert Systems with Applications (ESWA)*.
- *2025.04*: &nbsp;🎉 Our paper "[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](#macf)" is accepted by *Information Sciences (INS)*.
- *2025.02*: &nbsp;🎉 Our paper "[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](#fspdf)" is accepted by *Knowledge-Based Systems (KBS)*.
- *2024.08*: &nbsp;🎉 Our paper "[基于自适应原型特征类矫正的小样本学习方法](#crapf)" is accepted by *自动化学报 (ACTA AUTOMATICA SINICA, AAS)*.

## 📝 Publications

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

## 📖 Educations

- *2026.09 - now*, PhD student, School of Automation, Central South University, China.
- *2023.09 - 2026.06*, Master, School of Computer Science, Minnan Normal University, China.
- *2019.09 - 2023.06*, Undergraduate, School of Computer Science, Minnan Normal University, China.

## 🎖 Honors and Awards

- *2025.10* National Scholarship for Graduate Students (China)
- *2023.12* Third Prize, Huawei Cup – 20th China Graduate Mathematical Modeling Competition

</div>
<!-- ==================== End English Content ==================== -->

<!-- ==================== Chinese Content ==================== -->
<div id="content-zh" style="display:none">

<span class='anchor' id='about-me-zh'></span>

## 🤵🏻 关于我

我目前已拟录取为中南大学自动化学院博士研究生，主要从事极端回归建模相关研究，导师为[汪运](https://faculty.csu.edu.cn/wangyun1/zh_CN/index.htm)教授。我本科毕业于闽南师范大学计算机学院，并在该校继续攻读硕士学位，师从[赵红](https://fhqxa.github.io//)教授。

我的研究兴趣包括**计算机视觉 (Computer Vision, CV)**和**时间序列预测 (Time Series Forecasting, TSF）**。当前研究主要聚焦于以下方向：
- **极端回归建模 (Extreme Regression Modeling)**
- **小样本学习 (Few-Shot Learning, FSL)**
- **图神经网络 (Graph Neural Networks, GNNs)**

如有任何学术合作意向，欢迎通过邮箱与我联系：[linhuazou00@163.com](mailto:linhuazou00@163.com) / [zlh1836065471@163.com](mailto:zlh1836065471@163.com).

<span class='anchor' id='academic-service-zh'></span>
## 📝 学术服务

- *Pattern Recognition (PR)* 审稿人
- *Neural Networks (NN)* 审稿人
- *Knowledge-Based Systems (KBS)* 审稿人
- *Expert Systems with Applications (ESWA)* 审稿人
- *Computer Vision and Image Understanding (CVIU)* 审稿人

<span class='anchor' id='news-zh'></span>
## 🔥 新闻动态

- *2025.10*: &nbsp;🎉 论文 "[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](#fcgnn-zh)" 被 *IEEE Transactions on Fuzzy Systems (TFS)* 接收。
- *2025.04*: &nbsp;🎉 论文 "[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](#fsake-zh)" 被 *Expert Systems with Applications (ESWA)* 接收。
- *2025.04*: &nbsp;🎉 论文 "[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](#macf-zh)" 被 *Information Sciences (INS)* 接收。
- *2025.02*: &nbsp;🎉 论文 "[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](#fspdf-zh)" 被 *Knowledge-Based Systems (KBS)* 接收。
- *2024.08*: &nbsp;🎉 论文 "[基于自适应原型特征类矫正的小样本学习方法](#crapf-zh)" 被 *自动化学报 (Acta Automatica Sinica, AAS)* 接收。

<span class='anchor' id='publications-zh'></span>
## 📝 论文发表

<div class='paper-box' id="fcgnn-zh">
  <div class='paper-box-image'>
    <div>
      <div class="badge">TFS 2026</div>
      <img src='/images/2026-TSF-FCGNN.png' alt="FCGNN" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FCGNN: Fuzzy Cognitive Graph Neural Networks with Concept Evolution for Few-Shot Learning](https://ieeexplore.ieee.org/document/11202657)

**邹林华**，李冬卿，蒋承熹，王煜，赵红\*

*IEEE Transactions on Fuzzy Systems, 2026, 34(1): 41-52.*

[\[论文\]](/papers/2026-TSF-FCGNN.pdf) [\[代码\]](https://github.com/Zlh111111/FCGNN)

  </div>
</div>

<div class='paper-box' id="fsake-zh">
  <div class='paper-box-image'>
    <div>
      <div class="badge">ESWA 2025</div>
      <img src='/images/2025-ESWA-FSAKE.png' alt="FSAKE" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FSAKE: Few-Shot Graph Learning via Adaptive Neighbor Class Knowledge Embedding](https://www.sciencedirect.com/science/article/pii/S0957417425014903)

**邹林华**，金杰，李冬卿，赵红\*

*Expert Systems with Applications, 2025, 285: 127868.*

[\[论文\]](/papers/2025-ESWA-FSAKE.pdf) [\[代码\]](https://github.com/Zlh111111/FSAKE)

  </div>
</div>

<div class='paper-box' id="macf-zh">
  <div class='paper-box-image'>
    <div>
      <div class="badge">INS 2025</div>
      <img src='/images/2025-INS-MACF.png' alt="MACF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Multi-Granularity Awareness via Cross Fusion for Few-Shot Learning](https://doi.org/10.1016/j.ins.2025.122209)

吴志平，李冬卿，**邹林华**，赵红\*

*Information Sciences, 2025, 714: 122209.*

[\[论文\]](/papers/2025-INS-MACF.pdf) [\[代码\]](https://github.com/Zlh111111/MACF)

  </div>
</div>

<div class='paper-box' id="fspdf-zh">
  <div class='paper-box-image'>
    <div>
      <div class="badge">KBS 2025</div>
      <img src='/images/2025-KBS-FSPDF.png' alt="FSPDF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[FSPDF: Few-Shot Learning with Progressive Dual-Domain Feature Fusion via Self-Supervised Learning](https://doi.org/10.1016/j.knosys.2025.113389)

李冬卿，金杰，**邹林华**，赵红\*

*Knowledge-Based Systems, 2025, 317: 113389.*

[\[论文\]](/papers/2025-KBS-FSPDF.pdf) [\[代码\]](https://github.com/Zlh111111/FSPDF)

  </div>
</div>

<div class='paper-box' id="crapf-zh">
  <div class='paper-box-image'>
    <div>
      <div class="badge">自动化学报 2025</div>
      <img src='/images/2025-AAS-CRAPF.png' alt="CRAPF" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[基于自适应原型特征类矫正的小样本学习方法](https://doi.org/10.16383/j.aas.c240312)

赵红\*，钟杨清，金杰，**邹林华**

*自动化学报, 2025, 51(02): 475-484.*

[\[论文\]](/papers/2025-自动化学报-CRAPF.pdf)

  </div>
</div>

<span class='anchor' id='educations-zh'></span>
## 📖 教育经历

- *2026.09 - 至今*，博士在读，中南大学自动化学院
- *2023.09 - 2026.06*，硕士，闽南师范大学计算机学院
- *2019.09 - 2023.06*，本科，闽南师范大学计算机学院

<span class='anchor' id='honors-awards-zh'></span>
## 🎖 荣誉奖励

- *2025.10* 研究生国家奖学金
- *2023.12* "华为杯"第二十届中国研究生数学建模竞赛国家三等奖

</div>
<!-- ==================== End Chinese Content ==================== -->

# 🌍 Visitors / 访客

{% include visitor_map.html %}

<script>
function switchLang(lang) {
  document.getElementById('content-en').style.display = lang === 'en' ? '' : 'none';
  document.getElementById('content-zh').style.display = lang === 'zh' ? '' : 'none';
  document.getElementById('btn-en').classList.toggle('is-active', lang === 'en');
  document.getElementById('btn-zh').classList.toggle('is-active', lang === 'zh');
  localStorage.setItem('preferred-lang', lang);
}
(function () {
  var lang = localStorage.getItem('preferred-lang') || 'en';
  if (lang !== 'en') switchLang(lang);
})();
</script>

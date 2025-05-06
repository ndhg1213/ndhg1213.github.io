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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🌴 About Me

I am a master's student at Harbin Institute of Technology (Shenzhen), under the supervision of [Prof. Bin Chen](https://faculty.hitsz.edu.cn/BinChen). I obtained my B.Eng in Computer Science and Technology at Harbin Institute of Technology (Shenzhen) in 2024.

My research interests lie in machine learning and computer vision, especially in AI security and efficient AI.


<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
<meta charset="UTF-8">
<title>News</title>
<style>
  .news-container {
    height: 150px;
    overflow: auto;
  }
  .news-item {
    display: flex;
  }
  .news-date {
    min-width: 100px; /* 根据你的情况调整宽度 */
  }
  .news-content {
    flex-grow: 1;
  }
</style>
</head>
<body>

<h1>🔥 News</h1>
<div class="news-container">
  <ul>
    <li class="news-item">
      <div class="news-date">Feb 2025</div>
      <div class="news-content"><a href="https://arxiv.org/abs/2406.05704">H-PD</a> is accepted by CVPR2025. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Jan 2025</div>
      <div class="news-content"><a href="https://arxiv.org/abs/2412.09945">CMIDD</a> is accepted by ICLR2025. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Dec 2024</div>
      <div class="news-content">The paper of <a href="https://arxiv.org/abs/2412.09959">DDPS</a> is released. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Dec 2024</div>
      <div class="news-content">The paper of <a href="https://arxiv.org/abs/2412.09945">CMIDD</a> is released. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Jun 2024</div>
      <div class="news-content">The paper of <a href="https://arxiv.org/abs/2406.05704">H-PD</a> is released. </div>
    </li>
    <!-- <li class="news-item">
      <div class="news-date">Dec 2023</div>
      <div class="news-content">
        Started to cooperate with <a href="https://mayuelala.github.io/">Yue Ma</a>.
      </div>
    </li> -->
    <li class="news-item">
      <div class="news-date">Jul 2023</div>
      <div class="news-content">
        Started internship in Professor Bin Chen’s research group.
      </div>
    </li>
  </ul>
</div>

</body>
</html>

<!-- <h1>🔥 News</h1>
<div style="height: 150px; overflow: auto;">
<ul>

Mar 2024 &nbsp;&nbsp;&nbsp;&nbsp;Submitted one paper to ECCV2024.

Dec 2023 &nbsp;&nbsp;&nbsp;&nbsp;Started to cooperate with
<a href="https://mayuelala.github.io/">Yue Ma</a>.

Aug 2023 &nbsp;&nbsp;&nbsp;&nbsp;Started to cooperate with <a href="http://kailigo.github.io/">Dr. Kai Li</a>.

Jul 2023 &nbsp;&nbsp;&nbsp;&nbsp;Awarded as an outstanding camper in Tsinghua University Summer Camp.

Apr 202 &nbsp;&nbsp;&nbsp;&nbsp;Started internship in Professor Li Xiu’s research group.

</ul>
</div> -->

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='..\images\DDPS-title-case.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4 > <strong>Efficient Dataset Distillation via Diffusion-Driven Patch Selection for Improved Generalization</strong></font>

**<u>Xinhao Zhong</u>**, Shuoyang Sun, Xulin Gu, Zhaoyang Xu, Yaowei Wang, Min Zhang, Bin Chen $^{\dagger}$

*ArXiv preprint arXiv:2412.09959*
<!-- *arXiv preprint arXiv:2412.01197 (2024)* -->
<!-- [[**Project Page**](https://multibooth.github.io/)] -->
<!-- [[**Paper**](https://arxiv.org/abs/2404.14239)] -->
<!-- [[**Code**](https://github.com/chenyangzhu1/MultiBooth)] -->

<a href='https://arxiv.org/abs/2412.09959'><img src='https://img.shields.io/badge/ArXiv-2412.09959-red'></a>
<!-- <a href='https://InstantSwap.github.io/'><img src='https://img.shields.io/badge/Project-Page-Green'></a> -->
<!-- ![GitHub Repo stars](https://img.shields.io/github/stars/chenyangzhu1/InstantSwap) -->


We propose a novel framework orthogonal to existing diffusion-based dataset distillation methods, leveraging diffusion models for selection rather than generation.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='..\images\H_PD-title-case.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4 > <strong>Hierarchical Features Matter: A Deep Exploration of Progressive Parameterization Method for Dataset Distillation</strong></font>

**<u>Xinhao Zhong</u> $^{\*}$**, Hao Fang $^{\*}$, Bin Chen $^{\dagger}$, Xulin Gu, Meikang Qiu, Shuhan Qi, Shu-Tao Xia

*In The IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2025*
<!-- [[**Project Page**](https://multibooth.github.io/)] -->
<!-- [[**Paper**](https://arxiv.org/abs/2404.14239)] -->
<!-- [[**Code**](https://github.com/chenyangzhu1/MultiBooth)] -->

<a href='https://arxiv.org/abs/2406.05704'><img src='https://img.shields.io/badge/ArXiv-2406.05704-red'></a>
<a href='https://github.com/ndhg1213/H-PD'><img src='https://img.shields.io/badge/Project-Page-Green'></a>
<!-- ![GitHub Repo stars](https://img.shields.io/github/stars/chenyangzhu1/MultiBooth?style=social&link=https%3A%2F%2Fgithub.com%2Fchenyangzhu1%2FMultiBooth) -->

we propose a novel parameterization method dubbed Hierarchical Parameterization Distillation (H-PD), to systematically explore hierarchical feature within provided feature space (e.g., layers within pre-trained generative adversarial networks).

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='..\images\CMIDD-title-case.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4 > <strong>Going Beyond Feature Similarity: Effective Dataset distillation based on Class-aware Conditional Mutual Information</strong></font>

**<u>Xinhao Zhong</u>**, Bin Chen $^{\dagger}$, Hao Fang, Xulin Gu, Shu-Tao Xia, En-Hui Yang

*In The International Conference on Learning Representations (ICLR), 2025*
<!-- [[**Project Page**](https://multibooth.github.io/)] -->
<!-- [[**Paper**](https://arxiv.org/abs/2404.14239)] -->
<!-- [[**Code**](https://github.com/chenyangzhu1/MultiBooth)] -->

<a href='https://arxiv.org/abs/2412.09945'><img src='https://img.shields.io/badge/ArXiv-2412.09945-red'></a>
<a href='https://github.com/ndhg1213/CMIDD'><img src='https://img.shields.io/badge/Project-Page-Green'></a>
<!-- ![GitHub Repo stars](https://img.shields.io/github/stars/chenyangzhu1/MultiBooth?style=social&link=https%3A%2F%2Fgithub.com%2Fchenyangzhu1%2FMultiBooth) -->

we introduce conditional mutual information (CMI) into dataset distillation to assess the class-aware complexity of a dataset and propose a novel method by minimizing CMI to constrain the complexity of synthetic datasets. 

</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations

- _2024.09 - Future_, Tsinghua University, Master of Engineering in Electronic Information

- _2020.09 - 2024.6_, Harbin Institute of Technology (Shenzhen), Bachelor of Computer Science and Technology -->
<!-- - *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

- _2023.07 - Now, Professor Bin Chen’s [research group](https://faculty.hitsz.edu.cn/BinChen) at Harbin Institute of Technology (Shenzhen).

---

<!-- <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=368bdc&w=350&t=tt&d=Bet_ACSX3N0Q4N0Qg5FkZONno2ukkSvQt3F9rBotRSc&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script> -->

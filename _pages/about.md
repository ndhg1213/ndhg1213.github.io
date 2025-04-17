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
  <!-- <li class="news-item">
      <div class="news-date">Jan 2025</div>
      <div class="news-content"><a href="https://instantswap.github.io/">InstantSwap</a> is accepted by ICLR2025. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Dec 2024</div>
      <div class="news-content"><a href="https://multibooth.github.io/">MultiBooth</a> is accepted by AAAI2025. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Dec 2024</div>
      <div class="news-content">Excited to release <a href="https://instantswap.github.io/">InstantSwap</a>, an efficient customized concept swapping method across sharp shape differences. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Apr 2024</div>
      <div class="news-content">Excited to release <a href="https://multibooth.github.io/">MultiBooth</a>, a novel and efficient multi-concept customization method. </div>
    </li>
    <li class="news-item">
      <div class="news-date">Dec 2023</div>
      <div class="news-content">
        Started to cooperate with <a href="https://mayuelala.github.io/">Yue Ma</a>.
      </div>
    </li>
    <li class="news-item">
      <div class="news-date">Aug 2023</div>
      <div class="news-content">
        Started to cooperate with <a href="http://kailigo.github.io/">Dr. Kai Li</a>.
      </div>
    </li>
    <li class="news-item">
      <div class="news-date">Jul 2023</div>
      <div class="news-content">
        Awarded as an outstanding camper in Tsinghua University Summer Camp.
      </div>
    </li>
    <li class="news-item">
      <div class="news-date">Apr 2023</div>
      <div class="news-content">
        Started internship in Professor Li Xiu’s research group.
      </div>
    </li> -->
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='..\images\InstantSwap-title-case.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4 > <strong>InstantSwap: Fast Customized Concept Swapping across Sharp Shape Differences</strong></font>

**<u>Chenyang Zhu</u> $^{\*}$**, Kai Li $^{\*,\dagger}$, Yue Ma $^{\*}$,  Longxiang Tang, Chengyu Fang, Chubin Chen, Qifeng Chen, Xiu Li $^{\dagger}$

*In International Conference on Learning Representations (ICLR), 2025*
<!-- *arXiv preprint arXiv:2412.01197 (2024)* -->
<!-- [[**Project Page**](https://multibooth.github.io/)] -->
<!-- [[**Paper**](https://arxiv.org/abs/2404.14239)] -->
<!-- [[**Code**](https://github.com/chenyangzhu1/MultiBooth)] -->

<a href='https://arxiv.org/abs/2412.01197'><img src='https://img.shields.io/badge/ArXiv-2412.01197-red'></a>
<a href='https://InstantSwap.github.io/'><img src='https://img.shields.io/badge/Project-Page-Green'></a>
![GitHub Repo stars](https://img.shields.io/github/stars/chenyangzhu1/InstantSwap)


A novel training-free customized concept swapping framework, which enables efficient concept swapping across sharp shape differences.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='..\images\MultiBooth-Title-case.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size=4 > <strong>MultiBooth: Towards Generating All Your Concepts in an Image from Text</strong></font>

**<u>Chenyang Zhu</u>**, Kai Li $^{\dagger}$, Yue Ma, Chunming He, Xiu Li $^{\dagger}$

*In The AAAI Conference on Artificial Intelligence (AAAI), 2025*
<!-- [[**Project Page**](https://multibooth.github.io/)] -->
<!-- [[**Paper**](https://arxiv.org/abs/2404.14239)] -->
<!-- [[**Code**](https://github.com/chenyangzhu1/MultiBooth)] -->

<a href='https://arxiv.org/abs/2404.14239'><img src='https://img.shields.io/badge/ArXiv-2404.14239-red'></a>
<a href='https://multibooth.github.io/'><img src='https://img.shields.io/badge/Project-Page-Green'></a>
![GitHub Repo stars](https://img.shields.io/github/stars/chenyangzhu1/MultiBooth?style=social&link=https%3A%2F%2Fgithub.com%2Fchenyangzhu1%2FMultiBooth)

A novel and efficient technique for multi-concept customization in image generation from text.

</div>
</div>
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div>  -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICMTEL 2022</div><img src='images/ICMTEL2022_DFMH.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Deep Factorized Multi-view Hashing for Image Retrieval

**Chenyang Zhu** $^{\dagger}$ , Wenjue He $^{\dagger}$ , Zheng Zhang $^{*}$ , **ICMTEL 2022**

[[**Paper**](https://link.springer.com/chapter/10.1007/978-3-031-18123-8_49)]
[[**Code**](https://github.com/chenyangzhu1/DFMH)]

- Combining deep semi non-negative matrix factorization and adaptive weight strategy, a novel algorithm called DFMH was proposed to solve the problem of multi-view image retrieval.
</div>
</div> -->

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

<!-- # 💻 Internships

- _2023.04 - 2024.8_, Professor Li Xiu’s [research group](https://thusigsclub.github.io/thu.github.io/index.html) at Tsinghua University, Shen Zhen, China. -->

---

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=368bdc&w=350&t=tt&d=Bet_ACSX3N0Q4N0Qg5FkZONno2ukkSvQt3F9rBotRSc&co=ffffff&cmo=3acc3a&cmn=ff5353&ct=808080'></script>

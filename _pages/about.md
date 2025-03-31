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

I am a Ph.D. candidate in Cartography and GIS with expected graduation in June 2025.

I graduated from Faculty of Geographical Science, Beijing Normal University (北京师范大学地理科学学部) with a bachelor’s degree and have been pursuing my Ph.D. degree at State Key Laboratory of Remote Sensing Science, Faculty of Geographical Science, Beijing Normal University (北京师范大学地理科学学部遥感科学国家重点实验室). My Ph.D. supervisor is [Wenquan Zhu (朱文泉)](https://geot.bnu.edu.cn/Public/htm/news/5/317.html).

My research interest includes carbon cycle modelling, quantitative remote sesning, digital image processing and climate change. 

I have published more than 10+ papers with <a href='https://scholar.google.com/citations?user=deR-tUkAAAAJ'>h-index = <strong><span id='total_cit'>5</span></strong></a> (<a href='https://scholar.google.com/citations?user=deR-tUkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AFM 2025</div><img src='images/AFM_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Causality constrained machine learning framework enhances spatiotemporal generalization and interpretability of ecosystem respiration estimation (*under 2nd round review*)

*Agricultural and Forest Meteorology* (SCI一区Top) <br>
**<u>Cenliang Zhao</u>**, Wenquan Zhu<sup>✉️</sup>, Liyuan Chen, Zhiying Xie

- A novel framework taking causal effects as soft constraints into machine learning models.
- This framework can enhance the interpretability and generalization ability of TER estimation. 
- Vegetation structure’ effects on TER and corresponding seasonal variations were quantitatively revealed. 
- We displayed the similarity and difference between two attribution tools (XGBoost, PCMCI) via visible ways for the first time.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CEE 2025</div><img src='images/CEE_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vegetation structure and phenology primarily shape the spatiotemporal pattern of ecosystem respiration](https://doi.org/10.1038/s43247-025-02240-1)

*Communications Earth & Environment* (SCI一区Top) <br>
**<u>Cenliang Zhao</u>**, Wenquan Zhu<sup>✉️</sup>

- We applied a causality constrained interpretable machine learning framework (PCMCI+, XGBoost, SHAP) and established a TER estimation model called “CIML-TER”.
- We generated high-accuracy global monthly [TER estimates](https://doi.org/10.6084/m9.figshare.27634203) at a spatial resolution of 0.05° during 2001-2020. 
- Substantial regional variability existed in the influence of different drivers on TER. Beyond hydrothermal factors (contributing ~44.15 ± 11.1% of global TER variability), biotic factors (25.91 ± 9.8%) and spatiotemporal variation factors (29.94 ± 7.2%) were also critical. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AFM 2023</div><img src='images/AFM_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An end-to-end satellite-based GPP estimation model devoid of meteorological and land cover data](https://doi.org/10.1016/j.agrformet.2023.109337)

*Agricultural and Forest Meteorology* (SCI一区Top) <br>
Wenquan Zhu, **<u>Cenliang Zhao<sup>✉️</sup></u>**, Zhiying Xie

- Build a new GPP estimation model (ETES) based entirely on remote sensing data.
- Design a continuous variable set (SCVTG) to replace PFTs in GPP estimation.
- ETES model improves the GPP estimation accuracy at multiple temporal scales. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">地理学报 2022</div><img src='images/DLXB_2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RS 2023</div><img src='images/RS_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Radiation-Regulated Dynamic Maximum Light Use Efficiency for Improving Gross Primary Productivity Estimation](https://doi.org/10.3390/rs15051176)

*Remote Sensing* (SCI二区) <br>
Zhiying Xie, **<u>Cenliang Zhao<sup>✉️</sup></u>**, Wenquan Zhu, Hui Zhang, Yongshuo H.Fu

- We proposed a PAR-regulated dynamic LUE<sub>max</sub> by considering the nonlinear response of vegetation photosynthesis to solar radiation.
- The PAR-LUE outperfromed the MODIS and EC-LUE models in GPP estimation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">地理学报 2022</div><img src='images/DLXB_2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[北极气候和陆地环境变化对第一产业影响研究进展](https://doi.org/10.11821/dlxb202211010)

*地理学报* (中文核心, EI) <br>
**<u>赵涔良</u>**, 朱文泉<sup>✉️</sup>, 郭红翔, 陈力原, 谢志英

- 本文针对北极地区的种植业、畜牧业、林业以及渔业四个第一产业部门，系统梳理了它们受到气候及陆地环境变化影响的类型与程度。
- 气候及陆地环境变化对北极第一产业生产活动同时存在着积极影响与消极影响，并且在不同产业部门具有各异的表现形式与比重。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">遥感学报 2021</div><img src='images/YGXB_2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[植被最大光能利用率的模拟方法对比评估](https://doi.org/10.11834/jrs.20211394)

*遥感学报* (中文核心, EI) <br>
**<u>赵涔良</u>**, 朱文泉<sup>✉️</sup>, 谢志英

- 因此，本文针对目前已有的3种典型动态LUE<sub>max</sub>参数模拟方法(基于叶绿素遥感指数、基于 LAI 季节调节因子、马尔可夫链蒙特卡洛模拟)进行了对比评估实验。
- 不同的动态LUE<sub>max</sub>参数在各植被类型上的季节性变化特征有明显差异，总体上呈现出单峰、“U” 型和水平波动3种特征。
- 马尔可夫链蒙特卡洛方法对LUE<sub>max</sub>参数有着较好的模拟效果，其在郁闭灌丛、落叶针叶林以及常绿阔叶林上对GPP估算的提升效果十分明显。
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
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

I am a Ph.D. candidate (1997-now) in Cartography and GIS with expected graduation in June 2025.

I graduated from Faculty of Geographical Science, Beijing Normal University (北京师范大学地理科学学部) with a bachelor’s degree and have been pursuing my Ph.D. degree at State Key Laboratory of Remote Sensing Science, Faculty of Geographical Science, Beijing Normal University (北京师范大学地理科学学部遥感科学国家重点实验室). My Ph.D. supervisor is [Wenquan Zhu (朱文泉)](https://geot.bnu.edu.cn/Public/htm/news/5/317.html).

My research interest includes carbon cycle modelling, quantitative remote sesning, digital image processing and climate change. 

I have published more than 20+ papers with <a href='https://scholar.google.com/citations?user=deR-tUkAAAAJ'>h-index = <strong><span id='total_cit'>5</span></strong></a>.

# 🔥 News
- *2025.03*: &nbsp;🎉 The global monthly TER product ([CIML-TER v1.0 2001-2020](https://doi.org/10.6084/m9.figshare.27634203)) was published, which does not rely on PFT classification data and overcomes the "artificial discontinuities" phenomenon. 
- *2024.10*: &nbsp;👍 We have completed an 24-month-long field experiment, acquiring a satellite-ground synchronous in-situ dataset (including radiation and vegetation parameters) of domestically developed satellites (GF-1/2/3/4/6/7, ZY1-02D/02E, HJ-2A/B).

# 💻 Skills
[![My Skills](https://skillicons.dev/icons?i=py,r,matlab,js,raspberrypi,linux,md)](https://skillicons.dev)
## Field Competencies
- **Geospatial Tools**: ArcGIS Pro, QGIS, ENVI, Google Earth Engine 
- **Data Collection**: RTK GPS surveying, UAV photogrammetry, LiDAR scanning, Spectrum measurements (ASD FS4/HH2, PSR1100F, OceanOptics, CE-312, CNR4, MR-60, SI-111), AOD measurements (CE-318)

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

- 本文针对目前已有的3种典型动态LUE<sub>max</sub>参数模拟方法(基于叶绿素遥感指数、基于 LAI 季节调节因子、马尔可夫链蒙特卡洛模拟)进行了对比评估实验。
- 不同的动态LUE<sub>max</sub>参数在各植被类型上的季节性变化特征有明显差异，总体上呈现出单峰、“U” 型和水平波动3种特征。
- 马尔可夫链蒙特卡洛方法对LUE<sub>max</sub>参数有着较好的模拟效果，其在郁闭灌丛、落叶针叶林以及常绿阔叶林上对GPP估算的提升效果十分明显。
</div>
</div>

- `TEE 2024`[Uncertainty analysis of intra-module environmental stress parameter design in light use efficiency-based gross primary productivity estimation models](https://doi.org/10.1177/2754124X241235545), **<u>Cenliang Zhao</u>**, Wenquan Zhu, *Transactions in Earth, Environment, and Sustainability*.
- `GIScience & RS 2024` [Remote sensing of terrestrial gross primary productivity: a review of advances in theoretical foundation, key parameters and methods](https://doi.org/10.1080/15481603.2024.2318846), Wenquan Zhu, Zhiying Xie, **<u>Cenliang Zhao</u>**, Zhoutao Zheng, Kun Qiao, Dailiang Peng, Yongshuo H.Fu, *GIScience & Remote Sensing*.
- `环境与健康杂志 2024` [基于微博数据的2011—2021年北京市花粉过敏暴发起止日期提取及变化分析](https://doi.org/10.16241/j.cnki.1001-5914.2024.02.007), 杨欣怡, 朱文泉, **<u>赵涔良</u>**, *环境与健康杂志*.
- `极地研究 2023` [北极气候和陆地环境变化对工业影响的研究进展](https://doi.org/10.13679/j.jdyj.20220404), 郭红翔, 朱文泉, **<u>赵涔良</u>**, 陈力原, 谢志英, *极地研究*.
- `RS 2022` [A Prediction Model for the Outbreak Date of Spring Pollen Allergy in Beijing Based on Satellite-Derived Phenological Characteristics of Vegetation Greenness](https://doi.org/10.3390/rs14225891), Xinyi Yang, Wenquan Zhu, **<u>Cenliang Zhao</u>**, *Remote Sensing*.
- `EJRS 2022` [Phenological piecewise modelling is more conducive than whole-season modelling to winter wheat yield estimation based on remote sensing data](https://doi.org/10.1080/22797254.2022.2073916), Xin Huang, Wenquan Zhu, **<u>Cenliang Zhao</u>**, Zhiying Xie, Hui Zhang, *European Journal of Remote Sensing*.
- `北京师范大学学报（自然科学版） 2021` [基于多源数据产品集成分类制作的青藏高原现状植被图](https://doi.org/10.12202/j.0476-0301.2021171), 张慧, **<u>赵涔良</u>**, 朱文泉.

## Others
- `ACCR 2025` [The freezing‒thawing index and permafrost extent in pan-Arctic experienced rapid changes following the global warming hiatus](https://doi.org/10.1016/j.accre.2025.02.010), Hongxiang Guo, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Liyuan Chen, *Advances in Climate Change Research*.
- `ACCR 2025` [Degradation of potential winter roads threatens vulnerable communities’ freight accessibility in the pan-Arctic region](https://doi.org/10.1016/j.accre.2025.02.006), Liyuan Chen, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Hongxiang Guo, *Advances in Climate Change Research*.
- `地理学报 2025` [青藏高原植被遥感精细识别方法研究](https://doi.org/10.11821/dlxb202501002), 张慧, 朱文泉, 史培军, 唐海萍, 何邦科, 刘若杨, 杨欣怡, **<u>赵涔良</u>**, *地理学报*
- `JAG 2024` [High-precision estimation of pan-Arctic soil surface temperature from MODIS LST by incorporating multiple environment factors and monthly-based modeling](https://doi.org/10.1016/j.jag.2024.104114), Hongxiang Guo, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Liyuan Chen, *International Journal of Applied Earth Observation and Geoinformation*.
- `生态学报 2024` [复杂地形区植被覆盖度遥感精细估算方法——以青藏高原山地区为例](https://doi.org/10.20103/j.stxb.202403260625), 何邦科, 朱文泉, 史培军, 张慧, 刘若杨, 杨欣怡,  **<u>赵涔良</u>**, *生态学报*.
- `JAG 2024` [A new feature extraction algorithm for measuring the spatial arrangement of texture Primitives: Distance coding diversity](https://doi.org/10.1016/j.jag.2024.103698), Wenquan Zhu, Xinyi Yang, Ruoyang Liu, **<u>Cenliang Zhao</u>**, *International Journal of Applied Earth Observation and Geoinformation*.
- `生态学报 2024` [青藏高原各主要植被类型特征及环境差异](https://doi.org/10.20103/j.stxb.202211163308), 张慧, 朱文泉, 史培军, **<u>赵涔良</u>**, 刘若杨, 唐海萍, 王静爱, 何邦科, *生态学报*.
- `地理科学进展 2023` [北极气候与环境变化对第三产业影响的研究进展及展望](https://doi.org/10.18306/dlkxjz.2023.11.011), 陈力原, 朱文泉, 效存德, 王世金, 吴通华, **<u>赵涔良</u>**, 郭红翔, *地理科学进展*.
- `地理学报 2023` [青藏高原植被产氧量及其对近地表大气氧含量的贡献率](https://doi.org/10.11821/dlxb202305006), 刘若杨, 史培军, 唐海萍, 王静爱, 赵涔良, 朱文泉, *地理学报*.
- `RS 2022` [Reconstruction of Vegetation Index Time Series Based on Self-Weighting Function Fitting from Curve Features](https://doi.org/10.3390/rs14092247), Wenquan Zhu, Bangke He, Zhiying Xie, **<u>Cenliang Zhao</u>**, Huimin Zhuang, *Remote Sensing*.
- `植物生态学报 2021` [气候变暖背景下青藏高原草本植物物候变化空间换时间预测](https://doi.org/10.17521/cjpe.2019.0308), 李雪莹 , 朱文泉, 李培先, 谢志英, 赵涔良, *植物生态学报*.

## Patent
- 朱文泉, 杨欣怡, 刘若杨, **<u>赵涔良</u>**. 一种面向单时相影像的潜在地表异常遥感探测器构建方法, 专利号: 2023113429156, 申请日: 2023-10-17.
- 朱文泉, 刘若杨, 杨欣怡, **<u>赵涔良</u>**. 一种测度图像空间有序性的距离编码多样性算法, 专利号: 2022116004543, 申请日: 2022-12-12.
- 朱文泉, 何邦科, 谢志英, **<u>赵涔良</u>**. 一种基于曲线特征加权的植被指数时序数据函数拟合重建方法, 专利号: ZL 202210004927.7, 授权公告日: 2022-04-15.
- 朱文泉, 詹培, **<u>赵涔良</u>**. 一种基于合成孔径雷达时序数据的水稻自动识别方法, 专利号: ZL 202010117995.5, 授权公告日: 2021-12-03.

# 🎖 Honors and Awards
- *2024.01* Academic Innovation Award of Beijing Normal University 
- *2023.12* Top Scholarship Award, Beijing Normal University (Postgraduate)
- *2018.12* Top Scholarship Award, Beijing Normal University (Undergraduate)
- *2017.11* The Excellent Award of 15th SuperMap GIS Contest (6th of final 10)
- *2012.12* Lixin Tang Scholarship (High school)

# 📖 Educations
- *2019.09 - 2025.06 (now)*, Cartography and GIS, State Key Laboratory of Remote Sensing Science, Faculty of Geographical Science, Beijing Normal University, Beijing (北京师范大学地理科学学部遥感科学国家重点实验室 地图学与地理信息系统)
- *2015.09 - 2019.06*, Resource and Environmental Science, Faculty of Geographical Science, Beijing Normal University, Beijing (北京师范大学地理科学学部 资源环境科学)
- *2012.09 - 2015.06*, Science, Chengdu Shishi High School, Chengdu (成都石室中学-文庙校区 理科)

# 🌏 Field Research & Experimentation
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 🏫 Working and Teaching Activities
- *2022.09 - 2023.12*, Teaching Assistant of [Remote Sensing Digital Image Processing](https://www.icourse163.org/course/BNU-1002335009) (国家精品课程), Faculty of Geographical Science, Beijing Normal University, Beijing, China
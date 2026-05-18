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

I am a postdoctoral researcher (born in 1997) at School of Geography and Planning, Sun Yat-sen University (中山大学 地理科学与规划学院), Guangzhou, Guangdong, China, collabrating with Prof. [Xing Li (李星)](https://gp.sysu.edu.cn/teacher/LiXing).

I graduated from Faculty of Geographical Science, Beijing Normal University (北京师范大学 地理科学学部) with a bachelor’s degree in Resources and Environmental Science. Then I received my Ph.D. degree in Cartography and Geography Information System at State Key Laboratory of Remote Sensing Science, Faculty of Geographical Science, Beijing Normal University (北京师范大学 地理科学学部 遥感科学国家重点实验室). My Ph.D. supervisor is Prof. [Wenquan Zhu (朱文泉)](https://geot.bnu.edu.cn/Public/htm/news/5/317.html).

My research interests include carbon cycle modelling, quantitative remote sesning, digital image processing and climate change feedbacks. 

I have published more than 20+ papers with <a href='https://scholar.google.com/citations?user=deR-tUkAAAAJ'>h-index = <strong><span id='total_cit'>8</span></strong></a>.

# 🔥 News
- *2025.05*: &nbsp;🎉 I got the Ph.D. degree in Cartography and Geography Information System. 
- *2025.04*: &nbsp;🎉 The global carborn cycle dataset ([ETES-GPP](https://doi.org/10.1016/j.agrformet.2023.109337) and [CIML-TER](https://doi.org/10.1038/s43247-025-02240-1), 0.05 degree, monthly) are officially online at [BNU dataset center](https://rsec.bnu.edu.cn/download/carbonCycle.html).
- *2023.10*: &nbsp;👍 We have completed an 13-month-long field experiment, acquiring a satellite-ground synchronous in-situ dataset (including radiation and vegetation parameters) of Chinese satellites (GF-1/2/3/4/6/7, ZY1-02D/02E, HJ-2A/B).

# 💻 Skills
[![My Skills](https://skillicons.dev/icons?i=py,r,matlab,js,raspberrypi,linux,md)](https://skillicons.dev)
- **Geospatial Tools**: ArcGIS Pro, QGIS, ENVI, Google Earth Engine 
- **Data Collection**: RTK GPS surveying, UAV photogrammetry, LiDAR scanning, Spectrum measurements (ASD FS4/HH2, PSR1100F, OceanOptics, CE-312, CNR4, MR-60, SI-111), AOD measurements (CE-318)
- **Language**: Putonghua Proficiency Test Level 2-A (普通话水平测试二甲), International English Language Testing System (IELTS 6.5, 2019), Japanese Language Proficiency Test (JLPT N2, 2018)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AFM 2025</div><img src='images/AFM_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Causality constrained machine learning framework enhances the reliability and spatiotemporal generalization in ecosystem respiration estimation](https://doi.org/10.1016/j.agrformet.2025.110718)

*Agricultural and Forest Meteorology* (中科院1区Top, JCR-Q1) <br>
**<u>Cenliang Zhao</u>**, Wenquan Zhu<sup>✉️</sup>, Liyuan Chen, Zhiying Xie

- A novel framework taking causal effects as soft constraints into machine learning models.
- Causality constraints can enhance the inference reliability of XGBoost algorithm. 
- Vegetation structure’ effects on TER and corresponding seasonal variations were quantitatively revealed.
- The similarity and difference between two attribution tools (XGBoost, PCMCI) were evaluated.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CEE 2025</div><img src='images/CEE_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vegetation structure and phenology primarily shape the spatiotemporal pattern of ecosystem respiration](https://doi.org/10.1038/s43247-025-02240-1)

*Communications Earth & Environment* (中科院1区Top, JCR-Q1) <br>
**<u>Cenliang Zhao</u>**, Wenquan Zhu<sup>✉️</sup>

- We applied a causality constrained interpretable machine learning framework (PCMCI+, XGBoost, SHAP) and established a TER estimation model called “CIML-TER”.
- We generated high-accuracy global monthly [TER estimates](https://doi.org/10.6084/m9.figshare.27634203) at a spatial resolution of 0.05° during 2001-2020. 
- Substantial regional variability existed in the influence of different drivers on TER. Beyond hydrothermal factors (contributing ~44.15 ± 11.1% of global TER variability), biotic factors (25.91 ± 9.8%) and spatiotemporal variation factors (29.94 ± 7.2%) were also critical. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AFM 2023</div><img src='images/AFM_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An end-to-end satellite-based GPP estimation model devoid of meteorological and land cover data](https://doi.org/10.1016/j.agrformet.2023.109337)

*Agricultural and Forest Meteorology* (中科院1区Top, JCR-Q1) <br>
Wenquan Zhu, **<u>Cenliang Zhao<sup>✉️</sup></u>**, Zhiying Xie

- Build a new GPP estimation model (ETES) based entirely on remote sensing data.
- Design a continuous variable set (SCVTG) to replace PFTs in GPP estimation.
- ETES model improves the GPP estimation accuracy at multiple temporal scales. 
</div>
</div>

- `TEE 2024`[Uncertainty analysis of intra-module environmental stress parameter design in light use efficiency-based gross primary productivity estimation models](https://doi.org/10.1177/2754124X241235545), **<u>Cenliang Zhao</u>**, Wenquan Zhu<sup>✉️</sup>, *Transactions in Earth, Environment, and Sustainability*.
- `RS 2023` [A Radiation-Regulated Dynamic Maximum Light Use Efficiency for Improving Gross Primary Productivity Estimation](https://doi.org/10.3390/rs15051176), Zhiying Xie, **<u>Cenliang Zhao<sup>✉️</sup></u>**, Wenquan Zhu, Hui Zhang, Yongshuo H.Fu
- `地理学报 2022` [北极气候和陆地环境变化对第一产业影响研究进展](https://doi.org/10.11821/dlxb202211010), **<u>赵涔良</u>**, 朱文泉<sup>✉️</sup>, 郭红翔, 陈力原, 谢志英
- `遥感学报 2021` [植被最大光能利用率的模拟方法对比评估](https://doi.org/10.11834/jrs.20211394), **<u>赵涔良</u>**, 朱文泉<sup>✉️</sup>, 郭红翔, 陈力原, 谢志英

## As main co-author
- `RSE 2025` [A novel index for directly indicating fractional vegetation cover based on spectral differences between vegetation and soil](https://doi.org/10.1016/j.rse.2025.115056), Bangke He, Wenquan Zhu, **<u>Cenliang Zhao</u>**, Zhiying Xie, Huimin Zhuang, *Remote Sensing of Environment*.
- `GIScience & RS 2024` [Remote sensing of terrestrial gross primary productivity: a review of advances in theoretical foundation, key parameters and methods](https://doi.org/10.1080/15481603.2024.2318846), Wenquan Zhu, Zhiying Xie, **<u>Cenliang Zhao</u>**, Zhoutao Zheng, Kun Qiao, Dailiang Peng, Yongshuo H.Fu, *GIScience & Remote Sensing*.
- `环境与健康杂志 2024` [基于微博数据的2011—2021年北京市花粉过敏暴发起止日期提取及变化分析](https://doi.org/10.16241/j.cnki.1001-5914.2024.02.007), 杨欣怡, 朱文泉, **<u>赵涔良</u>**, *环境与健康杂志*.
- `极地研究 2023` [北极气候和陆地环境变化对工业影响的研究进展](https://doi.org/10.13679/j.jdyj.20220404), 郭红翔, 朱文泉, **<u>赵涔良</u>**, 陈力原, 谢志英, *极地研究*.
- `RS 2022` [A Prediction Model for the Outbreak Date of Spring Pollen Allergy in Beijing Based on Satellite-Derived Phenological Characteristics of Vegetation Greenness](https://doi.org/10.3390/rs14225891), Xinyi Yang, Wenquan Zhu, **<u>Cenliang Zhao</u>**, *Remote Sensing*.
- `EJRS 2022` [Phenological piecewise modelling is more conducive than whole-season modelling to winter wheat yield estimation based on remote sensing data](https://doi.org/10.1080/22797254.2022.2073916), Xin Huang, Wenquan Zhu, **<u>Cenliang Zhao</u>**, Zhiying Xie, Hui Zhang, *European Journal of Remote Sensing*.
- `北京师范大学学报（自然科学版） 2021` [基于多源数据产品集成分类制作的青藏高原现状植被图](https://doi.org/10.12202/j.0476-0301.2021171), 张慧, **<u>赵涔良</u>**, 朱文泉.

## Other publications
- `JAG 2025` [MSFDmap: A novel scheme to map monthly soil freeze depth in the pan-Arctic considering spatiotemporal heterogeneity in heat transfer capability](https://doi.org/10.1016/j.jag.2025.104820), Liyuan Chen, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Hongxiang Guo, *International Journal of Applied Earth Observation and Geoinformation*.
- `ISPRS 2025` [An automated method for estimating fractional vegetation cover from camera-based field measurements: Saturation-adaptive threshold for ExG (SATE)](https://doi.org/10.1016/j.isprsjprs.2025.08.017), Xuemiao Ye, Wenquan Zhu, Ruoyang Liu, Bangke He, Xinyi Yang, **<u>Cenliang Zhao</u>**, *ISPRS Journal of Photogrammetry and Remote Sensing*.
- `ACCRE 2025` [The freezing‒thawing index and permafrost extent in pan-Arctic experienced rapid changes following the global warming hiatus](https://doi.org/10.1016/j.accre.2025.02.010), Hongxiang Guo, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Liyuan Chen, *Advances in Climate Change Research*.
- `ACCRE 2025` [Degradation of potential winter roads threatens vulnerable communities’ freight accessibility in the pan-Arctic region](https://doi.org/10.1016/j.accre.2025.02.006), Liyuan Chen, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Hongxiang Guo, *Advances in Climate Change Research*.
- `地理学报 2025` [青藏高原植被遥感精细识别方法研究](https://doi.org/10.11821/dlxb202501002), 张慧, 朱文泉, 史培军, 唐海萍, 何邦科, 刘若杨, 杨欣怡, **<u>赵涔良</u>**, *地理学报*
- `JAG 2024` [High-precision estimation of pan-Arctic soil surface temperature from MODIS LST by incorporating multiple environment factors and monthly-based modeling](https://doi.org/10.1016/j.jag.2024.104114), Hongxiang Guo, Wenquan Zhu, Cunde Xiao, **<u>Cenliang Zhao</u>**, Liyuan Chen, *International Journal of Applied Earth Observation and Geoinformation*.
- `生态学报 2024` [复杂地形区植被覆盖度遥感精细估算方法——以青藏高原山地区为例](https://doi.org/10.20103/j.stxb.202403260625), 何邦科, 朱文泉, 史培军, 张慧, 刘若杨, 杨欣怡,  **<u>赵涔良</u>**, *生态学报*.
- `JAG 2024` [A new feature extraction algorithm for measuring the spatial arrangement of texture Primitives: Distance coding diversity](https://doi.org/10.1016/j.jag.2024.103698), Wenquan Zhu, Xinyi Yang, Ruoyang Liu, **<u>Cenliang Zhao</u>**, *International Journal of Applied Earth Observation and Geoinformation*.
- `生态学报 2024` [青藏高原各主要植被类型特征及环境差异](https://doi.org/10.20103/j.stxb.202211163308), 张慧, 朱文泉, 史培军, **<u>赵涔良</u>**, 刘若杨, 唐海萍, 王静爱, 何邦科, *生态学报*.
- `地理科学进展 2023` [北极气候与环境变化对第三产业影响的研究进展及展望](https://doi.org/10.18306/dlkxjz.2023.11.011), 陈力原, 朱文泉, 效存德, 王世金, 吴通华, **<u>赵涔良</u>**, 郭红翔, *地理科学进展*.
- `地理学报 2023` [青藏高原植被产氧量及其对近地表大气氧含量的贡献率](https://doi.org/10.11821/dlxb202305006), 刘若杨, 史培军, 唐海萍, 王静爱, **<u>赵涔良</u>**, 朱文泉, *地理学报*.
- `RS 2022` [Reconstruction of Vegetation Index Time Series Based on Self-Weighting Function Fitting from Curve Features](https://doi.org/10.3390/rs14092247), Wenquan Zhu, Bangke He, Zhiying Xie, **<u>Cenliang Zhao</u>**, Huimin Zhuang, *Remote Sensing*.
- `植物生态学报 2021` [气候变暖背景下青藏高原草本植物物候变化空间换时间预测](https://doi.org/10.17521/cjpe.2019.0308), 李雪莹 , 朱文泉, 李培先, 谢志英, **<u>赵涔良</u>**, *植物生态学报*.

## Patent
- 朱文泉, 何邦科, **<u>赵涔良</u>**. 一种基于新型遥感指数的植被覆盖度估算方法, 专利号: ZL 202510560677.9, 授权公告日: 2025-09-02.
- 朱文泉, 杨欣怡, 刘若杨, **<u>赵涔良</u>**. 一种面向单时相影像的潜在地表异常遥感探测器构建方法, 专利号: ZL 202311342915.6, 授权公告日: 2025-08-22.
- 朱文泉, 刘若杨, 杨欣怡, **<u>赵涔良</u>**. 一种测度图像空间有序性的距离编码多样性算法, 专利号: ZL 202211600454.3, 授权公告日: 2025-06-03.
- 朱文泉, 何邦科, 谢志英, **<u>赵涔良</u>**. 一种基于曲线特征加权的植被指数时序数据函数拟合重建方法, 专利号: ZL 202210004927.7, 授权公告日: 2025-05-30.
- 朱文泉, 詹培, **<u>赵涔良</u>**. 一种基于合成孔径雷达时序数据的水稻自动识别方法, 专利号: ZL 202010117995.5, 授权公告日: 2021-12-03.

## Program experience
- **国家自然科学基金面上项目**, "考虑森林群落结构及其季节动态的森林总初级生产力遥感估算方法研究", *2024.09 - 2025.06*, **研究骨干**
- **国家自然科学基金重大项目**, "地表异常遥感探测与即时诊断方法", 课题一“地表异常遥感响应特征与语义表征”, 子课题“地表异常遥感空间响应特征研究”, *2021.01 - 2025.06*, **参与**
- **国家重点研发计划课题**, "北极陆地环境变化对人类社会致利致害效应评估", *2020.11 — 2025.06*, **研究骨干**
- **第二次青藏科考研究项目**, "生物地球化学循环与环境健康"任务二之子专题“青藏高原植被图修订与更新”, *2020.06 — 2022.10*, **研究骨干**

# 🏅 Honors and Awards
- *2024.01* Academic Innovation Award of Beijing Normal University 
- *2023.12* Top Scholarship Award, Beijing Normal University (Postgraduate)
- *2018.12* Top Scholarship Award, Beijing Normal University (Undergraduate)
- *2017.11* The Excellent Award of 15th SuperMap GIS Contest ([6th of final 10](http://www.giscontest.com/supergis/newview.asp?aid=806))
- *2012.12* Lixin Tang (唐立新) Scholarship Award (High school)

# 📖 Educations
- *2019.09 - 2025.06*, Ph.D., Cartography and GIS, State Key Laboratory of Remote Sensing Science, Faculty of Geographical Science, Beijing Normal University, Beijing (北京师范大学地理科学学部遥感科学国家重点实验室 地图学与地理信息系统)
- *2015.09 - 2019.06*, B.S., Resource and Environmental Science, Faculty of Geographical Science, Beijing Normal University, Beijing (北京师范大学地理科学学部 资源环境科学)
- *2012.09 - 2015.06*, Science, Chengdu Shishi High School, Chengdu (成都石室中学-文庙校区 理科)

# 🌏 Field Research
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">202309 外业团队合影 (左6)</div><img src='images/202309_GF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Satellite-ground synchronous in-situ dataset** <br>
(**中国科学院空天信息创新研究院野外同步测量类数据集**) <br>
As the team leader of field experiment, I conducted 10+ satellite synchronous ground observation experiments across multiple locations (including refelctance (地表反射率), water-leaving radiance (离水辐射率), albedo (地表反照率), emissivity (地表发射率), landsurface temperature (地表温度), FVC (植被覆盖度), vegetation type and phenology (植被类型和物候)).
- *2023.10.21 - 2023.10.26* Zhuhai, Guangdong province (广东珠海)
- *2023.09.24 - 2023.09.28* Saihanba, Hebei province (河北塞罕坝)
- *2023.08.10 - 2023.08.17* Gaoyou, Jiangsu province (江苏高邮)
- *2023.07.27 - 2023.07.30* Saihanba, Hebei province (河北塞罕坝)
- *2023.07.10 - 2023.07.24* Beitun, Xinjiang province (新疆北屯) [Media Report](https://article.xuexi.cn/articles/index.html?art_id=5453280297232469863&source=share&cdn=https%3A%2F%2Fregion-xjbt-resource&study_style_id=feeds_opaque&reco_id=102433abf5b3c0a886600005&share_to=wx_single&study_share_enable=1&study_comment_disable=1&ptype=0&item_id=5453280297232469863)
- *2023.06.12 - 2023.06.17* Gaoyou, Jiangsu province (江苏高邮)
- *2023.05.31 - 2023.06.12* Beitun, Xinjiang province (新疆北屯)
- *2023.05.21 - 2023.05.30* Jiusan, Heilongjiang province (黑龙江九三)
- *2023.02.24 - 2023.03.06* Zhuhai, Guangdong province (广东珠海)
- *2022.09.16 - 2022.09.23* Jiusan, Heilongjiang province (黑龙江九三)
- *2022.09.03 - 2022.09.10* Saihanba, Hebei province (河北塞罕坝)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">202207 外业团队合影 (右2)</div><img src='images/202207_SHB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Instrument maintenance** <br>
Replaced the old phenology camera and updated the battery and SIM card of soil moisture monitors.
- *2022.07.21 - 2022.07.25* Saihanba, Hebei province (河北塞罕坝)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">202107 外业工作照 (右2)</div><img src='images/2021_TP.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**The Second Tibetan Plateau Scientific Expedition and Research** <br>
(**第二次青藏高原综合科学考察研究**) <br>
Operated DJI Phantom 4 Pro drones for aerial data collection (20+ flight missions), generating high-resolution orthomosaic maps. Processed multispectral imagery with Pix4Dmapper to analyze vegetation coverage patterns. Compiled daily field logs.
- *2021.07.25 - 2021.08.24* The Qilian Mountain, Qinghai province (青海祁连山脉). Survey route: Xining (西宁) - Menyuan (门源) – Gangcha (刚察)– Dulan (都兰) – Maduo (玛多)– Xinghai (兴海) - Xining (西宁). <br>
<center><video width="320" height="240" controls>
<source src="images/video.mp4" type="video/mp4">
</video></center>
</div>
</div>

# 🗣️ Conference

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">202604 第3届人工智能与遥感科学交叉论坛</div><img src='images/Meeting_202605.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**The 3rd Cross-Disciplinary Forum on Artifical Intelligence and Remote Sensing** <br>
(**第3届人工智能与遥感科学交叉论坛届地学青年论坛**) <br>
Section 4.9 Extreme climates and terrestrial ecosystem <br>
(专题4.9 极端气候与陆地生态系统) <br>
- *2026.05.16 18:05-18:20*  
- Title: Mechanistic insights into the unimodal temperature response of terrestrial ecosystem respiration.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">202604 第11届地学青年论坛</div><img src='images/Meeting_202604.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**The 11th Young Scientist Forum of Earth Science** <br>
(**第11届地学青年论坛**) <br>
Section 7.1 Terrestrial Phenology and carbon cycle under global warming <br>
(专题7.1 全球变化下的陆地生态系统物候与碳循环) <br>
- *2026.04.11 14:18-14:30*  
- Title: Embedding thermal adaptation into ecosystem respiration modelling: the global unimodal temperature sensitivity pattern.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">202508 第2届全国信息地理学大会</div><img src='images/Meeting_202508.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**The 2nd National Conference on Information Geography** <br>
(**第2届全国信息地理学大会**) <br>
Section 3.7 Remote sensing of terrestrial carbon cycle <br>
(专题3.7 陆地碳循环遥感) <br>
- *2025.08.20 09:25-09:40*  
- Title: Optimizaing global ecosystem respiration estimation via combining with causal inference.
</div>
</div>

# 🏫 Working Activities
- *2025.07 - now*, Postdoctoral Researcher, School of Geography and Planning, Sun Yat-sen University, Guangzhou, Guangdong, China
- *2022.09 - 2023.12*, Teaching Assistant of [Remote Sensing Digital Image Processing](https://www.icourse163.org/course/BNU-1002335009) (国家精品课程-遥感数字图像处理), Faculty of Geographical Science, Beijing Normal University, Beijing, China

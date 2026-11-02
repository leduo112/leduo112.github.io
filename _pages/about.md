---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am an MPhil student in the [Data Science and Analytics (DSA) Thrust](https://dsa.hkust-gz.edu.cn/) at **The Hong Kong University of Science and Technology (Guangzhou)**, working in [Prof. Jiaheng Wei](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/WEI-Jiaheng/jiahengwei)'s DataLab and co-supervised by [Prof. Yutao Yue](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/YUE-Yutao/yutaoyue). Before that, I received dual bachelor's degrees from **Xi'an Jiaotong University**, where I also conducted research on low-carbon urban energy systems in [Prof. Lu Sun](https://gr.xjtu.edu.cn/web/0020210384)'s group.

My research focuses on **data-centric, trustworthy machine learning**: diagnosing data quality and noise in AI systems, and building reliable data-driven models for low-carbon energy systems. Specifically:

1. **Data-centric AI**: diagnosing annotation errors in multimodal data, so that models are trained and evaluated on data we can trust.
2. **Data-driven Low-carbon Energy Systems**: scenario modeling and forecasting for building decarbonization and EV battery recycling.

<p class="phd-callout">🔎 I am looking for PhD positions starting in <strong>Fall 2027 or Spring 2028</strong>. Feel free to reach out by <a href="mailto:dzhang236@connect.hkust-gz.edu.cn">email</a>!</p>

# 📖 Education & Research Experience
<span class='anchor' id='experience'></span>

- *2025.09 – 2027.07 (expected)*, MPhil in Data Science and Analytics, **The Hong Kong University of Science and Technology (Guangzhou)**.
- *2024.08 – 2025.07*, Research in Prof. Lu Sun's group, **Xi'an Jiaotong University**.
- *2020.09 – 2024.06*, Bachelor's in Science and Technology of Human Settlements (Big Data & Smart City), with a double degree in Accounting, **Xi'an Jiaotong University**.

# 📝 Publications
<span class='anchor' id='publications'></span>

## 🧩 Data-centric AI

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2027 (under review)</div><a href='images/tag_framework.png'><img src='images/tag_framework.png' alt="TAG framework" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**TAG: Task-Conditioned Adaptive Diagnosis for Multimodal Data**

**Dongyi Zhang**, Yule Liu, Zhen Sun, Ziyang Liang, Yi Han, Xinlei He, Yutao Yue, Jiaheng Wei, Zhaowei Zhu

*Under review at ICLR 2027*

- Wrong answer labels in multimodal datasets silently distort how models are trained and evaluated, and no single detection strategy works best across all tasks.
- Built a unified benchmark on AVA-Bench, ScienceQA, and MMMU with controlled label noise, and found that the best strategy depends on the task type and the noise level.
- Proposed **TAG**, which picks a task-specific detection strategy for each sample and falls back to a shared one when the task is uncertain.
</div>
</div>

## 🌱 Low-carbon Energy Systems

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Buildings 2025</div><a href='images/buildings_framework.png'><img src='images/buildings_framework.png' alt="Research framework" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[**The Effect of Low-Carbon Technology on Carbon Emissions Reduction in the Building Sector: A Case Study of Xi'an, China**](https://doi.org/10.3390/buildings15121989)

**Dongyi Zhang**†, Lu Sun†, Yifan Zhang, Tianye Liu, Lu Gao, Fufu Wang, Xinting Qiao, Yuqi Liu, Jian Zuo, Yupeng Wang

*Buildings*, 2025

- Built a multi-scenario LEAP model of carbon emissions in Xi'an's building sector.
- Modeled the city-scale reduction potential of five low-carbon technologies, including heat pumps, rooftop PV, and advanced building materials.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Planned</div><a href='images/rcr.png'><img src='images/rcr.png' alt="EV battery retirement projections by chemistry and province" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

**The Carbon Reduction Benefits Analysis of Recycling and Second Life for Electric Vehicle Batteries in China**

Chenyang Wang, **Dongyi Zhang**, Xin Sun, Lu Sun*

*Planned for submission to Resources, Conservation & Recycling*

- Forecast province-level retirement of EV batteries in China from 2025 to 2035, combining vehicle adoption curves with battery lifetime distributions.
- Linked retirement volumes to the carbon benefits of recycling and second-life use, and to recycling capacity under new policy rules.
</div>
</div>

<p class="pub-note">* Corresponding author. † Equal contribution.</p>

## 🤝 Other Collaborations

<div class="collab-list" markdown="1">

- **When Can the Runtime Take Over? A Decision-Level Audit of LLM Agent Control**<br>Ziyang Liang, Tiantian Zhu, Haodong Wu, **Dongyi Zhang**, Letong Han, Shuyi Sun, Chang Liu, Yongqi Zhang. *Under review at ICLR 2027*
- **Degrees of Freedom in LLM Multi-Agent Coordination: Between Centralized and Decentralized Regimes**<br>Yiqing Peng, Hehai Lin, Zixuan Wang, **Dongyi Zhang**, Zhengjie Zhu, Yi Han, Yangyang Zheng, Hao Wang, Qian Li, Chengwei Qin. *Under review at ICLR 2027*
- **When Conversation Turns Hostile: Conversation-Observing Indirect Prompt Injection for LLM Agents**<br>Yi Han, Zhen Sun, Zhijie Deng, Yini Huang, Yangyang Zheng, **Dongyi Zhang**, Xinlei He. *Under review at ICLR 2027*
- **Beyond Fixed Workflows: Requirement-Conditioned Program Synthesis for Versatile Music-Driven Video Creation**<br>Yuhan Pu, Ziqian Mo, Zile Yang, Yini Huang, Yi Han, **Dongyi Zhang**, Aiwen Lu, Zeke Xie, Jiaheng Wei. *Under review at ACL Rolling Review*

</div>

# 🛠 Projects
<span class='anchor' id='projects'></span>

- **Music Generation and Music-Driven Video Creation** *(2026.03 – 2026.09, DataLab, HKUST(GZ))*. Responsible for quality evaluation of generated audio: crawled chart data from mainstream music platforms as a popularity reference for scoring, and evaluated further dimensions such as musicality. Also contributed to data collection and reference curation for video generation. Related manuscript: *Beyond Fixed Workflows* (under review at ACL ARR).
- **Differentially Private Medical Image Generation** *(2026.03 – 2026.06, course project, HKUST(GZ))*. Implemented the differential privacy module for a ControlNet-guided image generator, using DP-SGD with Opacus to study the privacy–utility trade-off on facial-palsy images from 206 patients.
- **TAG: Multimodal Annotation-Error Diagnosis** *(2026.01 – present, DataLab, HKUST(GZ))*. Curated multimodal benchmarks, compared 88 encoder–detector combinations across three datasets, and developed task- and noise-conditioned diagnostic strategies. The first-author ICLR 2027 submission reports a 1.24-percentage-point AUROC improvement over the best shared strategy on AVA-Bench.
- **EV Battery Retirement and Recycling Benefits** *(2025.06 – present, Prof. Lu Sun's group, Xi'an Jiaotong University)*. Forecast new-energy vehicle promotion across 31 provincial regions with Gompertz scenarios and a national-pathway calibration. Combined vehicle type, battery chemistry, and staged Weibull lifetimes to estimate retired battery quantities, energy, and mass for the team's recycling and second-life carbon-benefit analysis.
- **Silver Economy Industrial Platform** *(2025.01 – 2025.06, collaboration with Peking University)*. Analyzed the industry's spatial and temporal development and organized a database linking technologies, products, and demand.
- **Urban Low-Carbon Pathway Planning via Multi-Network Integration** *(2024.08 – 2024.12, government collaboration, Xi'an Jiaotong University)*. Built six carbon-emission scenarios from single-sector to multi-sector settings, incorporating transportation-network analysis to support urban low-carbon pathway planning.
- **Carbon-Emission Calculation Platform and Emission-Factor Database** *(2024.07 – 2025.03, collaboration with Xi'an Sanhao Software Co.)*. Designed the numerical scheme, functional requirements, and visualization modules for an educational carbon-emission simulation platform, and contributed to its emission-factor database.
- **Building-Sector Decarbonization in Xi'an** *(2024 undergraduate thesis; expanded into a 2025 Buildings paper)*. Built LEAP scenarios for building-sector emissions and modeled the reduction potential of five low-carbon technologies. The paper reports a combined reduction potential of 25.8%; I am the first-listed author and contributed equally with Prof. Lu Sun.
- **ESG Performance and Corporate Value in the Automotive Industry** *(2024, Accounting undergraduate thesis)*. Conducted an empirical study of the relationship between automotive companies' ESG performance and corporate value.
- **BeiDou-Based EV Charging-Station Siting** *(2023.07 – 2023.09, summer project competition)*. Processed spatiotemporal data and contributed to a charging-station siting plan. Our team won first prize in the annual final of the 6th “BeiDou Star” Silk Road International Challenge.
- **ML Surrogate for Hydrogen Fuel-Cell Stacks** *(2022.05 – 2023.05, undergraduate innovation project, PI)*. Coupled flow/thermal-resistance network models with COMSOL multiphysics simulation to generate training data, and trained a neural-network surrogate to predict stack discharge performance and cell-to-cell consistency. Rated National Excellent; released as software with a software copyright.
- **Building Energy Use and Conservation Potential from Monitoring Data** *(2022.05 – 2023.05, undergraduate innovation project)*. Cleaned building-energy monitoring data, detected outliers, and visualized results to assess conservation potential. The project was rated National Excellent.

{% comment %}
CV: after adding files/Dongyi_Zhang_CV.pdf, uncomment this block and add CV back to _data/navigation.yml.

# 📄 CV
<span class='anchor' id='cv'></span>

[Download my CV (PDF)](files/Dongyi_Zhang_CV.pdf)
{% endcomment %}

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
# 个人简介
我目前是南京大学计算机科学与技术系 [Websoft研究组](http://ws.nju.edu.cn/wiki/Wiki.jsp?page=Websoft) 的四年级博士生，导师是 [胡伟教授](http://ws.nju.edu.cn/~whu)。我的研究兴趣涵盖了一系列领域：图基座模型及其与大语言模型的双向增强、知识图谱、终身学习和图增强的语言问答。
## 教育背景
- 博士，南京大学，计算机科学与技术系，导师 [胡伟](http://ws.nju.edu.cn/~whu) （2021 - 至今）
- 硕士，南京航空航天大学，计算机科学与技术学院，导师 [李静](https://faculty.nuaa.edu.cn/lj12/zh_CN/index.htm) （2018 - 2021）
- 学士，中国矿业大学，计算机科学与技术学院 （2014 - 2018）

[comment]: <> (# Recent News)
[comment]: <> (- [*2025.02*] One 1st-author paper accepted to TKDE'2025!)
[comment]: <> (- [*2024.11*] Invited by OpenKG to give a [talk]&#40;https://github.com/nju-websoft/KG-ICL/blob/main/OpenKG-Slides-11.21.pdf&#41; on KG-ICL at Tongji University!)
[comment]: <> (- [*2024.11*] Invited by [LMG 2024]&#40;http://lmg.cipsc.org.cn/conference/cips-lmg2024/index.html&#41; to show our [poster]&#40;https://github.com/nju-websoft/KG-ICL/blob/main/poster.pdf&#41; about KG-ICL!)
[comment]: <> (- [*2024.11*] Awarded the National Scholarship!)
[comment]: <> (- [*2024.09*] One 1st-author paper accepted to NeurIPS'2024!)
[comment]: <> (- [*2024.07*] Invited by [CCDM 2024]&#40;https://ccf.org.cn/CCDM2024/general_3024&#41; to give a talk on RulePrem.)
[comment]: <> (- [*2024.06*] One 2nd-author paper accepted to ISWC'2024!)
[comment]: <> (- [*2024.05*] One 1st-author paper accepted to JCRD'2024!)
[comment]: <> (- [*2024.05*] One research project &#40;led by me&#41; under the Jiangsu Province Graduate Innovation Program, successfully concluded!)
# 主要论文
## 一作论文
- Transfer-and-Fusion: Integrated Link Prediction across Knowledge Graphs
  - <u>Yuanning Cui</u>, Zequn Sun, Wei Hu 
  - TKDE'25, CCF推荐A类国际期刊 \[[Paper](https://ieeexplore.ieee.org/document/10897840)\|[Code](https://github.com/websoft/CLP)\] 
- A Prompt-Based Knowledge Graph Foundation Model for Universal In-Context Reasoning 
  - <u>Yuanning Cui</u>, Zequn Sun, Wei Hu
  - NeurIPS'24, CCF推荐A类国际会议 \[[Paper](http://arxiv.org/abs/2410.12288)\|[Code](https://github.com/nju-websoft/KG-ICL)\]
- A Pre-trained Universal Knowledge Graph Reasoning Model Based on Rule Prompts
  - <u>Yuanning Cui</u>, Zequn Sun, Wei Hu 
  - JCRD'24, CCF推荐A类中文期刊 \[[Paper](https://kns.cnki.net/kcms2/article/abstract?v=Dm4VI7mKrXM7LHO7XuR5Ah1spGUmXEYVjzxlukLRdzjDjjtsVlP874zQ4fWBzBskh7KSAIM4x4wp5d3rYYrZNNZn04-R1dXZ8s1HxHrepbHqk2hpllLo1B6ca57ZBpnKmPVjANx6qVXMqXQycCrajoJ09aTWDb5ZN6UaXGuPOiC6WJAO7_JHKXwlj2C2SG1z&uniplatform=NZKPT&language=CHS)\|[Code](#)\]
- Lifelong Embedding Learning and Transfer for Growing Knowledge Graphs 
  - <u>Yuanning Cui</u>, Yuxin Wang, Zequn Sun, Wenqiang Liu, Yiqiao Jiang, Kexin Han, Wei Hu  
  - AAAI'23, CCF推荐A类国际会议 \[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25539/25311)\|[Code](https://github.com/nju-websoft/LKGE)\]
- Inductive Knowledge Graph Reasoning for Multi-Batch Emerging Entities 
  - <u>Yuanning Cui</u>, Yuxin Wang, Zequn Sun, Wenqiang Liu, Yiqiao Jiang, Kexin Han, Wei Hu 
  - CIKM'22, CCF推荐B类国际会议 \[[Paper](https://arxiv.org/pdf/2208.10378)\|[Code](https://github.com/nju-websoft/MBE)\]
- Duration-HyTE: A Time-Aware Knowledge Representation Learning Method Based on Duration Modeling
  - <u>Yuanning Cui</u>, Jing Li, Li Shen, Yang Shen, Lin Qiao, Jue Bo
  - JCRD'20, CCF推荐A类中文期刊 \[[Paper](https://kns.cnki.net/kcms2/article/abstract?v=iAN2XHIMbKv9vGU554HyrEtVJcU5_YanS7VkxsgoI5O3ICEpPdsZsnBsZwd_ppH_Fo4uZv2sgGz4J1jcwPfUlqsb_iwt2quuKzaLT39NPaO6sDV6mwGh9Z_Zs5yj_OPjngJDE-F8mksSLxl98nxgTznUyxHut420VQhHQJUsXpD-B2u5yZC-r81E9tSborFn&uniplatform=NZKPT&language=CHS)\|[Code](#)\]
## 二作论文
- Expanding the Scope: Inductive Knowledge Graph Reasoning with Multi-Starting Progressive Propagation  
  - Zhoutian Shao, <u>Yuanning Cui</u>, Wei Hu   
  - ISWC'24, CCF推荐B类国际会议 \[[Paper](https://arxiv.org/pdf/2407.10430)\|[Code](https://github.com/nju-websoft/MStar)\] 
- Improving Continual Relation Extraction by Distinguishing Analogous Semantics  
  - Wenzheng Zhao, <u>Yuanning Cui</u>, Wei Hu 
  - ACL'23, CCF推荐A类国际会议 \[[Paper](https://arxiv.org/pdf/2305.06620)\|[Code](https://github.com/nju-websoft/CEAR)\] 
- Lifelong Representation Learning of Multi-sourced Knowledge Graphs via Linked Entity Replay  
  - Zequn Sun, <u>Yuanning Cui</u>, Wei Hu  
  - JoS'23, CCF推荐A类中文期刊 \[[paper](https://www.jos.org.cn/josen/article/pdf/6887)\|[Code](https://github.com/nju-websoft/LifeKE)\] 
- Facing Changes: Continual Entity Alignment for Growing Knowledge Graphs  
  - Yuxin Wang, <u>Yuanning Cui</u>, Zequn Sun, Wenqiang Liu, Yiqiao Jiang, Kexin Han, Wei Hu  
  - ISWC'22, CCF推荐B类国际会议 \[[paper](https://arxiv.org/pdf/2207.11436)\|[Code](https://github.com/nju-websoft/ContEA)\] 
## 在审论文
- LanGraph: Synergy of Language and Graph Foundation Models for Generalized Knowledge Graph Question Answering
  - <u>Yuanning Cui</u>, Zequn Sun, Zhoutian Shao, Yang Liu, Wei Hu
  - ACL'25在审, CCF推荐A类国际会议 
## 演讲 & 海报
- A Prompt-Based Knowledge Graph Foundation Model for Universal In-Context Reasoning 
  - NeurIPS'24 poster presentation, Vancouver, Canada, December 2024
- CIPS-LGM 2024 Poster Presentation 
  - poster presentation, Jiaxing, China, November 2024
- A talk about the KG foundation model KG-ICL
  - OpenKG Ph.D. seminar oral presentation, Shanghai, China, November 2024
- A Pre-trained Universal Knowledge Graph Reasoning Model Based on Rule Prompts
  - CCDM 2024 oral presentation, Taian, China, July 2024
- A talk about dynamic KG representation learning  
  - OpenKG Ph.D. seminar oral presentation, Nanjing, China, September 2023
- Lifelong Embedding Learning and Transfer for Growing Knowledge Graphs
    - AAAI'23 oral presentation (virtual event), Washington, DC, USA, February 2023
- CIPS Pre-Conference Presentation for AAAI'23
  - oral presentation (virtual event), Beijing China, January 2023
- Inductive Knowledge Graph Reasoning for Multi-Batch Emerging Entities
  - CIKM'22 oral presentation (virtual event), Atlanta, GA, USA, October 2022

## 获奖
- 国家奖学金（博士研究生），南京大学（2024） *￥30,000*
- 研究生一等奖学金，南京大学（2023） *￥12,000*
- 南瑞特别奖学金，南京大学（2023） *￥8,000*
- 研究生一等奖学金，南京大学（2022） *￥10,000*
- 优秀人才研究生一等奖学金，南京大学（2022） *￥5,000*
- 华为特别奖学金，南京航空航天大学（2020） *￥8,000*
- 研究生一等奖学金，南京航空航天大学（2019 & 2020） *￥10,000*
- 校三好学生奖，南京航空航天大学（2019 & 2020）
- 科研创新先进个人，南京航空航天大学（2019 & 2020）

## 主持项目
- 江苏省研究生科研创新计划（2023 - 2024）
  - 项目名称：面向动态知识图谱的终身表示学习
  - 角色：项目负责人
  - 描述：本项目旨在开发一个针对动态知识图谱的终身表示学习框架，能够有效捕捉知识图谱中实体和关系的动态变化。
  - 
## 会议PC & 期刊审稿
- 会议：NeurIPS, AAAI, SIGKDD, ACL Rolling Review, ISWC, DASFAA, ESWC, CCKS
- 期刊：TKDE, TNNLS, KBS
  
# 教学经历
- *2023年春季* 助教，知识工程，南京大学
- *2022年春季* 助教，知识工程，南京大学
- *2019年春季* 助教，编程语言原理，南京航空航天大学
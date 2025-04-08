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

# About Me
I am currently a 4th-year Ph.D. Student at [Websoft Research Group](http://ws.nju.edu.cn/wiki/Wiki.jsp?page=Websoft) at the Department of Computer Science and Technology, 
Nanjing University, advised by [Prof. Wei Hu](http://ws.nju.edu.cn/~whu).

My research interest covers a range of issues: Graph Foundation Model, Knowledge graph, Lifelong Learning, and LLMs. 

## Education
- PhD, Nanjing University, Department of Computer Science and Technology, advised by [Wei Hu](http://ws.nju.edu.cn/~whu) (2021 - present)
- Master, Nanjing University of Aeronautics and Astronautics, School of Computer Science and Technology, advised by [Jing Li](https://faculty.nuaa.edu.cn/lj12/zh_CN/index.htm) (2018 - 2021)
- Bachelor, China University of Mining and Technology, School of Computer Science and Technology (2014 - 2018)

# Recent News
- [*2025.04*] One co-author paper accepted to SIGIR'2025!
- [*2025.02*] One 1st-author paper accepted to TKDE'2025!
- [*2024.11*] Invited by OpenKG to give a [talk](https://github.com/nju-websoft/KG-ICL/blob/main/OpenKG-Slides-11.21.pdf) on KG-ICL at Tongji University!
- [*2024.11*] Invited by [LMG 2024](http://lmg.cipsc.org.cn/conference/cips-lmg2024/index.html) to show our [poster](https://github.com/nju-websoft/KG-ICL/blob/main/poster.pdf) about KG-ICL!
- [*2024.11*] Awarded the National Scholarship!
- [*2024.09*] One 1st-author paper accepted to NeurIPS'2024!
- [*2024.07*] Invited by [CCDM 2024](https://ccf.org.cn/CCDM2024/general_3024) to give a talk on RulePrem.
- [*2024.06*] One 2nd-author paper accepted to ISWC'2024!

[//]: # (- [*2024.05*] One 1st-author paper accepted to JCRD'2024!)

[//]: # (- [*2024.05*] One research project &#40;led by me&#41; under the Jiangsu Province Graduate Innovation Program, successfully concluded!)

# Publications

## First-author Papers
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

## Co-author Papers

- Benchmarking Recommendation, Classification, and Tracing Based on Hugging Face Knowledge Graph
  - Qiaosheng Chen, Kaijia Huang, Xiaozhou, Weiqing Luo, <u>Yuanning Cui</u>, Gong Cheng
  - SIGIR'25, CCF推荐A类国际会议

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

## Under-review Papers
- LanGraph: Synergy of Language and Graph Foundation Models for Generalized Knowledge Graph Question Answering
  - <u>Yuanning Cui</u>, Zequn Sun, Zhoutian Shao, Yang Liu, Wei Hu
  - ACL'25在审, CCF推荐A类国际会议 

## Presentations

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

<br>
## Awards
- National Scholarship for Ph.D. Students, Nanjing University (2024) *￥30,000*
- 1st-Class Academic Scholarship for Graduate Students, Nanjing University (2023) *￥12,000*
- Special Scholarship from NARI, Nanjing University (2023) *￥8,000*
- 1st-Class Academic Scholarship for Graduate Students, Nanjing University (2022) *￥10,000*
- 1st-class Graduate Scholarship for Outstanding Talent, Nanjing University (2022) *￥5,000*
- Huawei Special Scholarship, NUAA (2020) *￥8,000*
- 1st-Class Academic Scholarship for Graduate Students, NUAA (2019 & 2020) *￥10,000*
- Merit Student Award Winners, NUAA (2019 & 2020)
- Outstanding Individual in Research and Innovation, NUAA (2019 & 2020)

[comment]: <> (- 1st-Class Academic Scholarship for Graduate Students, NUAA &#40;2019&#41; *￥10,000*)


## Project
- Jiangsu Province Graduate Innovation Program (2023 - 2024)
  - Title: Lifelong Representation Learning for Growing Knowledge Graphs
  - Role: Project Lead
  - Description: This project aims to develop a lifelong representation learning framework for growing knowledge graphs, which can effectively capture the dynamic changes of entities and relations in the knowledge graph.

## PC Member & Reviewer

- Conference: NeurIPS, AAAI, SIGKDD, ACL Rolling Review, ISWC, DASFAA, ESWC, CCKS
- Journal: TKDE, TNNLS, KBS
  
# Teaching
- *Spring, 2023* Teaching Assistant, Knowledge Engineering, Nanjing University
- *Spring, 2022* Teaching Assistant, Knowledge Engineering, Nanjing University
- *Spring, 2019* Teaching Assistant, Programming Language Principles, NUAA




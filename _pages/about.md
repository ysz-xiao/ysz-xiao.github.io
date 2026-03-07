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

# About me

Hi, I am Xiao. I received my Ph.D. in Computer Science from Nanjing University in 2019 and 2023. Currently, I serve as a Lecturer in the School of Automation and Electronic Information at Xiangtan University. Our research interests primarily lie in Reinforcement Learning (RL) and Explainable Artificial Intelligence (XAI), with a focus on improving RL interpretability and designing scalable solutions for complex, real-world systems.

# Courses

《人工智能微专业：Python编程与实践》, 《多智能体系统》, 《计算机操作系统》

# Publications

<!--
# Paper Under Submission
- Lili Yao, Xiao Liu*, Yannan Guo, Kang Shi, Huayao Wu and Changhai Nie. Enhancing Illicit Transaction Detection on Blockchain via High-Order Semantics. 2025 (投稿，本科生三作)
- Xizheng Qiao, Xinyi Peng, Kangrui Qi, Xiao Liu*. Symbolic Kolmogorov-Arnold Policy Gradient: An Interpretable Deep Reinforcement Learning Approach for DER Scheduling in Active Distribution Networks.2025 (投稿，本科生一作)
- Yannan Guo, Jianling Yao, Jianyang Yao, Xiao Liu*. SPMC: A Frequency Domain-Based Multi-Classification Method for Detecting Anomalies in Bitcoin Transactions. 2025. (投稿，本科生一作)
- Lin Wang, Fan Zhou, Xiao Liu*. Transformer Fault Diagnosis Using DeepFaultNet on Imbalanced Datasets, IEEE Transactions on Dielectrics and Electrical Insulation. (投稿，本科生二作)
- Yi Su, Zhuoceng Dai, Xiao Liu*, Attack and Defense Against Deep Reinforcement Learning-Based Agent for Discrete Domains: Application in Distribution Network Reconfiguration. TASE. 2025.
- Adversarial Attacks and Defense for Multi-Agent Deep Reinforcement Learning-Based Optimal Dispatching in an Active Distribution Network. 2025
- Transformer Fault Diagnosis Using DeepFaultNet on Imbalanced Datasets. 2025
-->

<!-- 质量一般的合作论文
Hui Li, Changhao Zhu*, Xiao Liu, Lijuan Li, Hongzhi Liu. Hybrid binarized neural network for high-accuracy classification of power quality disturbances. Electrical Engineering, 2024. https://doi.org/10.1007/s00202-024-02650-y
-->

- Yannan Guo, Jiangling Yao, Xiao Liu*, ArcLight-AttGRU: An Ultra-Lightweight Attention-Gated GRU Framework for Low-Frequency Series Arc Fault Detection, IEEE Transactions on Instrumentation and Measurement, 2026.
IEEE Transactions on Instrumentation & Measurement
- Siyuan Zhang, Yannan Guo, Xiao Liu*. A Physics-Guided Feature-Subspace Ensemble Framework for Forecasting Photovoltaic and Wind Power Generation, Electric Power Systems Research, 2026.
- Yongxin Su, Mengyao Xu, Xiao Liu, Mao Tan*, Rui Wang, Chunhua Yang. Explainable reinforcement learning for enhancing personal thermal comfort and optimizing demand response in household multi-zone HVAC system. Science China. 68, 1600403 (2025). https://doi.org/10.1007/s11431-024-2895-7
https://doi.org/10.1007/s11431-024-2895-7.
- Mao Tan, Jie Zhao, Xiao Liu*, Yongxin Su, Ling Wang, Rui Wang, Zhuocen Dai, Federated Reinforcement Learning for smart and privacy-preserving energy management of residential microgrids clusters, Engineering Applications of Artificial Intelligence, Volume 139, Part B, 2025, 109579, ISSN 0952-1976.
https://doi.org/10.1016/j.engappai.2024.109579.
- 曹宏业, 刘潇, 董绍康, 杨尚东, 霍静, 李文斌, 高阳*. 面向强化学习的可解释性研究综述. 计算机学报, Vol. 47 No. 8. 2024.
http://cjc.ict.ac.cn/online/onlinepaper/chy-2024729180508.pdf
- Wubing Chen, Shangdong Yang, Wenbin Li, Yujing Hu, Xiao Liu, Yang Gao*. Learning multi-intersection traffic signal control via coevolutionary multi-agent reinforcement learning. IEEE Transactions on Intelligent Transportation Systems, 2024. https://ieeexplore.ieee.org/abstract/document/10556581
- Wubing Chen, Wenbin Li, Xiao Liu, Gao Yang*. Learning explicit credit assignment for cooperative multi-agent reinforcement learning via polarization policy gradient, proceedings of the aaai conference on artificial intelligence. Vol. 37 No. 10: Technical Tracks 10. 2023. https://doi.org/10.1609/aaai.v37i10.26364
- Xiao Liu, Shuyang Liu, Bo An, Yang Gao*, Wenbin Li. Effective interpretable policy distillation via critical experience point identification. IEEE Intelligent Systems. Vol. 38, Issue: 5, Sept.-Oct. 2023. https://doi.org/10.1109/MIS.2023.3265868
- 刘潇, 刘书洋, 庄韫恺, 高阳*. 强化学习可解释性基础问题探索和方法综述. 软件学报. 2023, 34(5): 2300-2316. https://doi.org/10.13328/j.cnki.jos.006485
- Xiao Liu, Wenbin Li, Jing Huo, Lili Yao, Yang Gao*. Layerwise sparse coding for pruned deep neural networks with extreme compression ratio. Proceedings of the aaai conference on artificial intelligence. 34(04): 4900-4907. 2020. https://doi.org/10.1609/aaai.v34i04.5927


# Grants

- 国家自然科学基金青年项目，62406272，多智能体强化学习的部署安全性验证方法，2025.1-2027.12，主持
- 湖南省自然科学基金青年项目，2024JJ6438，深度强化学习可解释策略简化与规则提取研究，2025.1-2027.12，主持

<!--
比较差的论文
- Xizheng Qiao, Xinyi Peng, Kangrui Qi, Xiao Liu*. Enhancing der scheduling in active distribution networks: A symbolic deep reinforcement learning approach for improved interpretability and performance, 2025 IEEE International Symposium on the Application of Artificial Intelligence in Electrical Engineering, 2025. (本科生一作)
- Jing Shi, Xinyi Peng, Xizheng Qiao, Xiao Liu*. Balancing accuracy and explainability: An ensemble-kan model for patent grant prediction, 20th International Society of Scientometrics and Informetrics Conference, Yerevan, Armenia, 2025. (本科生二作)
-->

<!--
# 📖 履历
- *2023.07 - now*, 湘潭大学，讲师
- *2019.09 - 2023.6*, 南京大学，博士研究生，导师高阳教授
- *2018.09 - 2019.6*, 武汉大学，学术访问，导师杜博教授
- *2015.09 - 2018.6*, 中南民族大学，硕士研究生，导师周斌教授
- *2010.09 - 2014.6*, 中南民族大学，硕士研究生，导师周斌教授
-->

---
layout: default
title: Graph Condensation: Foundations, Methods and Prospects
description: WWW 2025 Tutorial
---


## Introduction
<div style="text-align: justify;">
Graph data is extensively utilized across various domains, owing to its capacity to represent complex structural relationships among diverse real-world entities. However, the rapid expansion of graph data introduces significant challenges in terms of storage, transmission, and the training of graph neural networks (GNNs) for effective graph data analysis. In light of these challenges, graph condensation (GC) has emerged as a data-centric solution, synthesizing a compact yet representative graph to replace the original large graph in GNN training. These GNNs trained on condensed graphs can achieve performance comparable to models trained on full-scale data, attracting substantial attention and stimulating extensive research.
In response to this trend, this tutorial provides a comprehensive and up-to-date overview of GC research. It systematically categorizes existing studies into five categories aligned with critical GC evaluation criteria: effectiveness, generalization, efficiency, fairness, and robustness. Additionally, we will provide an in-depth analysis of two fundamental components of GC: optimization strategies and condensed graph generation, elucidating their key characteristics and underlying technologies. Finally, this tutorial will explore GC applications across various fields and outline potential directions for future research in this rapidly evolving and impactful domain.
</div>


## Outline

This is a lecture-style tutorial that includes:

**Section 1: Welcome and Introduction (10 mins)**
  - Overview of Graph Representation Learning
  - Background of Graph Condensation

**Section 2: Definition and Taxonomy of GC (20 mins)**
  - Definition of Graph Condensation
  - Categorization of Existing GC Methods

**Section 3: A Review of GC Methods (90 mins)**
  - Optimization Strategies
  - GC Methods
  - Condensed Graph Generation
    
**Section 4: GC Toolkit: GCondenser (20 mins)**
  - The Framework of GCondenser
  - Characteristics of GCondenser

**Section 5: Applications and New Trends (20 mins)**
  - Applications for Existing GC Methods
  - Emerging Research Directions
    
**Section 6: Conclusion and Open Discussions (20 mins)**



## Presenter

<div style="text-align: justify;">
<ul style="list-style-type: disc; padding-left: 20px;">

<li><strong>Prof. Hongzhi Yin</strong> works as an ARC Future Fellow, Full Professor, and Director of the Responsible Big Data Intelligence Lab (RBDI) at The University of Queensland, Australia. He has published 300+ papers with an H-index of 78, making notable contributions to recommendation systems, graph learning, decentralized learning, and edge intelligence. His research has won 8 international and national Best Paper Awards, including Best Paper Award (Honorable Mention) at WSDM 2023, Best Paper Award at ICDE 2019, and Best Student Paper Award at DASFAA 2020.</li>

<br>
<li><strong>Mr. Xinyi Gao</strong> is currently pursuing his Ph.D. at The University of Queensland. He received his B.S. and M.S. degrees in Information and Communications Engineering from Xi’an Jiaotong University. His research work has been published on top data mining venues such as KDD, ICDE, WWW, and TKDE. His research interest primarily lies in the efficient and robust graph representation learning, such as graph condensation and imbalanced graph learning.</li>
<br>
<li><strong>Dr. Junliang Yu</strong> is an ARC DECRA Fellow at the University of Queensland. His research interests include recommender systems, data-centric AI, and graph learning. With over 30 papers published in premier venues such as KDD, WWW, ICDM, CIKM, AAAI, SIGIR, WSDM, TKDE, and VLDB Journal, he is a recognized contributor in his field.</li>

<br>
<li><strong>Dr. Ruihong Qiu</strong> is currently a Lecturer at The University of Queensland. He was awarded 2025 Discovery Early Career Researcher Award (DECRA) from the Australian Research Council (ARC). He received his PhD degree in Computer Science at The University of Queensland in 2022. His research mainly focuses on recommender systems, graph neural networks, and data science for cross-disciplinary projects, with publications on top-tier venues such as SIGIR, ICDM, WSDM, CIKM, TKDE, TOIS etc.</li>

<br>
<li><strong>Dr. Tong Chen</strong> is a Senior Lecturer at The University of Queensland, and an awardee of the 2023 Discovery Early Career Researcher Award (DECRA) from the Australian Research Council (ARC). Dr. Chen’s research on lightweight, on-device, and trustworthy recommender systems has been published on top-tier international venues such as KDD, SIGIR, WWW, TKDE, WSDM, TNNLS, TOIS, and CIKM. </li>

<br>
<li><strong>A/Prof. Quoc Viet Hung Nguyen</strong> is an Associate Professor and an ARC DECRA Fellow in Griffith University. He earned his Master and PhD degrees from EPFL (Switzerland). His research focuses on Data Integration, Data Quality, Recommender Systems, and Big Data Visualization, with special emphasis on web data, social data, IoT data and satellite data. He has published 180+ papers in top-tier conferences (e.g., SIGMOD, VLDB, ICDE, NeurIPS, KDD, SIGIR, WWW, etc.) and high impact journals (e.g., TPAMI, VLDBJ, TKDE, TOIS, etc.). He has served as senior PC for several A* conferences such as AAAI, IJCAI, TheWebConf, CIKM, ICONIP, etc.</li>

<br>
<li><strong>Prof. Zi Huang</strong> is a Professor and the Discipline Leader for Data Science in the School of EECS at The University of Queensland. She received her BSc degree from Department of Computer Science, Tsinghua University, China, and her PhD in Computer Science from School of EECS, The University of Queensland in 2001 and 2007 respectively. Her research interests mainly include multimedia, computer vision, social data analysis and knowledge discovery. She has been an Associate Editor of the VLDB Journal, ACM Transactions on Information Systems, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Transactions on Multimedia, and Pattern Recognition Journal. She has also served as a PC Co-Chair of ACM The Web Conference'25, ACM ICMR'23, and ACM CIKM'21.</li>

</ul>
</div>


## Our Papers on Graph Condensation
1. [Graph Condensation: A Survey](https://arxiv.org/abs/2401.11720v2) [📖](https://github.com/XYGaoG/Graph-Condensation-Papers)  
Transactions on Knowledge and Data Engineering (TKDE), 2025  
Xinyi Gao, Junliang Yu, Tong Chen, Guanhua Ye, Wentao Zhang, Hongzhi Yin  

1. [Rethinking and Accelerating Graph Condensation: A Training-Free Approach with Class Partition](https://arxiv.org/abs/2405.13707)  
ACM Web Conference (WWW), 2025  
Xinyi Gao, Guanhua Ye, Tong Chen, Wentao Zhang, Junliang Yu, Hongzhi Yin  

1. [Graph Condensation for Open-World Graph Learning](https://arxiv.org/abs/2405.17003)  
ACM SIGKDD Conference on Knowledge Discovery and Data Mining (SIGKDD), 2024  
Xinyi Gao, Tong Chen, Wentao Zhang, Yayong Li, Xiangguo Sun, Hongzhi Yin

1. [Graph Condensation for Inductive Node Representation Learning](https://arxiv.org/abs/2307.15967)  
IEEE International Conference on Data Engineering (ICDE), 2024  
Xinyi Gao, Tong Chen, Yilong Zang, Wentao Zhang, Quoc Viet Hung Nguyen, Kai Zheng, Hongzhi Yin

1. [Training-free Heterogeneous Graph Condensation via Data Selection](https://arxiv.org/abs/2412.16250)  
IEEE International Conference on Data Engineering (ICDE), 2025  
Yuxuan Liang, Wentao Zhang, Xinyi Gao, Ling Yang, Chong Chen, Hongzhi Yin, Yunhai Tong, Bin Cui

1. [RobGC: Towards Robust Graph Condensation](https://arxiv.org/abs/2406.13200)  
Xinyi Gao, Hongzhi Yin, Tong Chen, Guanhua Ye, Wentao Zhang, Bin Cui




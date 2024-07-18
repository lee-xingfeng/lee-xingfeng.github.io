---
permalink: /
title: "" 
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

**Yuan Sun (孙元)** is a Ph.D. candidate at the College of Computer Science, Sichuan University, advised by Prof. Dezhong Peng (彭德中). His current interests mainly focus on:
- **Image Set Classification**: it constructs an image set consisting of multiple images, and then measures the distance between two sets.
- **Cross-modal Retrieval**: it uses the information of one modal to retrieve the relevant content of another modal (such as text, image, audio, video, etc.).
- **Multi-view Clustering/Classification**: it integrates the supplementary and consistent information of multiple feature extractors for clustering or classification tasks.
- **AI4Science**: it utilizes Physics-Informed Neural Networks (PINNs) for solving forward and inverse PDE problems as well as their applications (such as nuclear reactor thermal hydraulics).

# 🔥 News
- \[**Publications**\]: Jul. 16, 2024, three papers were accepted by ACM Multimedia (ACM MM 2024)! Congrats to Honglin (Master), Longan (Undergrad), and coauthors! 🎉
- \[**Publications**\]: Jun. 26, 2024, one paper was accepted by IEEE Transactions on Image Processing (TIP)! Congrats to Yongxiang! 🎉
- \[**Publications**\]: Jun. 23, 2024, one paper was accepted by IEEE Transactions on Knowledge and Data Engineering (TKDE)! 🎉
- \[**Publications**\]: Apr. 20, 2024, one paper was accepted by IEEE Transactions on Multimedia (TMM)! 🎉
- \[**Publications**\]: Apr. 17, 2024, one paper was accepted by IJCAI 2024. Congrats to Kaiming (Master) and coauthors! 🎉
- \[**Publications**\]: Jan. 3, 2024, one paper was accepted by IEEE Transactions on Intelligent Transportation Systems (TITS). 🎉
- \[**Publications**\]: Sep. 22, 2023, one paper was accepted by AAAI 2024. 🎉
- \[**Publications**\]: Sep. 22, 2023, one paper was accepted by NeurIPS 2023. Congrats to Yang! 🎉
- \[**Publications**\]: Sep. 12, 2023, one paper was accepted by Expert Systems With Applications (ESWA)! 🎉
- \[**Publications**\]: Jul. 26, 2023, one paper was accepted by ACM Multimedia (ACM MM 2023)! 🎉
- \[**Services**\]: Jul. 28, 2023, I have been invited to be a PC member for AAAI 2024. 🎉
- \[**Publications**\]: Jul. 19, 2023, one paper was accepted by Information Fusion! Congrats to Xingfeng! 🎉
- \[**Publications**\]: Apr. 26, 2023, one paper was accepted by IEEE Transactions on Multimedia (TMM)! 🎉
- \[**Publications**\]: Feb. 14, 2023, one paper was accepted by IEEE Transactions on Image Processing (TIP)! 🎉
- \[**Publications**\]: Dec. 24, 2022, two papers were accepted by ACM Multimedia (ACM MM 2022)! Congrats to Jiali and coauthors! 🎉


# 📝 Publications 
(# denotes the corresponding author)
# 2024
- [20] Longan Wang, Yang Qin, **Yuan Sun**, Dezhong Peng, Xi Peng, Peng Hu, Robust Contrastive Cross-modal Hashing with Noisy Labels, **ACM MM 2024 (CCF-A类)**. 
- [19] Honglin Yuan, Shiyun Lai, Xingfeng Li, Jian Dai, **Yuan Sun#**, Zhenwen Ren#, Robust Prototype Completion for Incomplete Multi-view Clustering, **ACM MM 2024 (CCF-A类)**. 
- [18] **Yuan Sun**, Kaiming Liu, Yongxiang Li, Zhenwen Ren, Jian Dai, Dezhong Peng, Distribution Consistency Guided Hashing for Cross-Modal Retrieval, **ACM MM 2024 (CCF-A类)**. 
- [17] Yongxiang Li, Yang Qin, **Yuan Sun**, Dezhong Peng, Xi Peng, Peng Hu, RoMo: Robust Unsupervised Multimodal Learning with Noisy Pseudo Labels, **IEEE Transactions on Image Processing (TIP) (CCF-A类)**. 
- [16] **Yuan Sun**, Yang Qin, Yongxiang Li, Dezhong Peng, Xi Peng, Peng Hu, [Robust Multi-View Clustering with Noisy Correspondence](https://ieeexplore.ieee.org/document/10595464), **IEEE Transactions on Knowledge and Data Engineering (TKDE) (CCF-A类)**. [Code](https://github.com/sunyuan-cs/2024-TKDE-RMCNC)
- [15] **Yuan Sun**, Yang Qin, Dezhong Peng, Zhenwen Ren, Chao Yang, Peng Hu, [Dual Self-Paced Hashing for Image Retrieval](https://ieeexplore.ieee.org/abstract/document/10517459), **IEEE Transactions on Multimedia (TMM) (中科院一区)**. [Code](https://github.com/sunyuan-cs/DSPH)
- [14] Kaiming Liu, Yunhong Gong, Yu Cao, Zhenwen Ren, Dezhong Peng, **Yuan Sun#**, Dual Semantic Fusion Hashing for Multi-Label Cross-Modal Retrieval, **IJCAI 2024 (CCF-A类)**. 
- [13] **Yuan Sun**, Jian Dai, Zhenwen Ren, Qilin Li, Dezhong Peng, [Relaxed Energy Preserving Hashing for Image Retrieval](https://ieeexplore.ieee.org/abstract/document/10414409), **IEEE Transactions on Intelligent Transportation Systems (TITS) (中科院一区)**. [Code](https://github.com/sunyuan-cs/REPH_main)
- [12] **Yuan Sun**, Jian Dai, Zhenwen Ren, Yingke Chen, Dezhong Peng, Peng Hu, [Dual Self-Paced Cross-Modal Hashing](https://ojs.aaai.org/index.php/AAAI/article/view/29441), **AAAI 2024 (CCF-A类)**.
  
# 2023
- [11] Yang Qin, **Yuan Sun**, Dezhong Peng, Joey Tianyi Zhou, Xi Peng, Peng Hu, [Cross-modal Active Complementary Learning with Self-refining Correspondence](https://proceedings.neurips.cc/paper_files/paper/2023/file/4e580cdd54fe38ca9a5b8ea6fe99bb44-Paper-Conference.pdf), **NeurIPS 2023 (CCF-A类)**. [Code](https://github.com/QinYang79/CRCL)
- [10] **Yuan Sun**, Dezhong Peng, Zhenwen Ren, [Discrete Aggregation Hashing for Image Set Classification](https://www.sciencedirect.com/science/article/pii/S0957417423021176), **Expert Systems With Applications (中科院一区)**.
- [9] **Yuan Sun**, Dezhong Peng, Jian Dai, Zhenwen Ren, [Stepwise Refinement Short Hashing for Image Retrieval](https://openreview.net/pdf?id=9ol1HoBfir), **ACM MM 2023 (CCF-A类)**.
- [8] Xingfeng Li, Yinghui Sun, Quansen Sun, Zhenwen Ren, **Yuan Sun**, [Cross-view Graph Matching Guided Anchor Alignment for Incomplete Multi-view Clustering](https://www.sciencedirect.com/science/article/pii/S1566253523002579), **Information Fusion (中科院一区)**.
- [7] **Yuan Sun**, Zhenwen Ren, Peng Hu, Dezhong Peng, Xu Wang, [Hierarchical Consensus Hashing for Cross-Modal Retrieval](https://ieeexplore.ieee.org/document/10119165), **IEEE Transactions on Multimedia (TMM) (中科院一区)**. [Code](https://github.com/sunyuan-cs/HCCH)
- [6] **Yuan Sun**, Xu Wang, Dezhong Peng, Zhenwen Ren, Xiaobo Shen, [Hierarchical Hashing Learning for Image Set Classification](https://ieeexplore.ieee.org/document/10061433), **IEEE Transactions on Image Processing (TIP) (CCF-A类)**.

# 2022
- [5] **Yuan Sun**, Dezhong, Haixiao Huang, Zhenwen Ren, [Feature and Semantic Views Consensus Hashing for Image Set Classification](https://dl.acm.org/doi/abs/10.1145/3503161.3547876), **ACM MM 2022 (CCF-A类)**.
- [4] Jiali You, Zhenwen Ren, Quansen Sun, **Yuan Sun**, Xingfeng Li, [Approximate Shifted Laplacian Reconstruction for Multiple Kernel Clustering](https://dl.acm.org/doi/abs/10.1145/3503161.3548307), **ACM MM 2022 (CCF-A类)**.

# Before 2021
- [3] **Yuan Sun**, Zhenwen Ren, Chao Yang, Quansen Sun, Liwan Chen, Yanglong Ou, [Face Image Set Classification with Self-weighted Latent Sparse Discriminative Learning](https://link.springer.com/article/10.1007/s00521-020-05479-1), **Neural Computing and Applications (中科院二区)**.
- [2] Chao Yang, Zhenwen Ren, Quansen Sun, Mingna Wu, Maowei Yin, **Yuan Sun**, [Joint Correntropy Metric Weighting and Block Diagonal Rgularizer for Robust Multiple Kernel Subspace Clustering](https://www.sciencedirect.com/science/article/pii/S0020025519304803), **Information Sciences (中科院一区)**.
- [1] **Yuan Sun**, Zhenwen Ren, Chao Yang, Haoyun Lei, [Latent Sparse Discriminative Learning for Face Image Set Classification](https://link.springer.com/chapter/10.1007/978-981-15-7670-6_13), **International Conference on Neural Computing for Advanced Applications (EI)**.


# 🎖 Honors and Awards
- 四川省计算机学会年度优秀学生论文，2024.01.
- 中国自动化学会科技进步奖二等奖，2023.11.
- 国家奖学金，2023.09.
- 四川大学优秀研究生，2023.09.
- 博士一等学业奖学金，2023.09-2025.06.
- 博士创新奖学金，2023.03.
- 校级优秀硕士毕业论文，2021.06.
- NCAA 2020最佳论文提名奖.
- 成都市技术能手（成都市人力资源与保障局颁发），2018.12.
- 20余项学生科技竞赛获奖.


# 🙋 Services 
- Program Committee Member:
    - AAAI 2025.
    - AAAI 2024, CVPR 2024, IJCAI 2024, ACM MM 2024, ICML 2024, ECCV 2024, PRCV 2024, NeurIPS 2024.
    - ACM MM 2023, PRCV 2023.
- Journal Reviewer:
    - IEEE Transactions on Image Processing.
    - IEEE Transactions on Knowledge and Data Engineering.
    - IEEE Transactions on Neural Networks and Learning Systems.
    - IEEE Transactions on Circuits and Systems for Video Technology.
    - IEEE Transactions on Big Data.
    - IEEE Transactions on Computational Social Systems.
    - ACM Transactions on Multimedia Computing, Communications and Applications (TOMM).
    - IEEE Signal Processing Letters.
    - Neural Networks.
    - Information Fusion.
    - Expert Systems With Applications.
    - Neurocomputing.
    - Neural Computing and Applications.
    - CAAI Transactions on Intelligence Technology.
    - Data Science and Management.
    - The Visual Computer.
- Associate Editor:
    - ICARM 2024
- Workshop Chair:
    - CVDL 2024.


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

**Xingfeng Li (李杏峰)**  is a Ph.D. candidate at the Nanjing University of Science and Technology, Nanjing, Jiangsu, advised by Profs. Quansen Sun and Zhenwen Ren. Currently, I am a visiting student in A*STAR Centre for Frontier AI Research (CFAR), Singapore, supervised by Prof. Ivor W. Tsang and Associate prof. Yuangang Pan. His current interests mainly focus on:
- **Mult-view/Multi-kernel Clustering**: it integrates the supplementary and consistent information of multiple feature extractors for clustering tasks.
- **Feature Extraction and Feature Selection**: it extracts or selects the important features of high-dimensional data for addressing the curse of dimensionality.
- **Hashing learning**: it transforms data from original space to Hamming space for fast searching.
- **Deep learning**: it uses deep learning for clustering and classification tasks.


# 🔥 News
- \[**Publications**\]: Dec. 10, 2024, two paper were accepted by AAAI 2025! Congrats to Zhongwen (Master), and coauthors! 🎉
- \[**Publications**\]: Nov. 5, 2024, one paper were accepted by Information Fusion! 🎉
- \[**Publications**\]: Aug. 18, 2024, one paper was accepted by IEEE Transactions on Multimedia (TMM)! 🎉
- \[**Publications**\]: Jul. 16, 2024, two papers were accepted by ACM Multimedia (ACM MM 2024)! Congrates to Honglin (Master), Yinghui, and coauthors! 🎉
- \[**Publications**\]: Apr. 18, 2024, one paper was accepted by IJCAI 2024! 🎉
- \[**Publications**\]: Mar. 1, 2024, one paper was accepted by CVPR 2024! Congrats to Linhan and coauthors! 🎉
- \[**Publications**\]: Jul. 26, 2023, one paper was accepted by ACM Multimedia (ACM MM 2023)! 🎉
- \[**Publications**\]: Jul. 19, 2023, one paper was accepted by Information Fusion! 🎉
- \[**Publications**\]: Feb. 1, 2023, one paper was accepted by Pattern Recognition! 🎉
- \[**Publications**\]: Jan. 9, 2023, one paper was accepted by IEEE Transactions on Computational Social Systems (TCSS)! 🎉
- \[**Publications**\]: Dec. 24, 2022, two papers was accepted by ACM Multimedia (ACM MM 2022)! Congrats to Jiali and coauthors! 🎉
- \[**Publications**\]: Dec. 15, 2022, one papers was accepted by IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)! 🎉


# 📝 Publications 
(# denotes the corresponding author)
# 2025
- [19] Shilin Xu, Yuan Sun#, **Xingfeng Li**, Siyuan Duan, Zhenwen Ren, Zheng Liu, Dezhong Peng#, Noisy Label Calibration for Multi-view Classification, AAAI 2025 (CCF-A类). [Code avaliable](https://github.com/sstaree/NLC)
- [18] Zhongwen Wang, **Xingfeng Li#**, Yinghui Sun, Quansen Sun, Yuan Sun, Han Ling, Jian Dai, Zhenwen Ren [TPCH: Tensor-interacted Projection and Cooperative Hashing for Multi-view Clustering](https://arxiv.org/abs/2412.18847), **AAAI 2025 (CCF-A类)**. [Code avaliable](https://github.com/jankin-wang/TPCH)
# 2024
- [17] **Xingfeng Li**, Yuangang Pan, Yuan Sun, Yinghui Sun,  Quansen Sun, Zhenwen Ren, Ivor W. Tsang, [Scalable Unpaired Multi-view Clustering with Bipartite Graph Matching](https://www.sciencedirect.com/science/article/abs/pii/S1566253524005645), **Information Fusion 2024 (中科院一区)**.
- [16] **Xingfeng Li**, Yuangang Pan, Yuan Sun, Quansen Sun, Yinghui Sun, Ivor W. Tsang, Zhenwen Ren, [Incomplete Multi-view Clustering with Paired and Balanced Dynamic Anchor Learning](https://ieeexplore.ieee.org/document/10812848), **IEEE Transactions on Multimedia 2024 (中科院一区)**. [Code avaliable](https://github.com/lee-xingfeng/PBDAL)
- [15] Yinghui Sun, **Xingfeng Li#**, Sun Quansen, Min-Ling Zhang, Zhenwen Ren, [Improved Weighted Tensor Schatten 𝑝-Norm for Fast Multi-view Graph Clustering](https://openreview.net/pdf?id=qQph6GscZZ), **ACM MM 2024 (CCF-A类)**. [Code avaliable](https://github.com/lee-xingfeng/IWTSN) 
- [14] Honglin Yuan, Shiyun Lai, **Xingfeng Li**, Jian Dai, Yuan Sun, Zhenwen Ren, [Robust Prototype Completion for Incomplete Multi-view Clustering](https://openreview.net/pdf?id=4BrIZo3Ave), **ACM MM 2024 (CCF-A类)**. [Code avaliable](https://github.com/hl-yuan/RPCIC)
- [13] **Xingfeng Li**, Yuangang Pan, Yinghui Sun, Quansen Sun, Ivor W. Tsang, Zhenwen Ren, [Fast Unpaired Multi-view Clustering](https://www.ijcai.org/proceedings/2024/0496.pdf), **IJCAI 2024 (CCF-A类)**.
- [12] Han Ling, Quansen Sun, Yinghui Sun, Xian Xu, **Xingfeng Li**, [ADFactory: An Effective Framework for Generalizing Optical Flow with Nerf](https://openaccess.thecvf.com/content/CVPR2024/papers/Ling_ADFactory_An_Effective_Framework_for_Generalizing_Optical_Flow_with_NeRF_CVPR_2024_paper.pdf), **CVPR 2024 (CCF-A类)**. 

  
# 2023
- [11] **Xingfeng Li**, Yinghui Sun, Quansen Sun, Jia Dai, Zhenwen Ren, [Distribution Consistency based Fast Anchor Imputation for Incomplete Multi-view Clustering](https://dl.acm.org/doi/abs/10.1145/3581783.3612483), **ACM MM 2023 (CCF-A类)**. 
- [10] **Xingfeng Li**, Yinghui Sun, Quansen Sun, Zhenwen Ren, Yuan Sun, [Cross-view Graph Matching Guided Anchor Alignment for Incomplete Multi-view Clustering](https://www.sciencedirect.com/science/article/abs/pii/S1566253523002579), **Information Fusion 2023 (中科院一区)**.
- [9] **Xingfeng Li**, Zhenwen Ren, Quansen Sun, Zhi Xu, [Auto-weighted tensor schatten p-norm for robust multi-view graph clustering](https://www.sciencedirect.com/science/article/abs/pii/S0031320322005635), **Pattern Recognition 2023 (中科院一区)**.
- [8] **Xingfeng Li**, Yinghui Sun, Quansen Sun, Zhenwen Ren, [Enforced block diagonal graph learning for multikernel clustering](https://ieeexplore.ieee.org/abstract/document/10012408), **IEEE Transactions on Computational Social Systems 2023 (中科院二区)**.

# 2022
- [7] **Xingfeng Li**, Yinghui Sun, Quansen Sun, Zhenwen Ren, [Consensus cluster center guided latent multi-kernel clustering](https://ieeexplore.ieee.org/abstract/document/9987521), **IEEE Transactions on Circuits and Systems for Video Technology (中科院一区)**.
- [6] Jiali You, Zhenwen Ren, Quansen Sun, Yuan Sun, **Xingfeng Li**, [Approximate shifted laplacian reconstruction for multiple kernel clustering](https://dl.acm.org/doi/abs/10.1145/3503161.3548307), **ACM MM 2022 (CCF-A类)**. 
- [5] **Xingfeng Li**, Quansen Sun, Zhenwen Ren, Yinghui Sun, [Dynamic incomplete multi-view imputing and clustering](https://dl.acm.org/doi/abs/10.1145/3503161.3548245), **ACM MM 2022 (CCF-A类)**. 
- [4] **Xingfeng Li**, Yinghui Sun, Zhenwen Ren, Quansen Sun, [RPCA-Induced Graph Tensor Learning for Incomplete Multi-view Inferring and Clustering](https://link.springer.com/chapter/10.1007/978-981-19-6142-7_7), **International Conference on Neural Computing for Advanced Applications (EI)**.

# Before 2021
- [3] Zhenwen Ren, **Xingfeng Li**, Mithun Mukherjee, Yuqing Huang, Quansen Sun, Zhen Huang, Liwan Chen, [Robust multi-view graph clustering in latent energy-preserving embedding space](https://www.sciencedirect.com/science/article/abs/pii/S0950705120306183), **Information Sciences (中科院一区)**.
- [2] **Xingfeng Li**, Zhenwen Ren, Haoyun Lei, Yuqing Huang, Quansen Sun, Liwan Chen, [Multiple kernel clustering with pure graph learning scheme](https://www.sciencedirect.com/science/article/abs/pii/S0925231220316271), **Neurocomputing (中科院二区)**.
- [1] Haoran Li, Zhenwen Ren, Mithun Mukherjee, Yuqing Huang, Quansen Sun, **Xingfeng Li**, Liwan Chen, [Robust energy preserving embedding for multi-view subspace clustering](https://www.sciencedirect.com/science/article/abs/pii/S0950705120306183), **Knowledge-Based Systems (中科院一区)**.



# 🎖 Honors and Awards
- 南京理工大学优秀博士研究生培养对象，2024.07.
- 南京理工大学计算机学院-院长奖章，2024.06.
- 中国自动化学会科技进步奖二等奖，2023.11.
- 研究生国家奖学金，教育部，2023.09.
- 江苏省研究生科研创新计划项目(主持)，江苏省教育厅，2023.09.
- 国家公派留学项目(CSC-新加坡)，国家留学基金管理委员会，2023.08.
- 南京理工大学优秀研究生，2023.09, 2024.09.
- 博士一等学业奖学金，2021.09-2024.06.




# 🙋 Services 
- Program Committee Member:
    - AAAI 2025, ICLR 2025, CVPR 2025, ICML2025.
    - AAAI 2024, CVPR 2024, IJCAI 2024, ACM MM 2024, ICML 2024, NeurIPS 2024.
    - ACM MM 2023, PRCV 2023.
- Journal Reviewer:
    - IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI)
    - IEEE Transactions on Knowledge and Data Engineering (TKDE)
    - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
    - IEEE Transactions on Cybernetics (TCYB)
    - Transactions on Big Data (TBD)
    - Artificial Intelligence Review
    - Transactions on Computational Social Systems
    - Neural Networks.
    - Information Fusion.
    - Neurocomputing.
    - CAAI Transactions on Intelligence Technology.
    - The Visual Computer.



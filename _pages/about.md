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

**Xingfeng Li (李杏峰)**  is a Ph.D. candidate at the Nanjing University of Science and Technology, Nanjing, Jiangsu, advised by Profs. [Quansen Sun](https://cs.njust.edu.cn/e4/0c/c1730a189452/page.htm) and [Zhenwen Ren](http://unix8.net/). Currently, I am a visiting student in A*STAR Centre for Frontier AI Research (CFAR), Singapore, supervised by IEEE Fellow. [Ivor W. Tsang](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang) and Senior Scientist. [Yuangang Pan](https://yuangang-pan.github.io/profile/). His current interests mainly focus on:
- **Mult-view/Multi-kernel Clustering**: it integrates the supplementary and consistent information of multiple feature extractors for clustering tasks.
- **Feature Extraction and Feature Selection**: it extracts or selects the important features of high-dimensional data for addressing the curse of dimensionality.
- **Hashing learning**: it transforms data from original space to Hamming space for fast searching.
- **Deep learning**: it uses deep learning for clustering and classification tasks.


# 🔥 News
- \[**Publications**\]: Nov. 8, 2025, two papers were accepted by AAAI 2026! Congrats to Yufeng, Taotao, and coauthors! 
- \[**Publications**\]: July. 6, 2025, one paper were accepted by ACM MM 2025! Congrats to Junyu and coauthors! 🎉
- \[**Publications**\]: May. 1, 2025, one paper was accepted by ICML 2025! Congrats to Honglin, and coauthors! 🎉
- \[**Publications**\]: Apr. 29, 2025, one paper was accepted by IJCAI 2025! Congrats to Deyin, and coauthors! 🎉
- \[**Publications**\]: Apr. 5, 2025, one paper was accepted by Neural Networks! 🎉
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
{% comment %}
  取可见集合：公开（show_private=false）仅显示 public=true；自己看（true）显示全量
{% endcomment %}
{% assign all = site.data.pubs %}
{% if site.show_private %}
  {% assign pubs_visible = all %}
{% else %}
  {% assign pubs_visible = all | where: "public", true %}
{% endif %}

{% comment %} 排序：按年份降序；同年内保持写入顺序或可加自定义 rank 字段 {% endcomment %}
{% assign pubs_sorted = pubs_visible | sort: "year" | reverse %}

{% comment %} 计算全局编号起点（当前可见总数） {% endcomment %}
{% assign N = pubs_sorted | size %}

{% comment %} 分年分组，按年降序展示 {% endcomment %}
{% assign groups = pubs_sorted | group_by: "year" | sort: "name" | reverse %}

{% for g in groups %}
## {{ g.name }}
{% for p in g.items %}

- [{{ N }}] {{ p.authors }}, {{ p.title }}, **{{ p.venue }}**.{% if p.links %}
  {%- if p.links.pdf %} [PDF]({{ p.links.pdf }}){%- endif -%}
  {%- if p.links.arxiv %} [arXiv]({{ p.links.arxiv }}){%- endif -%}
  {%- if p.links.doi %} [DOI]({{ p.links.doi }}){%- endif -%}
  {%- if p.links.code %} [Code]({{ p.links.code }}){%- endif -%}
{%- endif %}

{% assign N = N | minus: 1 %}
{% endfor %}
{% endfor %}

**Total (public view):** {{ pubs_sorted | size }}
{% assign total_all = site.data.pubs | size %}
{% if total_all > pubs_sorted.size %}
  &nbsp;&nbsp;**Total (including private):** {{ total_all }}
{% endif %}


# 🎖 Honors and Awards
- 浦芯精英奖学金，南京市浦口区工业和信息化局，2024.12.
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
    - AAAI 2026, ICLR 2026, CVPR 2026
    - AAAI 2025, ICLR 2025, CVPR 2025, ICML2025, ICCV 2025, ACM MM 2025, NeurIPS 2025.
    - AAAI 2024, CVPR 2024, IJCAI 2024, ACM MM 2024, ICML 2024, NeurIPS 2024.
    - ACM MM 2023, PRCV 2023.
- Journal Reviewer:
    - IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI)
    - IEEE Transactions on Image Processing (TIP)
    - IEEE Transactions on Knowledge and Data Engineering (TKDE)
    - IEEE Transactions on Neural Networks and Learning（TNNLS）
    - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
    - IEEE Transactions on Cybernetics (TCYB)
    - Transactions on Big Data (TBD)
    - Pattern Recognition
    - Artificial Intelligence Review
    - Transactions on Computational Social Systems
    - Neural Networks.
    - Information Fusion.
    - Neurocomputing.
    - CAAI Transactions on Intelligence Technology.
    - The Visual Computer.

{% assign pubs = site.data.pubs %}
{% assign count_ccfa = 0 %}
{% assign count_cas1 = 0 %}

{% for p in pubs %}
  {% if p.venue contains "CCF-A" %}
    {% assign count_ccfa = count_ccfa | plus: 1 %}
  {% endif %}
  {% if p.venue contains "中科院一区" %}
    {% assign count_cas1 = count_cas1 | plus: 1 %}
  {% endif %}
{% endfor %}

<!--
  ✅ Private Stats
  CCF-A papers: {{ count_ccfa }}
  中科院一区 papers: {{ count_cas1 }}
-->

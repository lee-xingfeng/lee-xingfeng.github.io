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

<span class="anchor" id="about-me"></span>

**Xingfeng Li (李杏峰)** is an Associate Professor at the Southwest University of Science and Technology, Mianyang, Sichuan, where he works with Prof. Zhenwen Ren. He received his Ph.D. degree from Nanjing University of Science and Technology, supervised by Prof. [Quansen Sun](https://cs.njust.edu.cn/e4/0c/c1730a189452/page.htm) , and his Master’s degree under the supervision of Prof. [Zhenwen Ren](http://unix8.net/). He is currently a visiting scholar at A*STAR Centre for Frontier AI Research (CFAR), Singapore, supervised by IEEE Fellow [Ivor W. Tsang](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang) and Senior Scientist Yuangang Pan [Yuangang Pan](https://yuangang-pan.github.io/profile/).

His current interests mainly focus on:
- **Multi-modal learning**: it integrates the supplementary and consistent information of multiple feature extractors for clustering tasks.
- **Infrared and Visible Image Fusion**: it integrates complementary thermal and texture information from infrared and visible modalities to enhance scene perception.
- **Deep learning**: it uses deep learning for clustering and classification tasks.

# 🔥 News
- \[**Publications**\]: May. 1, 2026, one paper was accepted by The International Conference on Machine Learning 2026! Congrats to Hao and coauthors🎉
- \[**Publications**\]: Apr. 16, 2026, one paper was accepted by Neural Networks! 🎉
- \[**Publications**\]: Mar. 20, 2026, one paper was accepted by Pattern Recognition! Congrats to Shen and coauthors! 🎉
- \[**Publications**\]: Mar. 12, 2026, one paper was accepted by Pattern Recognition! Congrats to Hao and coauthors! 🎉
- \[**Publications**\]: Feb. 21, 2026, one paper was accepted by IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR 2026)! 🎉
- \[**Publications**\]: Nov. 9, 2025, one paper was accepted by Neurocomputing 2026! Congrats to Xinyue and coauthors! 🎉
- \[**Publications**\]: Nov. 8, 2025, two papers were accepted by AAAI 2026! Congrats to Yufeng, Taotao, and coauthors! 🎉
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
- \[**Publications**\]: Dec. 24, 2022, two papers was accepted by ACM Multimedia (ACM MM 2022)! 🎉
- \[**Publications**\]: Dec. 15, 2022, one papers was accepted by IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)! 🎉

# 📝 Publications
(# denotes the corresponding author)

{% comment %}
Data source: /_data/pubs.yml  -> site.data.pubs
show_private=false: only public=true
show_private=true : show all
{% endcomment %}

{% assign all = site.data.pubs %}

{% if all == nil %}
<div style="padding:12px;border:1px solid #f0c36d;background:#fff8e1;border-radius:8px;">
  <b>⚠️ Publications data not found.</b><br/>
  Please ensure <code>/_data/pubs.yml</code> is valid YAML and accessible as <code>site.data.pubs</code>.
</div>
{% else %}

  {% if site.show_private %}
    {% assign pubs_visible = all %}
  {% else %}
    {% assign pubs_visible = all | where: "public", true %}
  {% endif %}

  {% assign pubs_sorted = pubs_visible | sort: "year" %}
  {% assign N = pubs_sorted | size %}
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

{% comment %} -------- Stats (reuse pubs_visible) -------- {% endcomment %}

  {% assign ccfa = 0 %}
  {% assign ccfa_first = 0 %}
  {% assign ccfa_corr = 0 %}

  {% assign cas1 = 0 %}
  {% assign cas1_first = 0 %}
  {% assign cas1_corr = 0 %}

  {% for p in pubs_visible %}
    {% assign authors_plain = p.authors | replace: "*", "" %}

    {% assign is_ccfa = false %}
    {% if p.venue and p.venue contains "CCF-A" %}
      {% assign is_ccfa = true %}
    {% endif %}

    {% assign is_cas1 = false %}
    {% if p.venue and p.venue contains "中科院一区" %}
      {% assign is_cas1 = true %}
    {% endif %}

    {% assign first_raw = p.authors | split: "," | first | strip %}
    {% assign first_plain = first_raw | replace: "*", "" %}
    {% assign is_first = false %}
    {% if first_plain contains "Xingfeng Li" %}
      {% assign is_first = true %}
    {% endif %}

    {% assign is_corr = false %}
    {% if authors_plain contains "Xingfeng Li#" %}
      {% assign is_corr = true %}
    {% endif %}

    {% if is_ccfa %}
      {% assign ccfa = ccfa | plus: 1 %}
      {% if is_first %}{% assign ccfa_first = ccfa_first | plus: 1 %}{% endif %}
      {% if is_corr  %}{% assign ccfa_corr  = ccfa_corr  | plus: 1 %}{% endif %}
    {% endif %}

    {% if is_cas1 %}
      {% assign cas1 = cas1 | plus: 1 %}
      {% if is_first %}{% assign cas1_first = cas1_first | plus: 1 %}{% endif %}
      {% if is_corr  %}{% assign cas1_corr  = cas1_corr  | plus: 1 %}{% endif %}
    {% endif %}
  {% endfor %}

<!--
✅ Private Stats (safe)
CCF-A
  total:            {{ ccfa }}
  first-author:     {{ ccfa_first }}
  corresponding:    {{ ccfa_corr }}

中科院一区
  total:            {{ cas1 }}
  first-author:     {{ cas1_first }}
  corresponding:    {{ cas1_corr }}
-->

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
  - AAAI 2025, ICLR 2025, CVPR 2025, ICML 2025, ICCV 2025, ACM MM 2025, NeurIPS 2025
  - AAAI 2024, CVPR 2024, IJCAI 2024, ACM MM 2024, ICML 2024, NeurIPS 2024
  - ACM MM 2023, PRCV 2023
- Journal Reviewer:
  - IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI)
  - IEEE Transactions on Image Processing (TIP)
  - IEEE Transactions on Information Forensics and Security (TIFS)
  - IEEE Transactions on Knowledge and Data Engineering (TKDE)
  - IEEE Transactions on Neural Networks and Learning (TNNLS)
  - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
  - IEEE Transactions on Cybernetics (TCYB)
  - IEEE Transactions on Multimedia (TMM)
  - Transactions on Big Data (TBD)
  - Knowledge-Based Systems
  - Pattern Recognition
  - Artificial Intelligence Review
  - Transactions on Computational Social Systems
  - Neural Networks
  - Information Fusion
  - Neurocomputing
  - CAAI Transactions on Intelligence Technology
  - The Visual Computer

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

I am a Ph.D. student in Computer Science at Shanghai Jiao Tong University (SJTU), supervised by Prof. [Junchi Yan (严骏驰)](https://thinklab.sjtu.edu.cn/), and a member of the prestigious Wen-Tsun Wu AI Honorary Doctoral Class. I completed my undergraduate degree at SJTU in 2023, majoring in Artificial Intelligence within the Pilot Class for Outstanding Talent, an elite program reserved for top 5% of students.

My research centers on deep learning for complex optimization problems, with a particular emphasis on discrete combinatorial optimization. I have authored seven papers in leading conferences and journals, including four as (co-)first author at CVPR 2023, ICML 2024, NeurIPS 2025, and ICLR 2026. Additionally, I serve as a reviewer for top-tier venues, e.g., ICML, NeurIPS, ICLR, and TPAMI.




# 🔥 News
- *2026.01*: &nbsp;🎉 One paper on representation learning for combinatorial optimization is accepted by ICLR 2026!
- *2025.09*: &nbsp;🎉 One paper on sampling approach for combinatorial optimization is accepted by NeurIPS 2025!

# 📝 Publications 

## Combinatorial Optimization

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/iclr26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ConRep4CO: Contrastive Representation Learning of Combinatorial Optimization Instances across Types](https://openreview.net/pdf?id=OXRnvOOiAf)

**Ziao Guo**, Yang Li, Shiyue Wang, Junchi Yan

- This work proposes a contrastive pre-training framework for combinatorial optimization (CO) through an instance-level contrastive learning objective that aligns original CO problem instances with their canonical SAT-form counterparts.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/nips25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fractional Langevin Dynamics for Combinatorial Optimization via Polynomial-Time Escape](https://openreview.net/forum?id=BZ0igCEeoU)

**Ziao Guo**\*, Shiyue Wang*, Changhong Lu, Junchi Yan

- This work proposes a sampling technique for solving combinatorial optimization problems, and theoretically proves that this approach exhibits a polynomial time for escaping local minima, compared with exponential escape time of original LD in previous work.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024 (Spotlight)</div><img src='images/icml24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ ACM-MILP: Adaptive Constraint Modification via Grouping and Selection for Hardness-Preserving MILP Instance Generation](https://openreview.net/pdf?id=qDAAMmGsGw)

**Ziao Guo**, Yang Li, Chang Liu, Wenli Ouyang, Junchi Yan

- This work proposes a hardness-preserving MILP instance generation framework with adaptive constraint modification and constraint interrelation modeling.
- [![](https://img.shields.io/github/stars/Thinklab-SJTU/ACM-MILP?style=social&label=ACM-MILP)](https://github.com/Thinklab-SJTU/ACM-MILP) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/cvpr23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Learning of Partial Graph Matching via Differentiable Top-K](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Deep_Learning_of_Partial_Graph_Matching_via_Differentiable_Top-K_CVPR_2023_paper.pdf)

**Ziao Guo**\*, Runzhong Wang*, Shaofei Jiang, Xiaokang Yang, Junchi Yan

- This work proposes the first neural solver for partial graph matching (GM) problem, and release a new benchmark for partial GM.
- [![](https://img.shields.io/github/stars/Thinklab-SJTU/ThinkMatch?style=social&label=ThinkMatch)](https://github.com/Thinklab-SJTU/ThinkMatch) [![](https://img.shields.io/github/stars/Thinklab-SJTU/IMCPT-SparseGM-dataset?style=social&label=IMCPT-SparseGM-dataset)](https://github.com/Thinklab-SJTU/IMCPT-SparseGM-dataset)

</div>
</div>

- ![](https://img.shields.io/badge/JMLR 2024-darkblue) [Pygmtools: A python graph matching toolkit](https://www.jmlr.org/papers/volume25/23-0572/23-0572.pdf)<br>Runzhong Wang, **Ziao Guo**, Wenzheng Pan, Jiale Ma, Yikai Zhang, Nan Yang, et al.  [![](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social&label=pygmtools)](https://github.com/Thinklab-SJTU/pygmtools)

- ![](https://img.shields.io/badge/ICLR 2024-darkblue) [Towards Imitation Learning to Branch for MIP: A Hybrid Reinforcement Learning Based Sample Augmentation Approach](https://openreview.net/pdf?id=NdcQQ82mfy)<br>Changwen Zhang, Wenli Ouyang, Hao Yuan, Liming Gong, Yong Sun, **Ziao Guo**, et al.

- ![](https://img.shields.io/badge/ICML 2023-darkblue) [LinSATNet: the positive linear satisfiability neural networks](https://proceedings.mlr.press/v202/wang23at/wang23at.pdf) <br>Runzhong Wang, Yunhao Zhang, **Ziao Guo**, Tianyi Chen, Xiaokang Yang, Junchi Yan.  [![](https://img.shields.io/github/stars/Thinklab-SJTU/LinSATNet?style=social&label=LinSATNet)](https://github.com/Thinklab-SJTU/LinSATNet)



# 🎖 Honors and Awards
- *2024 2025* Wen-Tsun Wu Scholarship
- *2024* Yang Jiachi Scholarship (Top 1%)
- *2023* Shanghai Jiao Tong University Merit Graduate
- *2021* Tencent Scholarship (Top 1%)
- *2021* Finalist Winner of Mathematical Contest in Modeling (Top 2%)

# 📖 Educations
- *2023.09 - present*, PhD of Comupter Science and Technology, Shanghai Jiao Tong University (SJTU, 上海交通大学)
- *2019.09 - 2023.06*, B.S in Artificial Intelligence (The Pilot Class for Outstanding Talent), Shanghai Jiao Tong University (SJTU, 上海交通大学)


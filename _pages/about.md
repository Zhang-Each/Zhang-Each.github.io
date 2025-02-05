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


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

I am now a master student of computer science in Zhejiang University [KG Lab](https://www.zjukg.org/), advised by Prof. [Huajun Chen](https://scholar.google.com/citations?user=T6om-m4AAAAJ&hl=zh-CN&oi=ao) and Prof. [Wen Zhang](https://scholar.google.com/citations?user=Ig9ho4kAAAAJ&hl=zh-CN). My research interest includes **Multi-modal Knowledge Graphs** (<span style="color:#D70761;">MMKG</span>), **Large Language Models** (<span style="color:#c68864">LLM</span>), and their application (<span style="color:SeaGreen;">KG&LLM Application</span>) in real-world scenarios. I have published several papers at the top conferences such as SIGIR, ACL, ACM MM, SIGKDD, ICDE, AAAI, COLING, ISWC, IJCNN, NLPCC. Here is an overview of my research area and publications:

<img src='images/bigmap.png' align="center" width="60%">

I maintain a online noteboook (mainly in Chinese) on [this link](https://zhang-each.github.io/My-CS-Notebook/) to share my learning notes and daily life.

I am an incoming Ph.D. student of Zhejiang University in 2025 Spring.


# 🔥 News
- *2025.01*: 😄 We pre-print our paper [Have We Designed Generalizable Structural Knowledge Promptings? Systematic Evaluation and Rethinking](https://arxiv.org/abs/2501.00244).
- *2024.12*: 🎉 Our papers about [Fine-grained Multi-modal Entity Representation](https://arxiv.org/abs/2404.09468) and LLM-based Knowledge Graph Completion has been accepted by [AAAI 2025](https://aaai.org/conference/aaai/aaai-25/).
- *2024.07*: 🎉 Our paper about [Structural Knowledge Incorporation for LLMs](https://arxiv.org/pdf/2310.06671.pdf) has been accepted by [ACM MM 2024](https://2024.acmmm.org/) (oral presentation).
- *2024.05*:  😄 We pre-print two papers about [knowledge pre-training for diverse downstream tasks](https://arxiv.org/abs/2405.13085) and [mixture of modality knowledge experts in multi-modal knowledge graph](https://arxiv.org/abs/2405.16869).
- *2024.05*: 🎉 Our paper about Knowledgeable Alignment for LLMs has been accepted by [ACL 2024](https://2024.aclweb.org/) (Findings).
- *2024.03*: 🎉 [Our paper](https://www.techrxiv.org/doi/pdf/10.36227/techrxiv.171259566.60211714) about multi-modal knowledge graph completion is accepted by [SIGIR 2024](https://sigir-2024.github.io/index.html).
- *2024.02*: 🎉 [One paper](https://arxiv.org/abs/2402.15444) about multi-modal knowledge graph completion is accepted by [LREC-COLING 2024](https://lrec-coling-2024.org/).
- *2024.02*: 😄 We pre-print our survey paper [Knowledge Graphs Meet Multi-Modal Learning: A Comprehensive Survey](http://arxiv.org/abs/2402.05391).
- *2023.12*: 😄 I join Ant Group for a research intern, focusing on knowledge pre-training for recommender systems.

# 🌟 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/subaru.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Have We Designed Generalizable Structural Knowledge Promptings? Systematic Evaluation and Rethinking**](https://arxiv.org/abs/2501.00244)

Yichi Zhang, Zhuo Chen, Lingbing Guo, Yajing Xu, Shaokai Chen, Mengshu Sun, Binbin Hu, Zhiqiang Zhang, Lei Liang, Wen Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/SUBARU) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: A comprehensive evaluation of **structural knowledge promptings** <span style="color:#c68864;">LLM</span>.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/SUBARU)](https://github.com/zjukg/SUBARU) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/momok.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Mixture of Modality Knowledge Experts for Robust Multi-modal Knowledge Graph Completion**](https://arxiv.org/abs/2405.16869)

Yichi Zhang, Zhuo Chen, Lingbing Guo, Yajing Xu, Binbin Hu, Ziqi Liu, Wen Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/MoMoK) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Mixture-of-experts networks in <span style="color:#D70761;">MMKG</span>.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/MoMoK)](https://github.com/zjukg/MoMoK) 🌟
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/mudok.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Multi-domain Knowledge Graph Collaborative Pre-training and Prompt Tuning for Diverse Downstream Tasks**](https://arxiv.org/abs/2405.13085)

**Yichi Zhang**, Binbin Hu, Zhuo Chen, Lingbing Guo, Ziqi Liu, Zhiqiang Zhang, Lei Liang, Huajun Chen, Wen Zhang

[**Project Page**](https://github.com/zjukg/MuDoK) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Unified pre-training and prompt tuning for item knowledge graphs to serve diverse downstream tasks like recommendation and text understanding.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/MuDoK)](https://github.com/zjukg/MuDoK) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/mygo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**(MyGO)Tokenization, Fusion, and Augmentation: Towards Fine-grained Multi-modal Entity Representation**](https://arxiv.org/abs/2404.09468)

**Yichi Zhang**, Zhuo Chen, Lingbing Guo, Yajing Xu, Binbin Hu, Ziqi Liu, Wen Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/MyGO) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Fine-grained modality information tokenization, fusion, and augmentation in multi-modal knowledge graphs.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/MyGO)](https://github.com/zjukg/MyGO) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/knowpat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Knowledgeable Preference Alignment for LLMs in Domain-specific Question Answering**](https://arxiv.org/pdf/2311.06503.pdf)

**Yichi Zhang**, Zhuo Chen, Yin Fang, Lei Cheng, Yanxi Lu, Fangming Li, Wen Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/KnowPAT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Aligning <span style="color:#c68864">LLMs</span> with knowledgeable human preference with external KGs for domain-specific application.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/KnowPAT)](https://github.com/zjukg/KnowPAT) 🌟
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/native.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**NativE: Multi-modal Knowledge Graph Completion in the Wild**](https://arxiv.org/abs/2406.17605)

**Yichi Zhang**, Zhuo Chen, Lingbing Guo, Yajing Xu, Binbin Hu, Ziqi Liu, Wen Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/NATIVE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: <span style="color:#D70761;">MMKG</span> completion with diverse and imbalanced modality information.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/NATIVE)](https://github.com/zjukg/NATIVE) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/kopa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Making Large Language Models Perform Better in Knowledge Graph Completion**](https://arxiv.org/pdf/2310.06671.pdf)

**Yichi Zhang**, Zhuo Chen, Lingbing Guo, Yajing Xu, Wen Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/KoPA) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Incorporating structural information from KGs into <span style="color:#c68864">LLMs</span> to conduct structure-aware knowledge reasoning.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/KoPA)](https://github.com/zjukg/KoPA) 🌟
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Knowledge Graphs Meet Multi-Modal Learning: A Comprehensive Survey**](https://arxiv.org/pdf/2402.05391.pdf)

Zhuo Chen, **Yichi Zhang**, Yin Fang, Yuxia Geng, Lingbing Guo, Xiang Chen, Qian Li, Wen Zhang
, Jiaoyan Chen, Yushan Zhu, Jiaqi Li, Xiaoze Liu, Jeff Z. Pan, Ningyu Zhang, Huajun Chen

[**Project Page**](https://github.com/zjukg/KG-MM-Survey) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Comprehensive survey about <span style="color:#D70761;">MMKG</span> and KG-enhanced multi-modal learning.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/KG-MM-Survey)](https://github.com/zjukg/KG-MM-Survey) 🌟
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2024</div><img src='images/adamf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unleashing the Power of Imbalanced Modality Information for Multi-modal Knowledge Graph Completion**](https://arxiv.org/pdf/2402.15444.pdf)

**Yichi Zhang**, Zhuo Chen, Lei Liang, Huajun Chen, Wen Zhang

[**Project Page**](https://github.com/zjukg/AdaMF-MAT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- TL;DR: Augmenting the imbalanced modality information of <span style="color:#D70761;">MMKG</span>s with adversarial training.
- Github Stars: [![](https://img.shields.io/github/stars/zjukg/AdaMF-MAT)](https://github.com/zjukg/AdaMF-MAT) 🌟
</div>
</div>



# 📝 Publications
- `AAAI 2025` Tokenization, Fusion, and Augmentation: Towards Fine-grained Multi-modal Entity Representation. **Yichi Zhang**, Zhuo Chen, Lingbing Guo, Yajing Xu, Binbin Hu, Ziqi Liu, Wen Zhang, Huajun Chen (CCF-A)
- `AAAI 2025` K-ON: Stacking Knowledge On the Head Layer of Large Language Model. Lingbing Guo, **Yichi Zhang**, Zhongpu Bo, Zhuo Chen, Mengshu Sun, Zhiqiang Zhang, Wen Zhang, Huajun Chen (CCF-A)
- `ACM MM 2024` Making Large Language Models Perform Better in Knowledge Graph Completion. **Yichi Zhang**, Zhuo Chen, Lingbing Guo, Yajing Xu, Wen Zhang, Huajun Chen (CCF-A, Oral)
- `ACL 2024 (Findings)` Knowledgeable Preference Alignment for LLMs in Domain-specific Question Answering. **Yichi Zhang**, Zhuo Chen, Yin Fang, Lei Cheng, Yanxi Lu, Fangming Li, Wen Zhang, Huajun Chen (CCF-A)
- `SIGIR 2024` NativE: Multi-modal Knowledge Graph Completion in the Wild. **Yichi Zhang**, Zhuo Chen, Lingbing Guo, Yajing Xu, Binbin Hu, Ziqi Liu, Wen Zhang, Huajun Chen. (CCF-A)
- `KBS 2024` Distributed representations of entities in open-world knowledge graphs. Lingbing Guo, Zhuo Chen, Jiaoyan Chen, **Yichi Zhang**, Zequn Sun, Zhongpu Bo, Yin Fang, Xiaoze Liu, Huajun Chen, Wen Zhang. (CCF-C, JCR Section 1)
- `COLING 2024` Unleashing the Power of Imbalanced Modality Information for Multi-modal Knowledge Graph Completion. **Yichi Zhang**, Zhuo Chen, Lei Liang, Huajun Chen, Wen Zhang. (CCF-B)
- `ISWC 2023` Rethinking Uncertainly Missing and Ambiguous Visual Modality in Multi-Modal Entity Alignment. Zhuo Chen, Lingbing Guo, Yin Fang, **Yichi Zhang**, Jiaoyan Chen, Jeff Z Pan, Yangning Li, Huajun Chen, Wen Zhang (CCF-B, Oral, Best Paper Candidate)
- `ACM MM 2023` MEAformer: Multi-modal Entity Alignment Transformer for Meta Modality Hybrid. Zhuo Chen, Jiaoyan Chen, Wen Zhang, Lingbing Guo, Yin Fang, Yufeng Huang, **Yichi Zhang**, Yuxia Geng, Jeff Z Pan, Wenting Song, Huajun Chen (CCF-A, Poster)
- `NLPCC 2023` MACO: A Modality Adversarial and Contrastive Framework for Modality-missing Multi-modal Knowledge Graph Completion. **Yichi Zhang**, Zhuo Chen, Wen Zhang (CCF-C, Oral)
- `CCKS 2023` CausE: Towards Causal Knowledge Graph Embedding. **Yichi Zhang**, Wen Zhang (EI, Poster)
- `ICDE 2023` Tele-Knowledge Pre-training for Fault Analysis. Zhuo Chen, Wen Zhang, Yufeng Huang, Mingyang Chen, Yuxia Geng, Hongtao Yu, Zhen Bi, **Yichi Zhang**, Zhen Yao, Wenting Song, Xinliang Wu, Yi Yang, Song Jiang, Zhaoyang Lian, Yingying Li, Huajun Chen (CCF-A, Industry Track, Oral)
- `IJCNN 2023` Modality-Aware Negative Sampling for Multi-modal Knowledge Graph Embedding. **Yichi Zhang**, Mingyang Chen, Wen Zhang (CCF-C, Oral)
- `KDD 2022` Knowledge Graph Completion with Pre-trained Multimodal Transformer and Twins Negative Sampling. **Yichi Zhang**, Wen Zhang (CCF-A, UC Track)

# 🐘 Projects
- Knowledge Graph Enhanced Telecom Fault Analysis. Core participants. Cooperation with Huawei Technology. (2021-2024)
- [NeuralKG](https://github.com/zjukg/NeuralKG). An open-source python library for diverse knowledge graphs representation learning. (2021-2022)

# 👨‍🔬 Patents
- 一种基于图神经网络与对抗学习的多模态知识图谱补全方法
- 一种多领域知识图谱预训练和微调方法
- 一种基于混合模态知识专家的多模态知识图谱补全方法


# 🎖 Honors and Awards
- *2024.11* National Scholarship (国家奖学金)
- *2024.04* Chiang Chen Scholarship (蒋震奖学金)
- *2023.04* Chiang Chen Scholarship (蒋震奖学金)
- *2022.06* Outstanding Bachelor's Degree Graduates (优秀毕业生)
- *2022.04* Distinguished Engineer Scholarship (卓越工程师奖学金)
- *2021.10* Second-class Scholarships in Zhejiang University (校二等奖学金)
- *2020.12* College Scholarship from Higgs Technology (希格斯奖学金)
- *2020.10* Zhejiang Provincial Government Scholarship (浙江省政府奖学金)
- *2020.10* Second-class Scholarship in Zhejiang University (校二等奖学金)
- *2019.10* Second-class Scholarship in Zhejiang University (校二等奖学金)

# 📖 Educations
- *2022.09 - present*, Master Student, Zhejiang University, major in computer science.
- *2018.09 - 2022.06*, Undergraduate, Zhejiang University, major in software engineering, GPA: 3.92/4.0, Rank 6/78.
- *2015.09 - 2018.06* Xinchang Middle School. (浙江省新昌中学)


# 💻 Internships
- *2023.12 - present*, Research Intern at [Ant Group](https://www.antgroup.com/), Hangzhou. Advisor: [Binbin Hu](https://scholar.google.com/citations?user=a70Jt9oAAAAJ&hl=zh-CN&oi=ao) and [Ziqi Liu](https://scholar.google.com/citations?hl=zh-CN&user=4NYzqlcAAAAJ&view_op=list_works&sortby=pubdate)

# ✍️ Academic Service
- Conference Reviewer: Neurips 2024, WWW 2024, ARR 2023/2024, ACM MM 2024, IJCNN 2024.
- Conference Volunteer: ISWC 2023, IJCKG 2022.

<a href="https://info.flagcounter.com/YCFC"><img src="https://s11.flagcounter.com/mini/YCFC/bg_FFFFFF/txt_000000/border_CCCCCC/flags_0/" alt="Flag Counter" border="0"></a>

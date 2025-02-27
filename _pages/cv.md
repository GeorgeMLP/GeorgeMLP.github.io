---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My name is George Ma (Jiangyan Ma). I am an EECS PhD student at UC Berkeley, advised by Prof. [Somayeh Sojoudi](https://people.eecs.berkeley.edu/~sojoudi/). Previously, I was an undergraduate student at Peking University, where I did research on graph learning at Prof. [Yisen Wang](https://yisenwang.github.io/)'s lab. My email: [georgem@stu.pku.edu.cn](mailto:georgem@stu.pku.edu.cn). My homepage: [George Ma's Homepage](https://georgemlp.github.io). I actively write blogs on Zhihu: [George M's Zhihu Homepage](https://www.zhihu.com/people/george-m-55/posts).

Education
======
- *Undergraduate; Information and Computing Science*

  I studied at School of Electronic Engineering and Computer Science, Peking University. I majored in Applied Physics in the first two years of college and switched to Information and Computing Science thereafter.

- *PhD student; Electrical Engineering and Computer Sciences*

  Currently, I am an EECS PhD student at UC Berkeley.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Experience
======

- July 2022 -- October 2022; **Universal Graph Neural Networks without Message-Passing**

  In this research experience, I focused on studying the expressive power of MLP-based graph neural networks for graph-level tasks. I developed a novel MLP-based GNN called UBoN (Universal Bag of Nodes), specifically designed to achieve universal expressive power on graphs. I submitted my paper titled *Universal Graph Neural Networks without Message Passing* to ICLR 2023, although it was unfortunately rejected.

- October 2022 -- August 2023; **Laplacian Canonization for GNN Spectral Embedding**

  During my research, I explored the concept of Laplacian eigenvectors as universal graph positional encodings. Although being universal, there are challenges associated with their universality, such as sign and basis ambiguity. To tackle these issues, I proposed an innovative pre-processing technique called Laplacian Canonization. I submitted my paper titled *Laplacian Canonization: A Minimalist Approach to Sign and Basis Invariant Spectral Embedding* to NeurIPS 2023, and it was accepted as a poster.

- June 2023 -- September 2023; **Baking Symmetry into GFlowNets**

  I actively contributed to groundbreaking research as a member of Prof. Yoshua Bengio's lab at Mila - Quebec AI Institute in Montréal. Leveraging my expertise in invariant networks, I was dedicated to incorporating symmetries into the graph construction process of GFlowNets. Preliminary experiments demonstrated promising performance enhancements. I submitted my paper titled *Baking Symmetry into GFlowNets* to the NeurIPS 2023 AI4Science Workshop, and it was accepted as an **oral** presentation.

- June 2023 -- May 2024; **A Canonicalization Perspective on Invariant and Equivariant Learning**

  I collaborated with researchers from MIT to investigate the correlation between the canonicalizability of Laplacian eigenvectors and the expressive power of invariant networks (such as SignNet and BasisNet) that employ Laplacian eigenvectors as positional encodings. We established the theoretical framework of canonicalization, and applied it to solve the open problem of the expressive power of invariant networks with equivariance constraints. We also designed novel canonicalization algorithms for eigenvectors that are superior to prior work and even optimal. Our paper was accepted in NeurIPS 2024 as a poster.

- November 2024 -- Present; **Improving Automatic Interpretation of SAE Features**

  I am currently researching the interpretability of large language models (LLMs), focusing on using sparse auto-encoders (SAEs) to extract meaningful features that help us understand and influence model behavior. However, existing methods for automatically interpreting SAE features with LLMs are often inaccurate and heavily biased toward recall. In this work, we enhance SAE feature interpretation by incorporating structured explanations and a tree-based explainer. Additionally, we introduce "hard negative" sampling to mitigate recall bias in generated explanations. Finally, we conduct an empirical analysis to explore the complexity and polysemanticity of different LLM layers using SAEs.

Professional Activities
======
- [Top reviewer](https://neurips.cc/Conferences/2024/ProgramCommittee), NeurIPS 2024
- [Reviewer](https://iclr.cc/Conferences/2025/Reviewers), ICLR 2025
- [Reviewer](https://virtual.aistats.org/Conferences/2025/Reviewers), AISTATS 2025
- Reviewer, ICML 2025
- Reviewer, TMLR
- Reviewer, NeurIPS 2025

Awards
======

- Provincial First Prize of National Mathematics Olympiad in Senior
- Second Prize of the Chinese Mathematics Competitions
- Top 10 Excellent Graduation Thesis of School of EECS, Peking University
- Excellent Graduation Thesis, Peking University

Scholarships
======

- National Encouragement Scholarship, 2020--2024
- Cyrus Tang Scholarship, 2020--2024

Interests and Activities
======

- Learned Chinese Chess for 7 years, took part in various competitions
- Took soccer lessons for half a year
- Played badminton for 6 years
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

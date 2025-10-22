---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My name is George Ma (Jiangyan Ma). I am an EECS PhD student at UC Berkeley, advised by Prof. [Somayeh Sojoudi](https://people.eecs.berkeley.edu/~sojoudi/). Previously, I was an undergraduate student at Peking University, where I did research on graph learning at Prof. [Yisen Wang](https://yisenwang.github.io/)'s lab. My email: [george_ma@berkeley.edu](mailto:george_ma@berkeley.edu). My homepage: [George Ma's Homepage](https://georgemlp.github.io). I actively write blogs on Zhihu: [George M's Zhihu Homepage](https://www.zhihu.com/people/george-m-55/posts).

Education
======
- *Undergraduate; Information and Computing Science*

  I studied at School of Electronic Engineering and Computer Science, Peking University. I majored in Applied Physics in the first two years of college and switched to Information and Computing Science thereafter.

- *PhD student; Electrical Engineering and Computer Sciences*

  Currently, I am an EECS PhD student at UC Berkeley.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Preprints
======
  <ul>{% for post in site.preprints reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Experience
======

- May 2025 -- Sep 2025; **SpecAgent for Code Completion**

  Proposed *SpecAgent*, an indexing-time retrieval agent that anticipates future edits in code repositories to reduce inference-time latency. Designed a leakage-free benchmark to avoid future context leakage and provide more realistic evaluation. Experiments demonstrated 9–11% absolute improvements in code completion performance.

- Nov 2024 -- May 2025; **Revising SAE Feature Explanations**

  Investigated mechanistic interpretability of LLMs using sparse autoencoders (SAEs), which disentangle hidden representations into interpretable features. Proposed structured explanations, a tree-based explainer, and hard-negative sampling to address biases in current methods. The resulting paper was published at NeurIPS 2025.

- Dec 2024 -- Feb 2025; **Normalization Layers and Side-Channel Communication**

  Studied the role of normalization layers in CNNs and discovered that they enable long-range spatial communication beyond local receptive fields. Analyzed this effect in a toy localization task, showing normalization layers act as iterative message-passing mechanisms. The work highlights risks in applications requiring spatial locality.

- Jun 2023 -- May 2024; **Canonicalization for Invariant & Equivariant Learning**

  Collaborated with MIT researchers to introduce a canonicalization framework that unifies invariant and equivariant learning. This framework resolved an open problem on the expressiveness of invariant networks with equivariance constraints. We also designed new canonicalization algorithms for eigenvectors, leading to a publication at NeurIPS 2024.

- Jun 2023 -- Sep 2023; **Baking Symmetry into GFlowNets**

  Interned at Prof. Yoshua Bengio's lab (Mila) and applied my background in invariant networks to address symmetric actions in GFlowNets. Developed methods to incorporate symmetries into the generation process, improving both diversity and reward. The paper was presented as an **oral** at NeurIPS 2023 AI4Science.

- Oct 2022 -- Aug 2023; **Laplacian Canonization for GNNs**

  Explored Laplacian eigenvectors as universal graph positional encodings, which suffer from sign and basis ambiguity. Proposed *Laplacian Canonization*, a preprocessing algorithm that resolves these ambiguities. The work was published as a poster at NeurIPS 2023.

Professional Activities
======
- [Top reviewer](https://neurips.cc/Conferences/2024/ProgramCommittee), NeurIPS 2024
- [Reviewer](https://iclr.cc/Conferences/2025/Reviewers), ICLR 2025
- [Reviewer](https://virtual.aistats.org/Conferences/2025/Reviewers), AISTATS 2025
- [Reviewer](https://icml.cc/Conferences/2025/ProgramCommittee#top-reviewer), ICML 2025
- [Reviewer](https://neurips.cc/Conferences/2025/ProgramCommittee), NeurIPS 2025
- Reviewer, TMLR

Awards
======

- Top 10 Excellent Graduation Thesis of School of EECS, Peking University
- Excellent Graduation Thesis, Peking University

Scholarships
======

- National Encouragement Scholarship, 2020--2024
- Cyrus Tang Scholarship, 2020--2024
  
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

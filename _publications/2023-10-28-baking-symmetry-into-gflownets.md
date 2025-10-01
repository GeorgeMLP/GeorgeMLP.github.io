---
title: "Baking Symmetry into GFlowNets"
collection: publications
permalink: /publication/2023-10-28-baking-symmetry-into-gflownets
excerpt: 'We proposed to incorporate state and action symmetries into GFlowNets.'
date: 2023-10-28
venue: 'NeurIPS-AI4Science'
paperurl: 'https://openreview.net/forum?id=CZGHAeeBk3'
citation: 'Jiangyan Ma, Emmanuel Bengio, Yoshua Bengio, Dinghuai Zhang (2023). Baking Symmetry into GFlowNets. In <i>NeurIPS 2023 AI for Science: from Theory to Practice</i>.'
---
GFlowNets have exhibited promising performance in generating diverse candidates with high rewards. However, the current training pipelines of GFlowNets do not consider the presence of isomorphic actions, which are actions resulting in symmetric or isomorphic states. This lack of symmetry increases the amount of samples required for training GFlowNets and can result in inefficient and potentially incorrect flow functions. As a consequence, the reward and diversity of the generated objects decrease. In this study, our objective is to integrate symmetries into GFlowNets by identifying equivalent actions during the generation process. Experimental results using synthetic data demonstrate the promising performance of our proposed approaches. Our work was accepted as an **oral** presentation at NeurIPS 2023 AI4Science Workshop.
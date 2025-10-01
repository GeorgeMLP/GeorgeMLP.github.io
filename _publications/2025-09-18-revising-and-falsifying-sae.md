---
title: "Revising and Falsifying Sparse Autoencoder Feature Explanations"
collection: publications
permalink: /publication/2025-09-18-revising-and-falsifying-sae
excerpt: 'We developed new methods to refine and falsify sparse autoencoder feature explanations, yielding higher-quality interpretability of large language models.'
date: 2025-09-18
venue: 'NeurIPS'
paperurl: 'https://openreview.net/forum?id=OJAW2mHVND'
citation: 'George Ma, Samuel Pfrommer, Somayeh Sojoudi (2025). Revising and Falsifying Sparse Autoencoder Feature Explanations. In <i>Thirty-ninth Conference on Neural Information Processing Systems</i>.'
---
Mechanistic interpretability research seeks to reverse-engineer large language models (LLMs) by uncovering the internal representations of concepts within their activations. Sparse Autoencoders (SAEs) have emerged as a valuable tool for disentangling polysemantic neurons into more monosemantic, interpretable features. However, recent work on automatic explanation generation for these features has faced challenges: explanations tend to be overly broad and fail to take polysemanticity into consideration. This work addresses these limitations by introducing a similarity-based strategy for sourcing close negative sentences that more effectively falsify generated explanations. Additionally, we propose a structured, component-based format for feature explanations and a tree-based, iterative explanation method that refines explanations. We demonstrate that our structured format and tree-based explainer improve explanation quality, while our similarity-based evaluation strategy exposes biases in existing interpretability methods. We also analyze the evolution of feature complexity and polysemanticity across LLM layers, offering new insights into information content within LLMs' residual streams.
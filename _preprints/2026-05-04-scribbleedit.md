---
title: "ScribbleEdit: Synthetic Data for Image Editing with Scribbles and Text"
collection: preprints
permalink: /preprint/2026-05-04-scribbleedit
excerpt: 'ScribbleEdit introduces a large-scale synthetic dataset and training pipeline that combines freehand scribbles with natural language instructions to improve spatially precise, semantically consistent image editing.'
date: 2026-05-04
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2605.01135'
citation: 'Anya Ji, George Ma, Téa Wright, Yiming Zhang, David M. Chan, Alane Suhr, Somayeh Sojoudi (2026). ScribbleEdit: Synthetic Data for Image Editing with Scribbles and Text. <i>arXiv preprint arXiv:2605.01135</i>.'
---
Recent progress in generative models has significantly advanced image editing capabilities, yet precise and intuitive user control remains difficult. Specifically, users often struggle to communicate both exact spatial layouts and specific semantic details simultaneously. While natural language instructions effectively convey high-level semantics like texture and color, they lack spatial specificity. Conversely, freehand scribbles provide rough spatial boundaries but cannot express detailed visual attributes. Consequently, achieving precise control requires combining both modalities. However, existing models struggle to jointly interpret abstract scribbles alongside text due to a lack of specialized training data.

In this work, we introduce ScribbleEdit, a large-scale synthetic dataset designed to bridge this gap by combining natural language instructions with freehand scribble inputs for more accurate, controllable edits. We construct this dataset through a synthetic pipeline that automatically generates source-target image pairs via inpainting, which are then paired with human-drawn scribbles and VLM-generated text instructions. Using ScribbleEdit, we evaluate and finetune both diffusion-based and autoregressive unified multimodal image editing models. Our experiments reveal that while off-the-shelf models struggle with abstract scribble inputs, finetuning on our synthetic dataset significantly improves their ability to generate spatially aligned and semantically consistent edits.
---
title: "Mask Models are Token Level Contrastive Learners"
collection: publications
permalink: /publication/mask-models-are-token-level-contrastive-learners
excerpt: 'Proposed a theoretical framework to analysis mask models as token level contrastive learning models.'
date: 2023-01-26
venue: 'Submitted to ICML'
paperurl: 'https://zxp46.github.io/files/paper_mask_model_explained.pdf'
# citation: ''
---

In recent years, the field of self-supervised learning has seen a surge in the development of mask models, which have been demonstrated to have strong performance on downstream tasks and efficient training. To better understand the underlying mechanism behind these models' success, we propose a theoretical framework for mask modeling. By treating mask modeling as a low-rank recovery task, we demonstrate that it is a parametric version of Spectral Clustering and the reconstruction loss conforms to the form of Spectral Contrastive loss. This means that mask modeling can be understood as a token level Contrastive Learning. Our framework can be used to explain why optimal masking ratios vary among modalities and why there is a large gap between linear probing and finetuning performance for mask models. Additionally, our analysis suggests that the success of mask models depends on the model architecture, where a token mixing layer and layer normalization are crucial for the success of mask models. Our framework has the potential to be a step stone for future algorithm and network architecture design in the field of self-supervised learning.



[[Paper](https://zxp46.github.io/files/paper_mask_model_explained.pdf)]

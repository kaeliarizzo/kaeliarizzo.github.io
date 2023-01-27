---
title:  "Selecting deep neural networks that yield consistent attribution-based interpretations for genomics"
excerpt: "MLCB, 2022"
layout: single
header:
  teaser: /assets/images/atac.png
  url: https://proceedings.mlr.press/v200/majdandzic22a/majdandzic22a.pdf
---

![Image of network selection paper.](/assets/images/select.png)

## Abstract:

Deep neural networks (DNNs) have advanced our ability to take DNA primary sequence as input and predict a myriad of molecular activities measured via high-throughput functional genomic assays. Post hoc attribution analysis has been employed to provide insights into the importance of features learned by DNNs, often revealing patterns such as sequence motifs. However, attribution maps typically harbor spurious importance scores to an extent that varies from model to model, even for DNNs whose predictions generalize well. Thus, the standard approach for model selection, which relies on performance of a held-out validation set, does not guarantee that a high-performing DNN will provide reliable explanations. Here we introduce two approaches that quantify the consistency of important features across a population of attribution maps; consistency reflects a qualitative property of human interpretable attribution maps. We employ the consistency metrics as part of a multivariate model selection framework to identify models that yield high generalization performance and interpretable attribution analysis. We demonstrate the efficacy of this approach across various DNNs quantitatively with synthetic data and qualitatively with chromatin accessibility data.

[Full Text](https://proceedings.mlr.press/v200/majdandzic22a/majdandzic22a.pdf)

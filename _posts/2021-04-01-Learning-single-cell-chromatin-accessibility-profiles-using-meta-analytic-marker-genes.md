---
title:  "Learning single-cell chromatin accessibility profiles using meta-analytic marker genes"
excerpt: "bioRxiv, 2021"
layout: single
header:
  teaser: /assets/images/atac.png
---

![Image of scATAC paper.](/assets/images/atac.png)

## Abstract:

Single-cell Assay for Transposase Accessible Chromatin using sequencing (scATAC-seq) is a valuable resource to learn cis-regulatory elements such as cell-type specific enhancers and transcription factor binding sites. However, cell-type identification of scATAC-seq data is known to be challenging due to the heterogeneity derived from different protocols and the high dropout rate.

In this study, we perform a systematic comparison of 7 scATAC-seq datasets of mouse brain to benchmark the efficacy of neuronal cell-type annotation from gene sets. We find that redundant marker genes give a dramatic improvement for a sparse scATAC-seq annotation across the data collected from different studies. Interestingly, simple aggregation of such marker genes achieves performance comparable or higher than that of machine-learning classifiers, suggesting its potential for downstream applications. Based on our results, we reannotated all scATAC-seq data for detailed cell types using robust marker genes. Their meta scATAC-seq profiles are publicly available at https://gillisweb.cshl.edu/Meta_scATAC. Furthermore, we trained a deep neural network to predict chromatin accessibility from only DNA sequence and identified key motifs enriched for each neuronal subtype. Those predicted profiles are visualized together in our database as a valuable resource to explore cell-type specific epigenetic regulation in a sequence-dependent and -independent manner.

[Whole paper Link here](https://www.biorxiv.org/content/10.1101/2021.04.01.438068v2)
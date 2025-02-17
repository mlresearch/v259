---
title: Continuity Contrastive Representations of ECG for Heart Block Detection from
  Only Lead-I
abstract: 'Early detection of heart block can prevent life-threatening outcomes in
  patients with cardiac conduction disorders. While 12-lead ECG interpretation is
  the clinical standard apparatus, this work investigates detecting heart block from
  the lead-I ECG signals, the lead available on commercial smartwatches. We evaluate
  two state-of-the-art architectures: residual neural network and transformer encoder,
  both trained in a self-supervised contrastive learning manner with a novel signal-continuity-based
  ECG view definition on a dataset of 3.6 million ECGs from Massachusetts General
  Hospital. These models learn efficient ECG representations, which are used for heart
  block detection via linear probing on the PTB-XL dataset, a public ECG resource.
  To provide performance benchmarks, we compare our self-supervised models to supervised
  adaptations of both models trained on 10.6 thousand single-lead PTB-XL ECGs. Our
  analysis evaluates the performance of each model using the area under the receiver-operating
  curve (AUC), sensitivity, and specificity. We observe improved performance from
  the self-supervised pretraining. Additionally, we demonstrate the robust generalizability
  of these models in scarce-data scenarios, maintaining consistent performance with
  a reduced number of labeled training examples. This study highlights the potential
  of self-supervised learning in lead-I ECG diagnostics, offering promising implications
  for clinical applications where labeled data is scarce.'
software: https://github.com/teyaberg/continuity-contrastive-ecg
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bergamaschi25a
month: 0
tex_title: Continuity Contrastive Representations of ECG for Heart Block Detection
  from Only Lead-I
firstpage: 130
lastpage: 142
page: 130-142
order: 130
cycles: false
bibtex_author: Bergamaschi, Teya and Stultz, Collin and Alam, Ridwan
author:
- given: Teya
  family: Bergamaschi
- given: Collin
  family: Stultz
- given: Ridwan
  family: Alam
date: 2025-02-17
address:
container-title: Proceedings of the 4th Machine Learning for Health Symposium
volume: '259'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 2
  - 17
pdf: https://raw.githubusercontent.com/mlresearch/v259/main/assets/bergamaschi25a/bergamaschi25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

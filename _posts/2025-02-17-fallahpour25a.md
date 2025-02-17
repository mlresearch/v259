---
title: 'EHRMamba: Towards Generalizable and Scalable Foundation Models for Electronic
  Health Records'
abstract: Transformers have significantly advanced the modeling of Electronic Health
  Records (EHR), yet their deployment in real-world healthcare is limited by several
  key challenges. Firstly, the quadratic computational cost and insufficient context
  length of these models hinder hospitals’ ability in processing the extensive medical
  histories typical in EHR data. Additionally, existing models employ separate finetuning
  for each clinical task, complicating maintenance in healthcare environments. Moreover,
  these models focus exclusively on either clinical prediction or EHR forecasting,
  lacking proficiency in both tasks. To overcome these limitations, we introduce EhrMamba,
  a robust foundation model built on the Mamba architecture. EhrMamba can process
  sequences up to 300% times longer than previous models due to its linear computational
  cost. We also introduce a novel approach to Multitask Prompted Finetuning (MPF)
  for EHR data, which enables EhrMamba to simultaneously learn multiple clinical tasks
  in a single finetuning phase, significantly enhancing deployment and cross-task
  generalization. Furthermore, our model leverages the HL7 FHIR data standard to simplify
  integration into existing hospital systems. Alongside EhrMamba, we open-source Odyssey,
  a toolkit designed to support the development and deployment of EHR foundation models,
  with an emphasis on data standardization and interpretability. Our evaluations on
  the MIMIC-IV dataset demonstrate that EhrMamba advances state-of-the-art performance
  across 6 major clinical tasks and excels in EHR forecasting, marking a significant
  leap forward in the field.
software: https://github.com/VectorInstitute/odyssey
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fallahpour25a
month: 0
tex_title: 'EHRMamba: Towards Generalizable and Scalable Foundation Models for Electronic
  Health Records'
firstpage: 291
lastpage: 307
page: 291-307
order: 291
cycles: false
bibtex_author: Fallahpour, Adibvafa and Alinoori, Mahshid and Ye, Wenqian and Cao,
  Xu and Afkanpour, Arash and Krishnan, Amrit
author:
- given: Adibvafa
  family: Fallahpour
- given: Mahshid
  family: Alinoori
- given: Wenqian
  family: Ye
- given: Xu
  family: Cao
- given: Arash
  family: Afkanpour
- given: Amrit
  family: Krishnan
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
pdf: https://raw.githubusercontent.com/mlresearch/v259/main/assets/fallahpour25a/fallahpour25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

---
title: 'MED-OMIT: Extrinsically-Focused Evaluation Metric for Omissions in Medical
  Summarization'
abstract: Large language models (LLMs) have shown promise in safety-critical applications
  such as healthcare, yet the ability to quantify performance has lagged. An example
  of this challenge is in evaluating a summary of the patient’s medical record. A
  resulting summary can enable the provider to get a high-level overview of the patient’s
  health status quickly. Yet, a summary that omits important facts about the patient’s
  record can produce a misleading picture. This can lead to negative consequences
  on medical decision-making. We propose MED-OMIT as a metric to explore this challenge.
  We focus on using provider-patient history conversations to generate a subjective
  (a summary of the patient’s history) as a case study. We begin by discretizing facts
  from the dialogue and identifying which are omitted from the subjective. To determine
  which facts are clinically relevant, we measure the importance of each fact to a
  simulated differential diagnosis. We compare MED-OMIT’s performance to that of clinical
  experts and find broad agreement We use MED-OMIT to evaluate LLM performance on
  subjective generation and find some LLMs (gpt-4 and llama-3.1-405b) work well with
  little effort, while others (e.g. Llama 2) perform worse.
software: https://github.com/curai/curai-research/tree/main/MEDOMIT
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schumacher25a
month: 0
tex_title: 'MED-OMIT: Extrinsically-Focused Evaluation Metric for Omissions in Medical
  Summarization'
firstpage: 897
lastpage: 922
page: 897-922
order: 897
cycles: false
bibtex_author: Schumacher, Elliot and Rosenthal, Daniel and Naik, Dhruv and Nair,
  Varun and Price, Luladay and Tso, Geoffrey and Kannan, Anitha
author:
- given: Elliot
  family: Schumacher
- given: Daniel
  family: Rosenthal
- given: Dhruv
  family: Naik
- given: Varun
  family: Nair
- given: Luladay
  family: Price
- given: Geoffrey
  family: Tso
- given: Anitha
  family: Kannan
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
pdf: https://raw.githubusercontent.com/mlresearch/v259/main/assets/schumacher25a/schumacher25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

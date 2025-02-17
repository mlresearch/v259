---
title: 'Automating Feedback Analysis in Surgical Training: Detection, Categorization,
  and Assessment'
abstract: This work introduces the first framework for reconstructing surgical dialogue
  from unstructured real-world recordings, which is crucial for characterizing teaching
  tasks. In surgical training, the formative verbal feedback that trainers provide
  to trainees during live surgeries is crucial for ensuring safety, correcting behavior
  immediately, and facilitating long-term skill acquisition. However, analyzing and
  quantifying this feedback is challenging due to its unstructured and specialized
  nature. Automated systems are essential to manage these complexities at scale, allowing
  for the creation of structured datasets that enhance feedback analysis and improve
  surgical education. Our framework integrates voice activity detection, speaker diarization,
  and automated speech recognition, with a novel enhancement that 1) removes hallucinations
  (non-existent utterances generated during speech recognition fueled by noise in
  the operating room) and 2) separates speech from trainers and trainees using few-shot
  voice samples. These aspects are vital for reconstructing accurate surgical dialogues
  and understanding the roles of operating room participants. Using data from 33 real-world
  surgeries, we demonstrated the system’s capability to reconstruct surgical teaching
  dialogues and detect feedback instances effectively (F1 score of 0.79±0.07). Moreover,
  our hallucination removal step improves feedback detection performance by ≈14%.
  Evaluation on downstream clinically relevant tasks of predicting Behavioral Adjustment
  of trainees and classifying Technical feedback, showed performances comparable to
  manual annotations with F1 scores of 0.82±0.03 and 0.81±0.03 respectively. These
  results highlight the effectiveness of our framework in supporting clinically relevant
  tasks and improving over manual methods.
software: https://github.com/firdavsn/SurgicalFeedbackAI
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nasriddinov25a
month: 0
tex_title: 'Automating Feedback Analysis in Surgical Training: Detection, Categorization,
  and Assessment'
firstpage: 787
lastpage: 804
page: 787-804
order: 787
cycles: false
bibtex_author: Nasriddinov, Firdavs and Kocielnik, Rafal and Gupta, Arushi and Yang,
  Cherine and Wong, Elyssa and Anandkumar, Anima and Hung, Andrew
author:
- given: Firdavs
  family: Nasriddinov
- given: Rafal
  family: Kocielnik
- given: Arushi
  family: Gupta
- given: Cherine
  family: Yang
- given: Elyssa
  family: Wong
- given: Anima
  family: Anandkumar
- given: Andrew
  family: Hung
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
pdf: https://raw.githubusercontent.com/mlresearch/v259/main/assets/nasriddinov25a/nasriddinov25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

---
title: Residual Learning and Context Encoding for Adaptive Offline-to-Online Reinforcement
  Learning
abstract: Offline reinforcement learning (RL) allows learning sequential behavior
  from fixed datasets. Since offline datasets do not cover all possible situations,
  many methods collect additional data during online fine-tuning to improve performance.
  In general, these methods assume that the transition dynamics remain the same during
  both the offline and online phases of training. However, in many real-world applications,
  such as outdoor construction and navigation over rough terrain, it is common for
  the transition dynamics to vary between the offline and online phases. Moreover,
  the dynamics may vary during the online training. To address this problem of changing
  dynamics from offline to online RL we propose a residual learning approach that
  infers dynamics changes to correct the outputs of the offline solution. At the online
  fine-tuning phase, we train a context encoder to learn a representation that is
  consistent inside the current online learning environment while being able to predict
  dynamic transitions. Experiments in D4RL MuJoCo environments, modified to support
  dynamics’ changes upon environment resets, show that our approach can adapt to these
  dynamic changes and generalize to unseen perturbations in a sample-efficient way,
  whilst comparison methods cannot.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nakhaeinezhadfard24a
month: 0
tex_title: "{Residual Learning and Context Encoding for Adaptive Offline-to-Online
  Reinforcement Learning}"
firstpage: 1
lastpage: 15
page: 1-15
order: 1
cycles: false
bibtex_author: Nakhaeinezhadfard, Mohammadreza and Scannell, Aidan and Pajarinen,
  Joni
author:
- given: Mohammadreza
  family: Nakhaeinezhadfard
- given: Aidan
  family: Scannell
- given: Joni
  family: Pajarinen
date: 2024-06-11
address:
container-title: Proceedings of the 6th Annual Learning for Dynamics & Control Conference
volume: '242'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 6
  - 11
pdf: https://proceedings.mlr.press/v242/nakhaeinezhadfard24a/nakhaeinezhadfard24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

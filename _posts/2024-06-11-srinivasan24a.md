---
title: 'SpOiLer: Offline reinforcement learning using scaled penalties'
abstract: Offline Reinforcement Learning (RL) is a variant of off-policy learning
  where an optimal policy must be learned from a static dataset containing trajectories
  collected by an unknown behavior policy. In the offline setting, standard off-policy
  algorithms will overestimate values of out-of-distribution actions and a policy
  trained naively in this way will perform poorly in the environment due to distribution
  shift between the implied and real environment; this is especially likely when modelling
  complex and multi-modal data distributions. We propose Scaled-penalty Offline Learning
  (SpOiLer), an offline reinforcement learning algorithm that reduces the value of
  out-of-distribution actions relative to observed actions. The resultant pessimistic
  value function is a lower bound of the true value function and manipulates the policy
  towards selecting actions present in the dataset. Our method is a simple augmentation
  to the standard Bellman backup operator and implementation requires around 15 additional
  lines of code over soft actor-critic. We provide theoretical insights into how SpOiLer
  operates under the hood and show empirically that SpOiLer achieves remarkable performance
  against prior methods on a range of tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srinivasan24a
month: 0
tex_title: "{SpOiLer}: {O}ffline reinforcement learning using scaled penalties"
firstpage: 825
lastpage: 838
page: 825-838
order: 1
cycles: false
bibtex_author: Srinivasan, Padmanaba and Knottenbelt, William J.
author:
- given: Padmanaba
  family: Srinivasan
- given: William J.
  family: Knottenbelt
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
pdf: https://proceedings.mlr.press/v242/srinivasan24a/srinivasan24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

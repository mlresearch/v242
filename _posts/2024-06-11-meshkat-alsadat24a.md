---
title: 'Distributed On-the-Fly Control of Multi-Agent Systems With Unknown Dynamics:
  Using Limited Data to Obtain Near-optimal Control'
booktitle: Proceedings of the 6th Annual Learning for Dynamics \& Control Conference
abstract: We propose a method called ODMU for “on-the-fly control of distributed multi-agent
  systems with unknown nonlinear dynamics” and with (a)synchronous communication between
  the agents where data from a single finite-horizon trajectory is used, possibly
  in conjunction with side information. ODMU can be applied to real-time scenarios
  when the dynamics of the system are unknown or suddenly change such that a priori
  known model cannot be applied. In our proposed algorithm, the agents communicate
  their states using (a)synchronous communication and exploit the side information,
  e.g., regularities of the system, states, agents’ communication scheme, algebraic
  limitations, and coupling in the system states. We provide ODMU for over-approximating
  the reachable sets and to control the agents under conditions with severely limited
  data. ODMU creates differential inclusion sets that calculate the over approximations
  of the reachable sets containing the unknown vector field. We show that ODMU calculates
  the near-optimal control and calculates an upper bound (suboptimality bound) for
  the error between the optimal trajectory and the trajectory calculated by ODMU.
  We use convex-optimization-based control to obtain the guaranteed near-optimal solution.
  We demonstrate the effect of side information on obtaining smaller bounds on suboptimality
  by applying ODMU on a system of unicycles. Additionally, we present a case study
  where a multi-agent system of unicycles with unknown dynamics is controlled via
  ODMU. Moreover, we have developed two baselines, SINDYcMulti and CGP-LCBMulti to
  compare our method with them.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: meshkat-alsadat24a
month: 0
tex_title: "{Distributed On-the-Fly Control of Multi-Agent Systems With Unknown Dynamics:
  Using Limited Data to Obtain Near-optimal Control}"
firstpage: 1
lastpage: 12
page: 1-12
order: 1
cycles: false
bibtex_author: Meshkat Alsadat, Shayan and Baharisangari, Nasim and Xu, Zhe
author:
- given: Shayan
  family: Meshkat Alsadat
- given: Nasim
  family: Baharisangari
- given: Zhe
  family: Xu
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
pdf: https://proceedings.mlr.press/v242/meshkat-alsadat24a/meshkat-alsadat24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

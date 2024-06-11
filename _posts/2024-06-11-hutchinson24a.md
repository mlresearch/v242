---
title: Safe Online Convex Optimization with Multi-Point Feedback
booktitle: Proceedings of the 6th Annual Learning for Dynamics \& Control Conference
abstract: Motivated by the stringent safety requirements that are often present in
  real-world applications, we study a safe online convex optimization setting where
  the player needs to simultaneously achieve sublinear regret and zero constraint
  violation while only using zero-order information. In particular, we consider a
  multi-point feedback setting, where the player chooses $d + 1$ points in each round
  (where $d$ is the problem dimension) and then receives the value of the constraint
  function and cost function at each of these points. To address this problem, we
  propose an algorithm that leverages forward-difference gradient estimation as well
  as optimistic and pessimistic action sets to achieve $O(d \sqrt{T})$ regret and
  zero constraint violation under the assumption that the constraint function is smooth
  and strongly convex. We then perform a numerical study to investigate the impacts
  of the unknown constraint and zero-order feedback on empirical performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hutchinson24a
month: 0
tex_title: "{Safe Online Convex Optimization with Multi-Point Feedback}"
firstpage: 1
lastpage: 13
page: 1-13
order: 1
cycles: false
bibtex_author: Hutchinson, Spencer and Alizadeh, Mahnoosh
author:
- given: Spencer
  family: Hutchinson
- given: Mahnoosh
  family: Alizadeh
date: 2024-06-11
address:
container-title: Proceedings of the 6th Annual Learning for Dynamics \& Control Conference
volume: '242'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 6
  - 11
pdf: https://proceedings.mlr.press/v242/hutchinson24a/hutchinson24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

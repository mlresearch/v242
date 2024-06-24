---
title: 'Learning soft constrained MPC value functions: Efficient MPC design and implementation
  providing stability and safety guarantees'
abstract: 'Model Predictive Control (MPC) can be applied to safety-critical control
  problems, providing closed-loop safety and performance guarantees. Application of
  MPC requires solving an optimization problem at every sampling instant, making it
  challenging to implement on embedded hardware. To address this challenge, we propose
  a framework that combines a tightened soft constrained MPC formulation with a supervised
  learning framework to approximate the MPC value function. This combination enables
  us to obtain a corresponding optimal control law, which can be implemented efficiently
  on embedded platforms. The proposed framework ensures stability and constraint satisfaction
  for various nonlinear systems. While the design effort is similar to the design
  of nominal MPC formulations, we can establish input-to-state stability (ISS) with
  respect to the approximation error of the value function. Moreover, we prove that,
  while the optimal control law may be discontinuous, the value function corresponding
  to the soft constrained MPC problem is Lipschitz continuous for Lipschitz continuous
  systems. This serves two purposes: First, it allows to relate approximation errors
  to a sufficiently large constraint tightening to obtain constraint satisfaction
  guarantees. Secondly, it enables a very efficient supervised learning procedure
  for obtaining the approximation using continuous function approximator classes.
  We showcase the effectiveness of the method through a nonlinear numerical example.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chatzikiriakos24a
month: 0
tex_title: "Learning soft constrained {MPC} value functions: {E}fficient {MPC} design and
  implementation providing stability and safety guarantees"
firstpage: 387
lastpage: 398
page: 387-398
order: 387
cycles: false
bibtex_author: Chatzikiriakos, Nicolas and Wabersich, Kim Peter and Berkel, Felix
  and Pauli, Patricia and Iannelli, Andrea
author:
- given: Nicolas
  family: Chatzikiriakos
- given: Kim Peter
  family: Wabersich
- given: Felix
  family: Berkel
- given: Patricia
  family: Pauli
- given: Andrea
  family: Iannelli
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
pdf: https://proceedings.mlr.press/v242/chatzikiriakos24a/chatzikiriakos24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

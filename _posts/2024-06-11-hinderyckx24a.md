---
title: Linearised Data-Driven LSTM-Based Control of Multi-Input HVAC Systems
booktitle: Proceedings of the 6th Annual Learning for Dynamics \& Control Conference
abstract: The pursuit of sustainability has paved the way for building management
  systems (BMSs) that can steer buildings in an energy-efficient way. In this article,
  a deep learning approach is proposed to control multi-input HVAC systems in order
  to minimize both thermal discomfort and operational cost. More particularly, an
  LSTM-based encoder-decoder process model, trained on historical weather data and
  control sequences generated while the building was steered by a modern rule-based
  controller (RBC), is fed into an optimisation problem, to which a change of variables
  is applied to efficiently model the effect of interdependent control inputs. Both
  the nonlinear LSTM process model and the cost function of the optimisation problem
  are linearised to formulate the control problem as a mixed integer linear programming
  (MILP) problem, which ensures that the controller can operate in near real-time
  and with limited computational power. Moreover, to avoid resorting to model extrapolation
  and to improve the model’s predictive performance, the set of allowed control signal
  values is restricted using a quantile-based approach. In addition to the purely
  data-driven controller (DDC), a hybrid controller is designed to leverage the strengths
  of the RBC and the DDC. The performance of both controllers is benchmarked against
  the RBC’s performance using the BOPTEST simulation environment under various experiment
  settings, highlighting how the hyperparameters affect the controller’s performance.
  Compared to the RBC, we show that the proposed controllers realise substantial improvements
  in terms of both thermal comfort and operational cost while controlling a single
  zone or two zones simultaneously.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hinderyckx24a
month: 0
tex_title: "{Linearised Data-Driven LSTM-Based Control of Multi-Input HVAC Systems}"
firstpage: 1
lastpage: 13
page: 1-13
order: 1
cycles: false
bibtex_author: Hinderyckx, Andreas and Guillaume, Florence
author:
- given: Andreas
  family: Hinderyckx
- given: Florence
  family: Guillaume
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
pdf: https://proceedings.mlr.press/v242/hinderyckx24a/hinderyckx24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

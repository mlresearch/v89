---
title: Fast and Robust Shortest Paths on Manifolds Learned from Data
abstract: We propose a fast, simple and robust algorithm for computing shortest paths
  and distances on Riemannian manifolds learned from data. This amounts to solving
  a system of ordinary differential equations (ODEs) subject to boundary conditions.
  Here standard solvers perform poorly because they require well-behaved Jacobians
  of the ODE, and usually, manifolds learned from data imply unstable and ill-conditioned
  Jacobians. Instead, we propose a fixed-point iteration scheme for solving the ODE
  that avoids Jacobians. This enhances the stability of the solver, while reduces
  the computational cost. In experiments involving both Riemannian metric learning
  and deep generative models we demonstrate significant improvements in speed and
  stability over both general-purpose state-of-the-art solvers as well as over specialized
  solvers.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: arvanitidis19a
month: 0
tex_title: Fast and Robust Shortest Paths on Manifolds Learned from Data
firstpage: 1506
lastpage: 1515
page: 1506-1515
order: 1506
cycles: false
bibtex_author: Arvanitidis, Georgios and Hauberg, Soren and Hennig, Philipp and Schober,
  Michael
author:
- given: Georgios
  family: Arvanitidis
- given: Soren
  family: Hauberg
- given: Philipp
  family: Hennig
- given: Michael
  family: Schober
date: 2019-04-11
address: 
publisher: PMLR
container-title: Proceedings of the Twenty-Second International Conference on Artificial Intelligence and Statistics
volume: '89'
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 4
  - 11
pdf: http://proceedings.mlr.press/v89/arvanitidis19a/arvanitidis19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/arvanitidis19a/arvanitidis19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

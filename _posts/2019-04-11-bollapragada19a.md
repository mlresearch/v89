---
title: Nonlinear Acceleration of Primal-Dual Algorithms
abstract: We describe a convergence acceleration scheme for multi-step optimization
  algorithms. The extrapolated solution is written as a nonlinear average of the iterates
  produced by the original optimization algorithm. Our scheme does not need the underlying
  fixed-point operator to be symmetric, hence handles e.g. algorithms with momentum
  terms such as Nesterov’s accelerated method, or primal-dual methods such as Chambolle-Pock.
  The weights are computed via a simple linear system and we analyze performance in
  both online and offline modes. We use Crouzeix’s conjecture to show that acceleration
  is controlled by the solution of a Chebyshev problem on the numerical range of a
  nonsymmetric operator modelling the behavior of iterates near the optimum. Numerical
  experiments are detailed on image processing and logistic regression problems.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: bollapragada19a
month: 0
tex_title: Nonlinear Acceleration of Primal-Dual Algorithms
firstpage: 739
lastpage: 747
page: 739-747
order: 739
cycles: false
bibtex_author: Bollapragada, Raghu and Scieur, Damien and d'Aspremont, Alexandre
author:
- given: Raghu
  family: Bollapragada
- given: Damien
  family: Scieur
- given: Alexandre
  family: d’Aspremont
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
pdf: http://proceedings.mlr.press/v89/bollapragada19a/bollapragada19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/bollapragada19a/bollapragada19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

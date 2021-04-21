---
title: Efficient Greedy Coordinate Descent for Composite Problems
abstract: Coordinate descent with random coordinate selection is the current state
  of the art for many large scale optimization problems. However, greedy selection
  of the steepest coordinate on smooth problems can yield convergence rates independent
  of the dimension $n$, requiring $n$ times fewer iterations.  In this paper, we consider
  greedy updates that are based on subgradients for a class of non-smooth composite
  problems, including $L1$-regularized problems, SVMs and related applications. For
  these problems we provide (i) the first linear rates of convergence independent
  of $n$, and show that our greedy update rule provides speedups similar to those
  obtained in the smooth case. This was previously conjectured to be true for a stronger
  greedy coordinate selection strategy.  Furthermore, we show that (ii) our new selection
  rule can be mapped to instances of maximum inner product search, allowing to leverage
  standard nearest neighbor algorithms to speed up the implementation. We demonstrate
  the validity of the approach through extensive numerical experiments.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: karimireddy19a
month: 0
tex_title: Efficient Greedy Coordinate Descent for Composite Problems
firstpage: 2887
lastpage: 2896
page: 2887-2896
order: 2887
cycles: false
bibtex_author: Karimireddy, Sai Praneeth and Koloskova, Anastasia and Stich, Sebastian
  U. and Jaggi, Martin
author:
- given: Sai Praneeth
  family: Karimireddy
- given: Anastasia
  family: Koloskova
- given: Sebastian U.
  family: Stich
- given: Martin
  family: Jaggi
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
pdf: http://proceedings.mlr.press/v89/karimireddy19a/karimireddy19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/karimireddy19a/karimireddy19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

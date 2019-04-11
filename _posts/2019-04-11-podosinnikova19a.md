---
title: Overcomplete Independent Component Analysis via SDP
abstract: 'We present a novel algorithm for overcomplete independent components analysis
  (ICA), where the number of latent sources k exceeds the dimension p of observed
  variables. Previous algorithms either suffer from high computational complexity
  or make strong assumptions about the form of the mixing matrix. Our algorithm does
  not make any sparsity assumption yet enjoys favorable computational and theoretical
  properties. Our algorithm consists of two main steps: (a) estimation of the Hessians
  of the cumulant generating function (as opposed to the fourth and higher order cumulants
  used by most algorithms) and (b) a novel semi-definite programming (SDP) relaxation
  for recovering a mixing component. We show that this relaxation can be efficiently
  solved with a projected accelerated gradient descent method, which makes the whole
  algorithm computationally practical. Moreover, we conjecture that the proposed program
  recovers a mixing component at the rate $k < p^2/4$ and prove that a mixing component
  can be recovered with high probability when $k <(2 - \epsilon)p\log p$ when the
  original components are sampled uniformly at random on the hyper sphere. Experiments
  are provided on synthetic data and the CIFAR-10 dataset of real images.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: podosinnikova19a
month: 0
tex_title: Overcomplete Independent Component Analysis via SDP
firstpage: 2583
lastpage: 2592
page: 2583-2592
order: 2583
cycles: false
bibtex_author: Podosinnikova, Anastasia and Perry, Amelia and Wein, Alexander S. and
  Bach, Francis and d'Aspremont, Alexandre and Sontag, David
author:
- given: Anastasia
  family: Podosinnikova
- given: Amelia
  family: Perry
- given: Alexander S.
  family: Wein
- given: Francis
  family: Bach
- given: Alexandre
  family: d’Aspremont
- given: David
  family: Sontag
date: 2019-04-11
address: 
publisher: PMLR
container-title: Proceedings of Machine Learning Research
volume: '89'
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 4
  - 11
pdf: http://proceedings.mlr.press/v89/podosinnikova19a/podosinnikova19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/podosinnikova19a/podosinnikova19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

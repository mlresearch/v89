---
title: Adaptive MCMC via Combining Local Samplers
abstract: Markov chain Monte Carlo (MCMC) methods are widely used in machine learning.
  One of the major problems with MCMC is the question of how to design chains that
  mix fast over the whole state space; in particular, how to select the parameters
  of an MCMC algorithm. Here we take a different approach and, similarly to parallel
  MCMC methods, instead of trying to find a single chain that samples from the whole
  distribution, we combine samples from several chains run in parallel, each exploring
  only parts of the state space (e.g., a few modes only). The chains are prioritized
  based on the kernel Stein discrepancy, which provides a good measure of performance
  locally. The samples from the independent chains are combined using a novel technique
  for estimating the probability of different regions of the sample space. Experimental
  results demonstrate that the proposed algorithm may provide significant speedups
  in different sampling problems. Most importantly, when combined with the state-of-the-art
  NUTS algorithm as the base MCMC sampler, our method remained competitive with NUTS
  on sampling from unimodal distributions, while significantly outperformed state-of-the-art
  competitors on synthetic multimodal problems as well as on a challenging sensor
  localization task.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: shaloudegi19a
month: 0
tex_title: Adaptive MCMC via Combining Local Samplers
firstpage: 2701
lastpage: 2710
page: 2701-2710
order: 2701
cycles: false
bibtex_author: Shaloudegi, Ki\'{a}rash and Gy\"orgy, Andr\'{a}s
author:
- given: Kiárash
  family: Shaloudegi
- given: András
  family: György
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
pdf: http://proceedings.mlr.press/v89/shaloudegi19a/shaloudegi19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

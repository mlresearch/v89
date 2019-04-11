---
title: Sketching for Latent Dirichlet-Categorical Models
abstract: Recent work has explored transforming data sets into smaller, approximate
  summaries in order to scale Bayesian inference.  We examine a related problem in
  which the parameters of a Bayesian model are very large and expensive to store in
  memory, and propose more compact representations of parameter values that can be
  used during inference.  We focus on a class of graphical models that we refer to
  as latent Dirichlet-Categorical models, and show how a combination of two sketching
  algorithms known as count-min sketch and approximate counters provide an efficient
  representation for them. We show that this sketch combination – which, despite having
  been used before in NLP applications, has not been previously analyzed – enjoys
  desirable properties. We prove that for this class of models, when the sketches
  are used during Markov Chain Monte Carlo inference, the equilibrium of sketched
  MCMC converges to that of the exact chain as sketch parameters are tuned to reduce
  the error rate.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: tassarotti19a
month: 0
tex_title: Sketching for Latent Dirichlet-Categorical Models
firstpage: 256
lastpage: 265
page: 256-265
order: 256
cycles: false
bibtex_author: Tassarotti, Joseph and Tristan, Jean-Baptiste and Wick, Michael
author:
- given: Joseph
  family: Tassarotti
- given: Jean-Baptiste
  family: Tristan
- given: Michael
  family: Wick
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
pdf: http://proceedings.mlr.press/v89/tassarotti19a/tassarotti19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/tassarotti19a/tassarotti19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

---
title: Forward Amortized Inference for Likelihood-Free Variational Marginalization
abstract: In this paper, we introduce a new form of amortized variational inference
  by using the forward KL divergence in a joint-contrastive variational loss. The
  resulting forward amortized variational inference is a likelihood-free method as
  its gradient can be sampled without bias and without requiring any evaluation of
  either the model joint distribution or its derivatives. We prove that our new variational
  loss is optimized by the exact posterior marginals in the fully factorized mean-field
  approximation, a property that is not shared with the more conventional reverse
  KL inference. Furthermore, we show that forward amortized inference can be easily
  marginalized over large families of latent variables in order to obtain a marginalized
  variational posterior. We consider two examples of variational marginalization.
  In our first example we train a Bayesian forecaster for predicting a simplified
  chaotic model of atmospheric convection. In the second example we train an amortized
  variational approximation of a Bayesian optimal classifier by marginalizing over
  the model space. The result is a powerful meta-classification network that can solve
  arbitrary classification problems without further training.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: ambrogioni19a
month: 0
tex_title: Forward Amortized Inference for Likelihood-Free Variational Marginalization
firstpage: 777
lastpage: 786
page: 777-786
order: 777
cycles: false
bibtex_author: Ambrogioni, Luca and G\"{u}\c{c}l\"{u}, Umut and Berezutskaya, Julia
  and van den Borne, Eva and G\"{u}\c{c}l\"{u}t\"{u}rk, Ya\v{g}mur and Hinne, Max
  and Maris, Eric and van Gerven, Marcel
author:
- given: Luca
  family: Ambrogioni
- given: Umut
  family: Güçlü
- given: Julia
  family: Berezutskaya
- given: Eva
  family: Borne
- given: Yaǧmur
  family: Güçlütürk
- given: Max
  family: Hinne
- given: Eric
  family: Maris
- given: Marcel
  family: Gerven
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
pdf: http://proceedings.mlr.press/v89/ambrogioni19a/ambrogioni19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/ambrogioni19a/ambrogioni19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

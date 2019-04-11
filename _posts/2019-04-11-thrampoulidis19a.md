---
title: Lifting high-dimensional non-linear models with Gaussian regressors
abstract: We study the problem of recovering a structured signal $\mathbf{x}_0$ from
  high-dimensional data $\mathbf{y}_i=f(\mathbf{a}_i^T\mathbf{x}_0)$ for some nonlinear
  (and potentially unknown) link function $f$, when the regressors $\mathbf{a}_i$
  are iid Gaussian. Brillinger (1982) showed that ordinary least-squares estimates
  $\mathbf{x}_0$ up to a constant of proportionality $\mu_\ell$, which depends on
  $f$. Recently, Plan & Vershynin (2015) extended this result to the high-dimensional
  setting deriving sharp error bounds for the generalized Lasso. Unfortunately, both
  least-squares and the Lasso fail to recover $\mathbf{x}_0$ when  $\mu_\ell=0$. For
  example, this includes all even link functions. We resolve this issue by proposing
  and analyzing an alternative convex recovery method. In a nutshell, our method treats
  such link functions as if they were linear in a lifted space of higher-dimension.
  Interestingly, our error analysis captures the effect of both the nonlinearity and
  the problem’s geometry in a few simple summary parameters.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: thrampoulidis19a
month: 0
tex_title: Lifting high-dimensional non-linear models with Gaussian regressors
firstpage: 3206
lastpage: 3215
page: 3206-3215
order: 3206
cycles: false
bibtex_author: Thrampoulidis, Christos and Rawat, Ankit Singh
author:
- given: Christos
  family: Thrampoulidis
- given: Ankit Singh
  family: Rawat
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
pdf: http://proceedings.mlr.press/v89/thrampoulidis19a/thrampoulidis19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/thrampoulidis19a/thrampoulidis19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

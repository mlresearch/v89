---
title: Towards Optimal Transport with Global Invariances
abstract: Many problems in machine learning involve calculating correspondences between
  sets of objects, such as point clouds or images. Discrete optimal transport provides
  a natural and successful approach to such tasks whenever the two sets of objects
  can be represented in the same space, or at least distances between them can be
  directly evaluated. Unfortunately neither requirement is likely to hold when object
  representations are learned from data. Indeed, automatically derived representations
  such as word embeddings are typically fixed only up to some global transformations,
  for example, reflection or rotation. As a result, pairwise distances across two
  such instances are ill-defined without specifying their relative transformation.
  In this work, we propose a general framework for optimal transport in the presence
  of latent global transformations. We cast the problem as a joint optimization over
  transport couplings and transformations chosen from a flexible class of invariances,
  propose algorithms to solve it, and show promising results in various tasks, including
  a popular unsupervised word translation benchmark.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: alvarez-melis19a
month: 0
tex_title: Towards Optimal Transport with Global Invariances
firstpage: 1870
lastpage: 1879
page: 1870-1879
order: 1870
cycles: false
bibtex_author: Alvarez-Melis, David and Jegelka, Stefanie and Jaakkola, Tommi S.
author:
- given: David
  family: Alvarez-Melis
- given: Stefanie
  family: Jegelka
- given: Tommi S.
  family: Jaakkola
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
pdf: http://proceedings.mlr.press/v89/alvarez-melis19a/alvarez-melis19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/alvarez-melis19a/alvarez-melis19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

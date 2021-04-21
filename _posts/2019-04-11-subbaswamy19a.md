---
title: 'Preventing Failures Due to Dataset Shift: Learning Predictive Models That
  Transport'
abstract: Classical supervised learning produces unreliable models when training and
  target distributions differ, with most existing solutions requiring samples from
  the target domain. We propose a proactive approach which learns a relationship in
  the training domain that will generalize to the target domain by incorporating prior
  knowledge of aspects of the data generating process that are expected to differ
  as expressed in a causal selection diagram. Specifically, we remove variables generated
  by unstable mechanisms from the joint factorization to yield the Surgery Estimator—an
  interventional distribution that is invariant to the differences across environments.
  We prove that the surgery estimator finds stable relationships in strictly more
  scenarios than previous approaches which only consider conditional relationships,
  and demonstrate this in simulated experiments. We also evaluate on real world data
  for which the true causal diagram is unknown, performing competitively against entirely
  data-driven approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: subbaswamy19a
month: 0
tex_title: 'Preventing Failures Due to Dataset Shift: Learning Predictive Models That
  Transport'
firstpage: 3118
lastpage: 3127
page: 3118-3127
order: 3118
cycles: false
bibtex_author: Subbaswamy, Adarsh and Schulam, Peter and Saria, Suchi
author:
- given: Adarsh
  family: Subbaswamy
- given: Peter
  family: Schulam
- given: Suchi
  family: Saria
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
pdf: http://proceedings.mlr.press/v89/subbaswamy19a/subbaswamy19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/subbaswamy19a/subbaswamy19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

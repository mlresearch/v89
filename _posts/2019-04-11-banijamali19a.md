---
title: Optimizing over a Restricted Policy Class in MDPs
abstract: We address the problem of finding an optimal policy in a Markov decision
  process (MDP) under a restricted policy class defined by the convex hull of a set
  of base policies. This problem is of great interest in applications in which a number
  of reasonably good (or safe) policies are already known and we are interested in
  optimizing in their convex hull. We first prove that solving this problem is NP-hard.
  We then propose an efficient algorithm that finds a policy whose performance is
  almost as good as that of the best convex combination of the base policies, under
  the assumption that the occupancy measures of the base policies have a large overlap.
  The running time of the proposed algorithm is linear in the number of states and
  polynomial in the number of base policies. A distinct advantage of the proposed
  algorithm is that, apart from the computation of the occupancy measures of the base
  policies, it does not need to interact with the environment during the optimization
  process. This is especially important (i) in problems that due to concerns such
  as safety, we are restricted in interacting with the environment only through the
  (safe) base policies, and (ii) in complex systems where estimating the value of
  a policy can be a time consuming process.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: banijamali19a
month: 0
tex_title: Optimizing over a Restricted Policy Class in MDPs
firstpage: 3042
lastpage: 3050
page: 3042-3050
order: 3042
cycles: false
bibtex_author: Banijamali, Ershad and Abbasi-Yadkori, Yasin and Ghavamzadeh, Mohammad
  and Vlassis, Nikos
author:
- given: Ershad
  family: Banijamali
- given: Yasin
  family: Abbasi-Yadkori
- given: Mohammad
  family: Ghavamzadeh
- given: Nikos
  family: Vlassis
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
pdf: http://proceedings.mlr.press/v89/banijamali19a/banijamali19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/banijamali19a/banijamali19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

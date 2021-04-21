---
title: Active Exploration in Markov Decision Processes
abstract: We introduce the active exploration problem in Markov decision processes
  (MDPs). Each state of the MDP is characterized by a random value and the learner
  should gather samples to estimate the mean value of each state as accurately as
  possible. Similarly to active exploration in multi-armed bandit (MAB), states may
  have different levels of noise, so that the higher the noise, the more samples are
  needed. As the noise level is initially unknown, we need to trade off the exploration
  of the environment to estimate the noise and the exploitation of these estimates
  to compute a policy maximizing the accuracy of the mean predictions. We introduce
  a novel learning algorithm to solve this problem showing that active exploration
  in MDPs may be significantly more difficult than in MAB. We also derive a heuristic
  procedure to mitigate the negative effect of slowly mixing policies. Finally, we
  validate our findings on simple numerical simulations.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: tarbouriech19a
month: 0
tex_title: Active Exploration in Markov Decision Processes
firstpage: 974
lastpage: 982
page: 974-982
order: 974
cycles: false
bibtex_author: Tarbouriech, Jean and Lazaric, Alessandro
author:
- given: Jean
  family: Tarbouriech
- given: Alessandro
  family: Lazaric
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
pdf: http://proceedings.mlr.press/v89/tarbouriech19a/tarbouriech19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/tarbouriech19a/tarbouriech19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

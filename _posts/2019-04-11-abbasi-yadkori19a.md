---
title: Model-Free Linear Quadratic Control via Reduction to Expert Prediction
abstract: Model-free approaches for reinforcement learning (RL) and continuous control
  find policies based only on past states and rewards, without fitting a model of
  the system dynamics. They are appealing as they are general purpose and easy to
  implement; however, they also come with fewer theoretical guarantees than model-based
  RL.  In this work, we present a new model-free algorithm for controlling linear
  quadratic (LQ) systems, and show that its regret scales as $O(T^{\xi+2/3})$ for
  any small $\xi>0$ if time horizon satisfies $T>C^{1/\xi}$ for a constant $C$. The
  algorithm is based on a reduction of control of Markov decision processes to an
  expert prediction problem. In practice, it corresponds to a variant of policy iteration
  with forced exploration, where the policy in each phase is greedy with respect to
  the average of all previous value functions.  This is the first model-free algorithm
  for adaptive control of LQ systems that provably achieves sublinear regret and has
  a polynomial computation cost. Empirically, our algorithm dramatically outperforms
  standard policy iteration, but performs worse than a model-based approach.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: abbasi-yadkori19a
month: 0
tex_title: Model-Free Linear Quadratic Control via Reduction to Expert Prediction
firstpage: 3108
lastpage: 3117
page: 3108-3117
order: 3108
cycles: false
bibtex_author: Abbasi-Yadkori, Yasin and Lazic, Nevena and Szepesvari, Csaba
author:
- given: Yasin
  family: Abbasi-Yadkori
- given: Nevena
  family: Lazic
- given: Csaba
  family: Szepesvari
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
pdf: http://proceedings.mlr.press/v89/abbasi-yadkori19a/abbasi-yadkori19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/abbasi-yadkori19a/abbasi-yadkori19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

---
title: Efficient Linear Bandits through Matrix Sketching
abstract: We prove that two popular linear contextual bandit algorithms, OFUL and
  Thompson Sampling, can be made efficient using Frequent Directions, a deterministic
  online sketching technique. More precisely, we show that a sketch of size $m$ allows
  a $\mathcal{O}(md)$ update time for both algorithms, as opposed to $\Omega(d^2)$
  required by their non-sketched versions in general (where $d$ is the dimension of
  context vectors). This computational speedup is accompanied by regret bounds of
  order $(1+\varepsilon_m)^{3/2}d\sqrt{T}$ for OFUL and of order $\big((1+\varepsilon_m)d\big)^{3/2}\sqrt{T}$
  for Thompson Sampling, where $\varepsilon_m$ is bounded by the sum of the tail eigenvalues
  not covered by the sketch. In particular, when the selected contexts span a subspace
  of dimension at most $m$, our algorithms have a regret bound matching that of their
  slower, non-sketched counterparts. Experiments on real-world datasets corroborate
  our theoretical results.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: kuzborskij19a
month: 0
tex_title: Efficient Linear Bandits through Matrix Sketching
firstpage: 177
lastpage: 185
page: 177-185
order: 177
cycles: false
bibtex_author: Kuzborskij, Ilja and Cella, Leonardo and Cesa-Bianchi, Nicol\`{o}
author:
- given: Ilja
  family: Kuzborskij
- given: Leonardo
  family: Cella
- given: Nicolò
  family: Cesa-Bianchi
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
pdf: http://proceedings.mlr.press/v89/kuzborskij19a/kuzborskij19a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v89/kuzborskij19a/kuzborskij19a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

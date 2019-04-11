---
title: Adaptive Activity Monitoring with Uncertainty Quantification in Switching Gaussian
  Process Models
abstract: Emerging wearable sensors have enabled the unprecedented ability to continuously
  monitor human activities for healthcare purposes. However, with so many ambient
  sensors collecting different measurements, it becomes important not only to maintain
  good monitoring accuracy, but also low power consumption to ensure sustainable monitoring.
  This power-efficient sensing scheme can be achieved by deciding which group of sensors
  to use at a given time, requiring an accurate characterization of the trade-off
  between sensor energy usage and the uncertainty in ignoring certain sensor signals
  while monitor- ing. To address this challenge in the context of activity monitoring,
  we have designed an adaptive activity monitoring framework. We first propose a switching
  Gaussian process to model the observed sensor signals emitting from the underlying
  activity states. To efficiently compute the Gaussian process model likelihood and
  quantify the context prediction uncertainty, we propose a block circulant embedding
  technique and use Fast Fourier Transforms (FFT) for inference. By computing the
  Bayesian loss function tailored to switching Gaussian processes, an adaptive monitoring
  procedure is developed to select features from available sensors that optimize the
  trade-off between sensor power consumption and the prediction performance quantified
  by state prediction entropy. We demonstrate the effectiveness of our framework on
  the popular benchmark of UCI Human Activity Recognition using Smartphones.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: ardywibowo19a
month: 0
tex_title: Adaptive Activity Monitoring with Uncertainty Quantification in Switching
  Gaussian Process Models
firstpage: 266
lastpage: 275
page: 266-275
order: 266
cycles: false
bibtex_author: Ardywibowo, Randy and Zhao, Guang and Wang, Zhangyang and Mortazavi,
  Bobak and Huang, Shuai and Qian, Xiaoning
author:
- given: Randy
  family: Ardywibowo
- given: Guang
  family: Zhao
- given: Zhangyang
  family: Wang
- given: Bobak
  family: Mortazavi
- given: Shuai
  family: Huang
- given: Xiaoning
  family: Qian
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
pdf: http://proceedings.mlr.press/v89/ardywibowo19a/ardywibowo19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

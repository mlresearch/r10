---
abstract: Multinomial logistic regression is one of the most popular models for modelling
  the effect of explanatory variables on a subject choice between a set of specified
  options. This model has found numerous applications in machine learning, psychology
  or economy. Bayesian inference in this model is non trivial and requires, either
  to resort to a MetropolisHastings algorithm, or rejection sampling within a Gibbs
  sampler. In this paper, we propose an alternative model to multinomial logistic
  regression. The model builds on the Plackett-Luce model, a popular model for multiple
  comparisons. We show that the introduction of a suitable set of auxiliary variables
  leads to an Expectation-Maximization algorithm to find Maximum A Posteriori estimates
  of the parameters. We further provide a full Bayesian treatment by deriving a Gibbs
  sampler, which only requires to sample from highly standard distributions. We also
  propose a variational approximate inference scheme. All are very simple to implement.
  One property of our Plackett-Luce regression model is that it learns a sparse set
  of feature weights. We compare our method to sparse Bayesian multinomial logistic
  regression and show that it is competitive, especially in presence of polychotomous
  data.
title: 'Plackett-Luce regression: A new Bayesian model for polychotomous data'
year: '2012'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: archambeau12a
month: 0
tex_title: 'Plackett-Luce regression: A new {B}ayesian model for polychotomous data'
firstpage: 81
lastpage: 89
page: 81-89
order: 81
cycles: false
bibtex_author: Archambeau, Cedric and Caron, Francois
author:
- given: Cedric
  family: Archambeau
- given: Francois
  family: Caron
date: 2012-08-14
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 28th Conference on Uncertainty in Artificial Intelligence
volume: R10
genre: inproceedings
issued:
  date-parts:
  - 2012
  - 8
  - 14
pdf: https://raw.githubusercontent.com/mlresearch/r10/main/assets/archambeau12a/archambeau12a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

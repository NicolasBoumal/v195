---
title: 'Algorithmic Gaussianization through Sketching: Converting Data into Sub-gaussian
  Random Designs'
abstract: 'Algorithmic Gaussianization is a phenomenon that can arise when using randomized
  sketching or sampling methods to produce smaller representations of large datasets:
  For certain tasks, these sketched representations have been observed to exhibit
  many robust performance characteristics that are known to occur when a data sample
  comes from a sub-gaussian random design, which is a powerful statistical model of
  data distributions. However, this phenomenon has only been studied for specific
  tasks and metrics, or by relying on computationally expensive methods. We address
  this by providing an algorithmic framework for gaussianizing data using sparse sketching
  operators, proving that it is possible to efficiently construct data sketches that
  are nearly indistinguishable (in terms of total variation distance) from sub-gaussian
  random designs. In particular, relying on a recently introduced sketching technique
  called Leverage Score Sparsified (LESS) embeddings, we show that one can construct
  an $n\times d$ sketch of an$N\times d$ matrix $A$, where $n\ll N$, that is nearly
  indistinguishable from a sub-gaussian design, in time $O(\mathrm{nnz}(A)\log N +
  nd^2)$, where $\mathrm{nnz}(A)$ is the number of non-zero entries in $A$. As a consequence,
  strong statistical guarantees and precise asymptotics available for the estimators
  produced from sub-gaussian designs (e.g., for least squares and Lasso regression,
  covariance estimation, low-rank approximation, etc.) can be straightforwardly adapted
  to our sketching framework. We illustrate this with a new approximation guarantee
  for sketched least squares, among other examples. The key technique that enables
  our analysis is a novel variant of the Hanson-Wright inequality on the concentration
  of random quadratic forms, which we establish for random vectors that arise from
  sparse sketches.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: derezinski23a
month: 0
tex_title: 'Algorithmic Gaussianization through Sketching: Converting Data into Sub-gaussian
  Random Designs'
firstpage: 1
lastpage: 36
page: 1-36
order: 1
cycles: false
bibtex_author: Derezi{\'n}ski, Micha{\l}
author:
- given: Michał
  family: Dereziński
date: 2023-07-12
address: 
container-title: Proceedings of Thirty Sixth Conference on Learning Theory
volume: '195'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 7
  - 12
pdf: https://proceedings.mlr.press/v195/derezinski23a/derezinski23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

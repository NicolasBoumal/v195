---
title: Testing of Index-Invariant Properties in the Huge Object Model
abstract: 'Distribution testing is a central part of property testing, with applications
  to various research areas, such as computational and statistical learning, information
  theory, and probabilistic program checking.    The original distribution testing
  model relies on samples drawn independently from the distribution to be tested.
  However, when the distribution in question is over the $n$-dimensional Hamming cube
  $\left\{0,1\right\}^{n}$ for a large $n$, even reading a few samples is infeasible.
  To address this, Goldreich and Ron [ITCS 2022] have defined a model called the \emph{huge
  object model}, in which the samples may only be queried in a few places.For any
  sample/query model, the following three questions are considered fundamental: {\bf
  (i)} understand what classes of objects can be  “learned \emph{easily}", {\bf (ii)}
  characterize {\em testable properties}, that is, properties that can be tested in
  the given sample/query model using a constant number of samples/queries, and {\bf
  (iii)} understand the {\em gap} between {\em adaptive} and {\em non-adaptive} query/sample
  complexities.In this work, we study these questions for the huge object model for
  distribution testing. To do so, we initiate a study of a general class of distribution
  properties that are invariant under a permutation of the indices of the vectors
  in $\left\{0,1\right\}^{n}$, while still not being necessarily fully symmetric as
  per the definition used in traditional distribution testing.We prove that every
  distribution over  $\left\{0,1\right\}^{n}$ whose support has a bounded VC-dimension
  can be efficiently learned up to a permutation. The number of queries made by the
  algorithm depends only on the VC-dimension of the support of the distribution and
  is independent of $n$. This gives efficient testers for index-invariant distribution
  properties that admit a global VC-dimension bound. To complement this result, we
  argue that satisfying only index-invariance or only a VC-dimension bound is insufficient
  to guarantee a tester whose query complexity is independent of $n$. Moreover, we
  prove that the dependency of the sample and query complexities of our tester on
  the VC-dimension is essentially tight. As a second part of this work, we address
  the question of thenumber of queries required for non-adaptive testing. We show
  that it can be at most quadratic in the numberof queries required for an adaptive
  tester in the case of index-invariant properties. This contrasts with the tight
  (easily provable) exponential gap between adaptive and non-adaptive testers for
  general non-index-invariant properties. Finally, we provide an index-invariant property
  for which the quadratic gap between adaptive and non-adaptive query complexities
  for testing is almost tight.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty23a
month: 0
tex_title: Testing of Index-Invariant Properties in the Huge Object Model
firstpage: 1
lastpage: 72
page: 1-72
order: 1
cycles: false
bibtex_author: Chakraborty, Sourav and Fischer, Eldar and Ghosh, Arijit and Mishra,
  Gopinath and Sen, Sayantan
author:
- given: Sourav
  family: Chakraborty
- given: Eldar
  family: Fischer
- given: Arijit
  family: Ghosh
- given: Gopinath
  family: Mishra
- given: Sayantan
  family: Sen
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
pdf: https://proceedings.mlr.press/v195/chakraborty23a/chakraborty23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

---
title: Resolving the Mixing Time of the Langevin Algorithm to its Stationary Distribution
  for Log-Concave Sampling
abstract: 'Sampling from a high-dimensional distribution is a fundamental task in
  statistics, engineering, and the sciences. A canonical approach is the Langevin
  Algorithm, i.e., the Markov chain for the discretized Langevin Diffusion. This is
  the sampling analog of Gradient Descent. Despite being studied for several decades
  in multiple communities, tight mixing bounds for this algorithm remain unresolved
  even in the seemingly simple setting of log-concave distributions over a bounded
  domain. This paper completely characterizes the mixing time of the Langevin Algorithm
  to its stationary distribution in this setting (and others). This mixing result
  can be combined with any bound on the discretization bias in order to sample from
  the stationary distribution of the Langevin Diffusion. In this way, we disentangle
  the study of the mixing and bias of the Langevin Algorithm.Our key insight is to
  analyze the Langevin Algorithm’s convergence by using a new Lyapunov function: the
  shifted divergence, a quantity studied in the differential privacy literature. Briefly,
  this Lyapunov function is a version of the Renyi divergence that is smoothed in
  optimal transport distance, and we use the amount of smoothing to measure the Langevin
  Algorithm’s progress. In addition to giving a short, simple proof of optimal mixing
  bounds, this analysis approach also has several additional appealing properties.
  First, our approach removes all unnecessary assumptions required by other sampling
  analyses. Second, our approach unifies many settings: it extends if the Langevin
  Algorithm uses projections, stochastic mini-batch gradients, or strongly convex
  potentials (whereby our mixing time improves exponentially). Third, our approach
  unifies many metrics: it proves mixing in the stringent notion of Renyi divergence,
  which immediately implies mixing in all common metrics via standard comparison inequalities.
  Fourth, our approach exploits convexity only through the contractivity of a gradient
  step—reminiscent of how convexity is used in textbook proofs of Gradient Descent. '
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: altschuler23a
month: 0
tex_title: Resolving the Mixing Time of the Langevin Algorithm to its Stationary Distribution
  for Log-Concave Sampling
firstpage: 1
lastpage: 2
page: 1-2
cycles: false
bibtex_author: Altschuler, Jason and Talwar, Kunal
author:
- given: Jason
  family: Altschuler
- given: Kunal
  family: Talwar
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
pdf: https://proceedings.mlr.press/v195/altschuler23a/altschuler23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

---
title: 'Instance-Optimality in Interactive Decision Making: Toward a Non-Asymptotic
  Theory'
abstract: We consider the development of adaptive, instance-dependent algorithms for
  interactive decision making (bandits, reinforcement learning, and beyond) that,
  rather than only performing well in the worst case, adapt to favorable properties
  of real-world instances for improved performance. We aim for instance-optimality,
  a strong notion of adaptivity which asserts that, on any particular problem instance,
  the algorithm under consideration outperforms all consistent algorithms. Instance-optimality
  enjoys a rich asymptotic theory originating from the work of \citet{lai1985asymptotically}
  and \citet{graves1997asymptotically}, but non-asymptotic guarantees have remained
  elusive outside of certain special cases. Even for problems as simple as tabular
  reinforcement learning, existing algorithms do not attain instance-optimal performance
  until the number of rounds of interaction is doubly exponential in the number of
  states.In this paper, we take the first step toward developing a non-asymptotic
  theory of instance-optimal decision making with general function approximation.
  We introduce a new complexity measure, the Allocation-Estimation Coefficient (AEC),
  and provide a new algorithm, AE2, which attains non-asymptotic instance-optimal
  performance at a rate controlled by the AEC. Our results recover the best known
  guarantees for well-studied problems such as finite-armed and linear bandits and,
  when specialized to tabular reinforcement learning, attain the first instance-optimal
  regret bounds with polynomial dependence on all problem parameters, improving over
  prior work exponentially. We complement these results with lower bounds that show
  that i) existing notions of statistical complexity are insufficient to derive non-asymptotic
  guarantees, and ii) under certain technical conditions, boundedness of the Allocation-Estimation
  Coefficient is necessary to learn an instance-optimal allocation of decisions in
  finite time.
section: Original Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wagenmaker23a
month: 0
tex_title: 'Instance-Optimality in Interactive Decision Making: Toward a Non-Asymptotic
  Theory'
firstpage: 1322
lastpage: 1472
page: 1322-1472
order: 1322
cycles: false
bibtex_author: Wagenmaker, Andrew J. and Foster, Dylan J.
author:
- given: Andrew J.
  family: Wagenmaker
- given: Dylan J.
  family: Foster
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
pdf: https://proceedings.mlr.press/v195/wagenmaker23a/wagenmaker23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

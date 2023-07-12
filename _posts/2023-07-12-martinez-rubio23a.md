---
title: 'Accelerated Riemannian Optimization: Handling Constraints with a Prox to Bound
  Geometric Penalties'
abstract: We propose a globally-accelerated, first-order method for the optimization
  of smooth and (strongly or not) geodesically-convex functions in a wide class of
  Hadamard manifolds. We achieve the same convergence rates as Nesterov’s accelerated
  gradient descent, up to a multiplicative geometric penalty and log factors.  Crucially,
  we can enforce our method to stay within a compact set we define. Prior fully accelerated
  works \emph{resort to assuming} that the iterates of their algorithms stay in some
  pre-specified compact set, except for two previous methods of limited applicability.
  For our manifolds, this solves the open question in (Kim and Yang, 2022) about obtaining
  global general acceleration without iterates assumptively staying in the feasible
  set.In our solution, we design an accelerated Riemannian inexact proximal point
  algorithm, which is a result that was unknown even with exact access to the proximal
  operator, and is of independent interest. For smooth functions, we show we can implement
  the prox step inexactly with first-order methods in Riemannian balls of certain
  diameter that is enough for global accelerated optimization.
section: Original Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: martinez-rubio23a
month: 0
tex_title: 'Accelerated Riemannian Optimization: Handling Constraints with a Prox
  to Bound Geometric Penalties'
firstpage: 359
lastpage: 393
page: 359-393
order: 359
cycles: false
bibtex_author: Mart{\'i}nez-Rubio, David and Pokutta, Sebastian
author:
- given: David
  family: Martínez-Rubio
- given: Sebastian
  family: Pokutta
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
pdf: https://proceedings.mlr.press/v195/martinez-rubio23a/martinez-rubio23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

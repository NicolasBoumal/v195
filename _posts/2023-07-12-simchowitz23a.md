---
title: 'Tackling Combinatorial Distribution Shift: A Matrix Completion Perspective'
abstract: 'Obtaining rigorous statistical guarantees for generalization under distribution
  shift remains an open and active research area. We study a setting we call    \emph{combinatorial
  distribution shift}, where (a) under the test- and training-distributions,  the
  labels $z$ are determined by pairs of features $(x,y)$, (b) the training  distribution
  has coverage of certain \emph{marginal} distributions over $x$ and $y$ separately,
  but (c) the test distribution involves examples from a product distribution over
  $(x,y)$ that is \emph{not} covered by the training distribution. Focusing on the
  special case where the labels are given by \emph{bilinear embeddings}  into a Hilbert
  space $\mathcal H$: $\mathbb{E}[z \mid x,y ]=⟨f_{\star}(x),g_{\star}(y)\rangle_{\mathcal{H}}$,
  we aim to extrapolate to a test distribution domain that is {not} covered in training,
  or \emph{bilinear combinatorial extrapolation}. Our setting generalizes a special
  case of matrix completion from missing-not-at-random data,  for which all existing
  results require the ground-truth matrices to be either \emph{exactly low-rank},
  or to exhibit very sharp spectral cutoffs.  In this work, we develop a series of
  theoretical results that enable bilinear combinatorial extrapolation under \emph{gradual}
  spectral decay as observed in typical high-dimensional data, including novel algorithms,
  generalization guarantees, and linear-algebraic results. A key tool is a novel perturbation
  bound for the rank-$k$ singular value decomposition approximations between two matrices
  that depends on the \emph{relative} spectral gap rather than the \emph{absolute}
  spectral gap, a result we think may be of broader independent interest.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: simchowitz23a
month: 0
tex_title: 'Tackling Combinatorial Distribution Shift: A Matrix Completion Perspective'
firstpage: 1
lastpage: 113
page: 1-113
order: 1
cycles: false
bibtex_author: Simchowitz, Max and Gupta, Abhishek and Zhang, Kaiqing
author:
- given: Max
  family: Simchowitz
- given: Abhishek
  family: Gupta
- given: Kaiqing
  family: Zhang
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
pdf: https://proceedings.mlr.press/v195/simchowitz23a/simchowitz23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

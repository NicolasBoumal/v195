---
title: Distribution-Independent Regression for Generalized Linear Models with Oblivious
  Corruptions
abstract: 'We demonstrate the first algorithms for the problem of regression for generalized
  linear models (GLMs) in the presence of additive oblivious noise. We assume we have
  sample access to examples $(x, y)$ where $y$ is a noisy measurement of $g(w^* \cdot
  x)$. In particular, $y = g(w^* \cdot x) + \xi + \eps$ where $\xi$ is the oblivious
  noise drawn independently of $x$, satisfying  $\Pr[\xi = 0] \geq o(1)$, and $\eps
  \sim \cN(0, \sigma^2)$. Our goal is to accurately recover a function $g(w \cdot
  x)$ with arbitrarily small error when compared to the true values $g(w^* \cdot x)$,
  rather than the noisy measurements $y$. We present an algorithm that tackles the
  problem in its most general distribution-independent setting, where the solution
  may not be identifiable. The algorithm is designed to return the solution if it
  is identifiable, and otherwise return a small list of candidates, one of which is
  close to the true solution. Furthermore, we characterize a necessary and sufficient
  condition for identifiability, which holds in broad settings. The problem is identifiable
  when the quantile at which $\xi + \eps = 0$ is known, or when the family of hypotheses
  does not contain candidates that are nearly equal to a translated $g(w^* \cdot x)
  + A$ for some real number $A$, while also having large error when compared to $g(w^*
  \cdot x)$. This is the first result for GLM regression which can handle more than
  half the samples being arbitrarily corrupted. Prior work focused largely on the
  setting of linear regression with oblivious noise, and giving algorithms under more
  restrictive assumptions.  '
section: Original Papers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas23e
month: 0
tex_title: Distribution-Independent Regression for Generalized Linear Models with
  Oblivious Corruptions
firstpage: 5453
lastpage: 5475
page: 5453-5475
order: 5453
cycles: false
bibtex_author: Diakonikolas, Ilias and Karmalkar, Sushrut and Park, Jong Ho and Tzamos,
  Christos
author:
- given: Ilias
  family: Diakonikolas
- given: Sushrut
  family: Karmalkar
- given: Jong Ho
  family: Park
- given: Christos
  family: Tzamos
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
pdf: https://proceedings.mlr.press/v195/diakonikolas23e/diakonikolas23e.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

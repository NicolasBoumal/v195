---
title: The Complexity of Markov Equilibrium in Stochastic Games
abstract: We show that computing approximate stationary Markov coarse correlated equilibria
  (CCE) in general-sum stochastic games is PPAD-hard, even when there are two players,
  the game is turn-based, the discount factor is an absolute constant, and the approximation
  is an absolute constant. Our intractability results stand in sharp contrast to the
  results in normal-form games, where exact CCEs are efficiently computable. A fortiori,
  our results imply that, in the setting of multi-agent reinforcement learning (MARL),
  it is computationally hard to learn stationary Markov CCE policies in stochastic
  games, even when the interaction is two-player and turn-based, and both the discount
  factor and the desired approximation of the learned policies is an absolute constant.
  In turn, these results stand in sharp contrast to single-agent reinforcement learning
  (RL) where near-optimal stationary Markov policies can be computationally efficiently
  learned. Complementing our intractability results for stationary Markov CCEs, we
  provide a decentralized algorithm (assuming shared randomness among players) for
  learning a nonstationary Markov CCE policy with polynomial time and sample complexity
  in all problem parameters. Previous work for learning Markov CCE policies all required
  exponential time and sample complexity in the number of players. In balance, our
  work advocates for the use of nonstationary Markov CCE policies as a computationally
  and statistically tractable solution concept in MARL, advancing an important and
  outstanding frontier in machine learning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: daskalakis23a
month: 0
tex_title: The Complexity of Markov Equilibrium in Stochastic Games
firstpage: 1
lastpage: 55
page: 1-55
order: 1
cycles: false
bibtex_author: Daskalakis, Constantinos and Golowich, Noah and Zhang, Kaiqing
author:
- given: Constantinos
  family: Daskalakis
- given: Noah
  family: Golowich
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
pdf: https://proceedings.mlr.press/v195/daskalakis23a/daskalakis23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

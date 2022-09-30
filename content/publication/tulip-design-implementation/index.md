---
title: Design and implementation of a modular interior-point solver for linear
  optimization
publication_types:
  - "2"
authors:
  - admin
  - Miguel F. Anjos
  - Andrea Lodi
doi: https://doi.org/10.1007/s12532-020-00200-8
publication: Mathematical Programming Computation
publication_short: Math. Prog. Comp.
abstract: "This paper introduces the algorithmic design and implementation of
  Tulip, an open-source interior-point solver for linear optimization. It
  implements a regularized homogeneous interior-point algorithm with multiple
  centrality corrections, and therefore handles unbounded and infeasible
  problems. The solver is written in Julia, thus allowing for a flexible and
  efficient implementation: Tulip’s algorithmic framework is fully disentangled
  from linear algebra implementations and from a model’s arithmetic. In
  particular, this allows to seamlessly integrate specialized routines for
  structured problems. Extensive computational results are reported. We find
  that Tulip is competitive with open-source interior-point solvers on the H.
  Mittelmann’s benchmark of barrier linear programming solvers. Furthermore, we
  design specialized linear algebra routines for structured master problems in
  the context of Dantzig–Wolfe decomposition. These routines yield a tenfold
  speedup on large and dense instances that arise in power systems operation and
  two-stage stochastic programming, thereby outperforming state-of-the-art
  commercial interior point method solvers. Finally, we illustrate Tulip’s
  ability to use different levels of arithmetic precision by solving problems in
  extended precision."
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2021-02-08T21:13:14.851Z
---

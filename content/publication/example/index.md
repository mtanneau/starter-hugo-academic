---
abstract: The Security-Constrained Economic Dispatch (SCED) is a fundamental
  optimization model for Transmission System Operators (TSO) to clear real-time
  energy markets while ensuring reliable operations of power grids. In a context
  of growing operational uncertainty, due to increased penetration of renewable
  generators and distributed energy resources, operators must continuously
  monitor risk in real-time, i.e., they must quickly assess the system’s
  behavior under various changes in load and renewable production.
  Unfortunately, systematically solving an optimization problem for each such
  scenario is not practical given the tight constraints of real-time operations.
  To overcome this limitation, this paper proposes to learn an optimization
  proxy for SCED, i.e., a Machine Learning (ML) model that can predict an
  optimal solution for SCED in milliseconds. Motivated by a principled analysis
  of the market-clearing optimizations of MISO, the paper proposes a novel
  just-in-time ML pipeline that addresses the main challenges of learning SCED
  solutions, i.e., the variability in load, renewable output and production
  costs, as well as the combinatorial structure of commitment decisions. A novel
  combined classification-plus-regression architecture is also proposed, to
  further capture the behavior of SCED solutions. Numerical experiments are
  reported on the French transmission system, and demonstrate the approach’s
  ability to produce, within a time frame that is compatible with real-time
  operations, accurate optimization proxies that produce relative errors below
  1%.
draft: false
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - Wenbo Chen
  - admin
  - Pascal Van Hentenryck
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *EPSR*
url_source: ""
url_video: ""
author_notes: []
publication: In Electric Power Systems Research
featured: false
date: 2022-07-03T00:00:00.000Z
url_slides: ""
title: Learning Optimization Proxies for Large-Scale Security-Constrained
  Economic Dispatch
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
doi: https://doi.org/10.1016/j.epsr.2022.108566
---

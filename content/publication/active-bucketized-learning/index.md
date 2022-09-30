---
title: Active Bucketized Learning for ACOPF Optimization Proxies
publication_types:
  - "3"
authors:
  - Michael Klamkin
  - admin
  - Terrence W. Mak
  - Pascal Van Hentenryck
doi: https://doi.org/10.48550/arXiv.2208.07497
abstract: This paper considers optimization proxies for Optimal Power Flow
  (OPF), i.e., machine-learning models that approximate the input/output
  relationship of OPF. Recent work has focused on showing that such proxies can
  be of high fidelity. However, their training requires significant data, each
  instance necessitating the (offline) solving of an OPF for a sample of the
  input distribution. To meet the requirements of market-clearing applications,
  this paper proposes Active Bucketized Sampling (ABS), a novel active learning
  framework that aims at training the best possible OPF proxy within a time
  limit. ABS partitions the input distribution into buckets and uses an
  acquisition function to determine where to sample next. It relies on an
  adaptive learning rate that increases and decreases over time. Experimental
  results demonstrate the benefits of ABS
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-16T20:53:17.983Z
---

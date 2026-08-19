---
title: "Alignment-Sensitive Minimax Rates for Spectral Algorithms with Learned Kernels"

authors:
  - Dongming Huang
  - me
  - Yicheng Li
  - Qian Lin

date: "2026-05-01T00:00:00Z"
publishDate: "2026-05-01T00:00:00Z"

publication_types: ["paper-conference"]

publication:
  name: "Proceedings of the 43rd International Conference on Machine Learning"
  volume: 306

peer_reviewed: true
open_access: true

abstract: >-
  We study spectral algorithms in settings where kernels may arise from a
  learning procedure, and ask how the resulting spectral order affects risk.
  We introduce the effective span dimension (ESD), an alignment-sensitive
  complexity measure that depends jointly on the target signal, the spectral
  order induced by the kernel, and the noise level. The ESD is defined without
  requiring eigen-decay conditions or source conditions, and it captures how
  much of the target signal lies in the leading spectral span. We prove that,
  for sequence models whose ESD is at most K, the minimax excess risk scales
  with the noise variance times K, and we extend the framework to linear
  models and RKHS regression. Furthermore, we analyze over-parameterized
  gradient flow in a fixed-eigenbasis spectral learning model and prove that
  it can reduce the ESD under certain conditions. Together with numerical
  experiments, these results connect adaptive feature learning with reductions
  in ESD and offer a novel perspective on generalization beyond traditional
  fixed-kernel theories.

summary: >-
  An alignment-sensitive minimax framework for spectral algorithms based on
  effective span dimension, with applications to learned kernels, linear
  models, RKHS regression, and over-parameterized gradient flow.

tags:
  - Statistical Learning Theory
  - Kernel Methods
  - Minimax Theory
  - Spectral Algorithms
  - Adaptive Learning

featured: false

links:
  # Replace the empty URL with the OpenReview forum page.
  - type: source
    label: Source
    url: "https://openreview.net/forum?id=4HrWo5x7YF"
  - type: pdf
    url: "Alignment-Sensitive Minimax Rates for Spectral Algorithms with Learned Kernels.pdf"

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
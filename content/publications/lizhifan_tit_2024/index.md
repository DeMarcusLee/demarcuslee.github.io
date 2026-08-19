---
title: 'Estimating Double Sparse Structures Over $\ell_u(\ell_q)$-Balls: Minimax Rates and Phase Transition'

# Authors
# `me` should correspond to content/authors/me/.
authors:
  - me
  - 'Yanhang Zhang'
  - 'Jianxin Yin'

# Author notes
author_notes:
  - 'First author'
  - 
  - 

# Online publication date
date: '2024-08-29T00:00:00Z'

# Schedule page publish date
publishDate: '2024-08-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata
publication:
  name: 'IEEE Transactions on Information Theory'
  short_name: 'IEEE Trans. Inf. Theory'

peer_reviewed: true

# The paper is available for personal use through IEEE Xplore.
open_access: false

abstract: >
  This paper studies high-dimensional double sparse structures, where the
  parameter of interest simultaneously exhibits group-wise and element-wise
  sparsity. By combining the Gilbert-Varshamov bound and its variants, we
  develop a novel lower bound technique for the metric entropy of double sparse
  parameter spaces over $\ell_u(\ell_q)$-balls with $u, q \in [0, 2)$. Using this technique
  together with Fano's inequality, we establish lower bounds for the estimation
  error. Matching upper bounds are obtained through a direct analysis of
  constrained least-squares estimators and empirical process techniques. For
  $u, q \in (0, 2)$, we identify a phase transition phenomenon in the minimax
  rates. We further extend the results to double sparse linear regression and
  develop a Double Sparse Iterative Hard Thresholding (DSIHT) procedure with
  minimax optimality guarantees. Numerical experiments demonstrate the
  advantages of the proposed method over existing iterative hard thresholding
  methods and the sparse group Lasso.
math: true

summary: >
  We establish minimax rates and phase transition phenomena for double sparse
  structures over $\ell_u(\ell_q)$-balls, and propose a minimax-optimal Double Sparse
  Iterative Hard Thresholding method for double sparse linear regression.

tags:
  - Double sparsity
  - High-dimensional statistics
  - Minimax rates
  - Phase transition
  - Gilbert-Varshamov bound
  - Iterative hard thresholding
  - Double sparse regression

# Do not include this paper in Featured Publications for now.
featured: false

# Standard identifiers
hugoblox:
  ids:
    doi: '10.1109/TIT.2024.3451512'

# Custom links
links:
  - type: pdf
    url: 2207.11888v2.pdf


# Optional featured image.
# Add this section only if a featured image exists in this folder.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# No associated project or slides for now.
projects: []
slides: ''
---
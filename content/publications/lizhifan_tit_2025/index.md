---
title: 'Rethinking Hard Thresholding Pursuit: Full Adaptation and Sharp Estimation'

# Authors
# `me` should correspond to content/authors/me/.
authors:
  - 'Yanhang Zhang'
  - 'Shixiang Liu'
  - me
  - 'Xueqin Wang'
  - 'Jianxin Yin'

# Author notes
author_notes:
  - 
  - 
  - 'Corresponding author'
  - 
  - 

# Online publication date
date: '2025-08-29T00:00:00Z'

# Schedule page publish date
publishDate: '2025-08-29T00:00:00Z'

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
  Hard Thresholding Pursuit (HTP) has attracted increasing attention for its
  robust theoretical guarantees and impressive numerical performance in
  non-convex optimization. This paper considers a high-dimensional linear
  regression model with n observations, p predictors, and an unknown
  $s^{\star}$-sparse signal $\beta^{\star}$ corrupted by noise with magnitude sigma. We
  introduce a novel tuning-free procedure, namely Full-Adaptive HTP (FAHTP),
  that simultaneously adapts to the unknown sparsity and signal strength of
  the underlying model. Our theoretical analysis rigorously characterizes the
  iterative thresholding dynamics of FAHTP and provides refined theoretical
  insights. Specifically, under the beta-min condition
  $\min_{i \in S^{\star}} |\beta^{\star}_i| >= C \sigma \sqrt{(log(p)/n)}$, FAHTP achieves
  the oracle estimation rate $\sigma \sqrt{s^{\star}/n}$ and recovers the true
  support set exactly. More importantly, even without the beta-min condition,
  FAHTP achieves a tighter error bound than the classical minimax rate with
  high probability. Comprehensive numerical experiments substantiate our
  theoretical findings and demonstrate the effectiveness and robustness of
  the proposed FAHTP procedure.

math: true

summary: >
  We propose a tuning-free Full-Adaptive Hard Thresholding Pursuit procedure
  that adapts simultaneously to unknown sparsity, noise level, and signal
  strength. Under the beta-min condition, FAHTP achieves the oracle estimation
  rate and exact support recovery; for general signals, it obtains a sharper
  estimation bound than the classical minimax rate.

tags:
  - Hard thresholding pursuit
  - Full adaptation
  - High-dimensional linear regression
  - Minimax optimality
  - Oracle estimation
  - Exact support recovery
  - Beta-min condition
  - Restricted isometry property
  - Sparse estimation

# Do not include this paper in Featured Publications for now.
featured: false

# Standard identifiers
hugoblox:
  ids:
    doi: '10.1109/TIT.2025.3603987'

# Custom links
links:
  - type: pdf
    url: 'Rethinking_Hard_Thresholding_Pursuit_Full_Adaptation_and_Sharp_Estimation.pdf'


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
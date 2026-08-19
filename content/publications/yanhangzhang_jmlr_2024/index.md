---
title: 'A Minimax Optimal Approach to High-Dimensional Double Sparse Linear Regression'

# Authors
# `me` should correspond to content/authors/me/.
authors:
  - 'Yanhang Zhang'
  - me
  - 'Shixiang Liu'
  - 'Jianxin Yin'

# Author notes
author_notes:
  - 
  - 'Co-first author'
  -
  - 'Corresponding author'

# Online publication date
date: '2024-12-04T00:00:00Z'

# Schedule page publish date
publishDate: '2024-12-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata
publication:
  name: 'Journal of Machine Learning Research'
  short_name: 'J. Mach. Learn. Res'

peer_reviewed: true

# The article is published under the CC-BY 4.0 license.
open_access: true

abstract: >
  This paper studies high-dimensional double sparse linear regression, where the
  regression coefficient exhibits both element-wise and group-wise sparsity. We
  propose an iterative hard thresholding procedure that dynamically updates the
  threshold at each iteration. Matching upper and lower bounds for parameter
  estimation are established, demonstrating the minimax optimality of the proposed
  method. We further introduce a fully adaptive procedure that handles unknown
  sparsity levels and noise levels, and prove that it achieves optimal statistical
  accuracy with fast convergence. The element-wise sparsity level is shown to
  provide a trade-off between classical iterative hard thresholding and group
  iterative hard thresholding. Under suitable beta-min conditions, the proposed
  procedure achieves the oracle estimation rate and almost full recovery of the
  true support at both the element-wise and group-wise levels. Numerical and
  real-data experiments demonstrate the advantages of the proposed method over
  several existing approaches.

math: true

summary: >
  We propose a minimax-optimal and fully adaptive double sparse iterative hard
  thresholding procedure for high-dimensional linear regression, with guarantees
  for optimal estimation, oracle-rate estimation, and almost full support recovery.

tags:
  - Double sparsity
  - Iterative hard thresholding
  - Minimax optimality
  - Adaptive estimation
  - Support recovery
  - Oracle estimation rate
  - Sparse group selection
  - High-dimensional linear regression

# Do not include this paper in Featured Publications for now.
featured: false

# Standard identifiers
hugoblox:
  ids:
    doi: 'https://jmlr.org/papers/v25/23-0653.html'

# Custom links
links:
  - type: pdf
    url: 'A minimax optimal approach to high-dimensional double sparse linear regression.pdf'
  - type: code
    url: 'https://github.com/Yanhang129/ADSIHT'

# Optional featured image.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# No associated project or slides for now.
projects: []
slides: ''
---
---
title: 'Exact Recovery in the Double Sparse Model: Sufficient and Necessary Signal Conditions'

# Authors
# `me` should correspond to content/authors/me/.
authors:
  - 'Shixiang Liu'
  - me
  - 'Yanhang Zhang'
  - 'Jianxin Yin'

# Author notes
author_notes:
  -
  - 'Co-first author'
  -
  - 'Corresponding author'

# Online publication date
# The exact online publication date is not specified in the provided PDF.
date: '2026-01-30T00:00:00Z'

# Schedule page publish date
publishDate: '2026-01-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata
publication:
  name: 'Electronic Journal of Statistics'
  short_name: 'Electron. J. Stat'

peer_reviewed: true

# The article is published under the journal's open-access model.
open_access: true

abstract: >
  The double sparse linear model, which has both group-wise and element-wise
  sparsity in regression coefficients, has attracted considerable attention in
  high-dimensional statistics. This paper establishes the sufficient and necessary
  relationship between exact support recovery and the optimal minimum signal
  conditions in the double sparse model. Specifically, under the proposed signal
  conditions, a two-stage double sparse iterative hard thresholding procedure
  achieves exact support recovery with a suitably chosen threshold parameter.
  Moreover, the procedure maintains asymptotic normality, aligning with the
  ordinary least-squares estimator given the true support and thereby possessing
  oracle properties. Conversely, we prove that no method can achieve exact support
  recovery when these signal conditions are violated. These results fill a critical
  gap in the minimax optimality theory of support recovery for the double sparse
  model. Numerical experiments are provided to support the theoretical findings.

math: true

summary: >
  We establish sufficient and necessary minimum signal conditions for exact support
  recovery in the double sparse linear model, and show that a two-stage double
  sparse iterative hard thresholding procedure achieves minimax-optimal support
  recovery together with oracle asymptotic normality.

tags:
  - Double sparsity
  - Exact support recovery
  - Variable selection
  - Minimax optimality
  - Oracle properties
  - Iterative hard thresholding
  - High-dimensional linear regression

# Do not include this paper in Featured Publications for now.
featured: false

# Standard identifiers
hugoblox:
  ids:
    doi: '10.1214/26-EJS2486'

# Custom links
links:
  - type: pdf
    url: 'Exact recovery in the double sparse model- Sufficient and necessary signal conditions.pdf'


# Optional featured image.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# No associated project or slides for now.
projects: []
slides: ''
---
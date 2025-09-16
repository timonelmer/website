---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Treatment effect estimation with observational network data using machine learning
subtitle: ''
summary: ''
authors:
- Corinne Emmenegger
- Meta-Lina Spohn
- Timon Elmer
- Peter Bühlmann
tags: []
categories: []
date: '2025-04-01'
lastmod: 2025-09-16T18:29:49+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-09-16T16:29:49.190935Z'
publication_types:
- '2'
abstract: Causal inference methods for treatment eﬀect estimation usually assume independent
  units. However, this assumption is often questionable because units may interact,
  resulting in spillover eﬀects between them. We develop augmented inverse probability
  weighting (AIPW) for estimation and inference of the expected average treatment
  eﬀect (EATE) with observational data from a single (social) network with spillover
  eﬀects. In contrast to overall eﬀects such as the global average treatment eﬀect,
  the EATE measures, in expectation and on average over all units, how the outcome
  of a unit is causally aﬀected by its own treatment, marginalizing over the spillover
  eﬀects from other units. We develop cross-ﬁtting theory with plugin machine learning
  to obtain a semiparametric treatment eﬀect estimator that converges at the parametric
  rate and asymptotically follows a Gaussian distribution. The asymptotics are developed
  using the dependency graph rather than the network graph, which makes explicit that
  we allow for spillover eﬀects beyond immediate neighbors in the network. We apply
  our AIPW method to the Swiss StudentLife Study data to investigate the eﬀect of
  hours spent studying on exam performance accounting for the students’ social network.
publication: '*Journal of Causal Inference*'
doi: 10.1515/jci-2023-0082
links:
- name: URL
  url: https://www.degruyterbrill.com/document/doi/10.1515/jci-2023-0082/html
---

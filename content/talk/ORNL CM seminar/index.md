---
title: A Nonlocal Optimization Method for Inverse Design Problem
event: ORNL Computational Mechanics Seminar
event_url: https://www.ornl.gov/event/nonlocal-optimization-method-inverse-design-problems

location: ORNL Computational Mechanics Seminar (virtual event)
address:
  street: Oak Ridge National Laboratory
  city: Oak Ridge
  region: TN
  postcode: '37830'
  country: United States

#summary: An example talk using Academic's Markdown slides feature.
abstract: "Computational inverse design aims to use mathematical optimization algorithms and automate the search for structures and materials. The ultimate goal is to pursue desired performance metrics and generate the best possible design. Much of this progress is made by gradient-based algorithms, which are promising methods to efficiently search the enormous degrees of freedom in high-dimensional design space.  However, existing local-gradient-based optimization approaches lack nonlocal exploration ability required for escaping from local minima in non-convex landscapes. In this work, we propose a nonlocal optimization method with novel directional Gaussian smoothing (DGS) operator to address this challenge. Compared with the local gradient, the DGS gradient allows for a large smoothing radius to capture the global structure of loss landscapes. A deterministic Gauss-Hermite quadrature is used to develop a DGS gradient estimator with higher accuracy than Monte Carlo estimators. The nonlocal optimization method has its advantages on portability and flexibility to naturally incorporate the parameterization, physics simulation (e.g., FEM, CFD, MD, DFT), and objective formulation together to builds up an effective inverse design workflow. The methodology is demonstrated by structural topology optimization problems and nanophotonic device design examples.  Our method shows superior performance with faster convergence compared with classical local gradient approaches in structural and materials design.."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-08-20T14:00:00Z"
date_end: "2020-08-20T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#- internal-project

# Enable math on this page?
math: true
---




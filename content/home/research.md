+++
# A Recent Blog Posts section created with the Pages widget.
# This section displays recent blog posts from `content/post/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

title = "Research Highlights"
subtitle = ""

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "post"

  # Choose how much pages you would like to display (0 = all pages)
  count = 5

  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
    exclude_featured = false

[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"

  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"

  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.1  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""

+++
### **Research Overview**

The overall objective is to develop foundational methods for efficient and robust learning, design and decision-making in complex science and engineering problems.
<p align="center">
<img src="overview3.jpg" alt="drawing" width="650"/>
</p>

<!-- https://davidwells.io/snippets/how-to-align-images-in-markdown -->

---
### Accelerated Inverse Learning with Invertible Neural Networks
We propose a novel approach leveraging recent advances in deep invertible models incorporated with a precise localization via gradient descent for efficiently and accurately solving inverse problems and apply to advanced materials design and discovery.
<p align="center">
<img src="inverse_learning.jpg" alt="drawing" width="800"/>
</p>

---
### A Scalable Directional Gaussian Smoothing (DGS) for Blackbox Optimization
We develop a nonlocal gradient operator, Directional Gaussian smoothing (DGS), to skip small local optima and capture major structures of the loss’s landscape in black-box optimization, specifically high-dimensional cases (e.g., scale to 2000D). Please see our arxiv: https://lnkd.in/eC2dS-v

We have successfully applied DGS for a couple of scientific applications, including advanced materials design, structural optimization, heat conduction model calibration in additive manufacturing. Please check our Materials & Design paper https://lnkd.in/ePypMVt

<p align="center">
<img src="one_page.png" alt="drawing" width="800"/>
</p>

---
###  Benchmarking graph neural networks for materials chemistry
We present a workflow and testing platform, MatDeepLearn[Github repository](https://github.com/vxfung/MatDeepLearn), for quickly and reproducibly assessing and comparing GNNs and other machine learning models, and we use this platform to optimize and evaluate a selection of top performing GNNs on several representative datasets in computational materials chemistry.
<p align="center">
<img src="gnn2.jpg" alt="drawing" width="800"/>
</p>

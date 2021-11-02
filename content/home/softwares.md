+++
# A Projects section created with the Portfolio widget.
# This section displays recent blog posts from `content/software/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Software"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "software"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0

  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"

  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"

  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

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
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++

<img src="uqpy.jpeg" alt="drawing" width="120"/>

### **UQpy**: [Github repository](https://github.com/SURGroup/UQpy)

UQpy (Uncertainty Quantification with python) is an open-source python package for modeling uncertainty in physical and mathematical systems. Capabilities include sampling, statistical inference, surrogate modeling, sensitivity analysis, dimension reduction, reliability and more. The [Shields Uncertainty Research Group](https://sites.google.com/site/jhusurg/) at the Department of Civil and Systems Engineering at Johns Hopkins has developed and maintain UQpy.

**Reference** - Audrey Olivier, Dimitris G. Giovanis, B.S. Aakash, Mohit Chauhan, Lohit Vandanapu, Michael D. Shields. [UQpy: A general purpose Python package and development environment for uncertainty quantification](https://www.sciencedirect.com/science/article/abs/pii/S1877750320305056). In *Journal of Computational Science* **47**, 101204, 2020.

---
### **MatDeepLearn**: [Github repository](https://github.com/vxfung/MatDeepLearn)

MatDeepLearn is a platform for testing and using graph neural networks (GNNs) and other machine learning (ML) models for materials chemistry applications. MatDeepLearn takes in data in the form of atomic structures and their target properties, processes the data into graphs, trains the ML model of choice (optionally with hyperparameter optimization), and provides predictions on unseen data. It allows for different GNNs to be benchmarked on diverse datasets drawn from materials repositories as well as conventional training/prediction tasks.

**Reference** - Victor Fung, Jiaxin Zhang, Eric Juarez, Bobby Sumpter. [Benchmarking graph neural networks for materials chemistry](https://www.nature.com/articles/s41524-021-00554-0). In *npj Computational Materials* **7**, 84, 2021.

---
### **MatDesINNe**: [Github repository](https://github.com/jxzhangjhu/MatDesINNe)

The ability to readily design novel materials with chosen functional properties on-demand represents a next frontier in materials discovery. However, thoroughly and efficiently sampling the entire design space in a computationally tractable manner remains a highly challenging task. To tackle this problem, we propose an inverse design framework (MatDesINNe) utilizing invertible neural networks which can map both forward and reverse processes between the design space and target property.

**Reference** - Victor Fung, **Jiaxin Zhang**, Guoxiang Hu, P Ganesh, Bobby G Sumpter.[Inverse design of two-dimensional materials with invertible neural networks](https://arxiv.org/abs/2106.03013).  In *npj Computational Materials*, 2021 (accepted).


<!-- You can find more information here:

Documentation
Github repository
Paper (Journal of Computational Science) -->

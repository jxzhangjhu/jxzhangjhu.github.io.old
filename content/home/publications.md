+++
# A Recent Publications section created with the Pages widget.
# This section displays recent blog posts from `content/publication/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Publications"
subtitle = "ddsada"

+++

## 📝 Publications

1. ICLR 2021 - [Generalized Energy Based Models](https://arxiv.org/abs/2003.05033) by Michael Arbel et. al.

   <img src="image1.jpg" width = "500" height = "300" alt="图片无法加载时显示的文字" align=center />

   <!-- ### <img src="image/image1.jpg" alt="JAX" height="15px"> &nbsp;JAX Packages -->

   <!-- <img src="assets/normalizing-flow.svg" alt="Normalizing Flow" width="1000"> -->

   >[Github Code](https://github.com/MichaelArbel/GeneralizedEBM)

   <!-- > We introduce the Generalized Energy Based Model (GEBM) for generative modelling. These models combine two trained components: a base distribution (generally an implicit model), which can learn the support of data with low intrinsic dimension in a high dimensional space; and an energy function, to refine the probability mass on the learned support. Both the energy function and base jointly constitute the final model, unlike GANs, which retain only the base distribution (the "generator"). GEBMs are trained by alternating between learning the energy and the base. We show that both training stages are well-defined: the energy is learned by maximising a generalized likelihood, and the resulting energy-based loss provides informative gradients for learning the base. Samples from the posterior on the latent space of the trained model can be obtained via MCMC, thus finding regions in this space that produce better quality samples. Empirically, the GEBM samples on image-generation tasks are of much better quality than those from the learned generator alone, indicating that all else being equal, the GEBM will outperform a GAN of the same complexity. When using normalizing flows as base measures, GEBMs succeed on density modelling tasks, returning comparable performance to direct maximum likelihood of the same networks. -->

2. ICLR 2021 - [No MCMC for me: Amortized sampling for fast and stable training of energy-based models](https://arxiv.org/abs/2010.04230) by Will Grathwohl et al.

   >[Github Code](https://github.com/wgrathwohl/VERA)

3. NeurIPS 2019 - [Implicit Generation and Modeling with Energy-Based Models](https://arxiv.org/abs/1903.08689) by YiLun Du and Igor Mordatch

   >[Github Code](https://github.com/openai/ebm_code_release)

4. ICLR 2020 - [Your Classifier is Secretly an Energy Based Model and You Should Treat it Like One](https://arxiv.org/abs/1912.03263) by Will Grathwohl et al.

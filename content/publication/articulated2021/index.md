---
abstract: We present a method for efficient differentiable simulation of articulated bodies. This enables integration of articulated body dynamics into deep learning frameworks, and gradient-based optimization of neural networks that operate on articulated bodies. We derive the gradients of the forward dynamics using spatial algebra and the adjoint method. Our approach is an order of magnitude faster than autodiff tools. By only saving the initial states throughout the simulation process, our method reduces memory requirements by two orders of magnitude. We demonstrate the utility of efficient differentiable dynamics for articulated bodies in a variety of applications. We show that reinforcement learning with articulated systems can be accelerated using gradients provided by our method. In applications to control and inverse problems, gradient-based optimization enabled by our work accelerates convergence by more than an order of magnitude.
slides: ""
url_pdf: "http://proceedings.mlr.press/v139/qiao21a.html"
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Junbang Liang
  - Vladlen Koltun
  - Ming C. Lin
author_notes: []
publication: International Conference on Machine Learning (ICML 2021)
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: "https://icml.cc/virtual/2021/poster/9049"
title: Efficient Differentiable Simulation of Articulated Bodies
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2021-07-01T00:00:00Z
url_slides: "https://icml.cc/media/icml-2021/Slides/9049.pdf"
publishDate: 2021-07-01T00:00:00Z
url_poster: ""
url_code: "https://github.com/YilingQiao/diffarticulated"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

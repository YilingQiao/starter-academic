---
abstract: Differentiable physics is a powerful approach to learning and control
  problems that involve physical objects and environments. While notable
  progress has been made, the capabilities of differentiable physics solvers
  remain limited. We develop a scalable framework for differentiable physics
  that can support a large number of objects and their interactions. To
  accommodate objects with arbitrary geometry and topology, we adopt meshes as
  our representation and leverage the sparsity of contacts for scalable
  differentiable collision handling. Collisions are resolved in localized
  regions to minimize the number of optimization variables even when the number
  of simulated objects is high. We further accelerate implicit differentiation
  of optimization with nonlinear constraints. Experiments demonstrate that the
  presented framework requires up to two orders of magnitude less memory and
  computation in comparison to recent particle-based methods. We further
  validate the approach on inverse problems and control scenarios, where it
  outperforms derivative-free and model-free baselines by at least an order of
  magnitude.
slides: ""
url_pdf: "https://arxiv.org/abs/2007.02168"
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Junbang Liang
  - Vladlen Koltun
  - Ming C. Lin
author_notes: []
publication: In ICML 2020
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Scalable Differentiable Physics for Learning and Control
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2020-07-01T00:00:00Z
url_slides: ""
publishDate: 2020-07-01T00:00:00Z
url_poster: ""
url_code: "https://github.com/YilingQiao/diffsim"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

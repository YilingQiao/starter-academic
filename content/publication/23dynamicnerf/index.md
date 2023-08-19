---
abstract: Embedding polygonal mesh assets within photorealistic Neural Radience Fields (NeRF) volumes, such that they can be rendered and their dynamics simulated in a physically consistent manner with the NeRF, is under-explored from the system perspective of integrating NeRF into the traditional graphics pipeline. This paper designs a two-way coupling between mesh and NeRF during rendering and simulation. We first review the light transport equations for both mesh and NeRF, then distill them into a straightforward algorithm for updating radiance and throughput along a cast ray with an arbitrary number of bounces. To resolve the discrepancy between the linear color space that the path tracer assumes, versus the sRGB color space that standard NeRF uses, we train NeRF with High Dynamic Range (HDR) images. We also present a strategy to estimate light sources and cast shadows on the NeRF. Finally, we consider how the hybrid surface-volumetric formulation can be efficiently integrated with a high-performance physics simulator that supports cloth, rigid and soft bodies. The full rendering and simulation system can be run on a GPU at interactive rates. We show that a hybrid system approach outperforms alternatives in visual realism for mesh insertion, because it allows realistic light transport from volumetric NeRF media onto surfaces, which affects the appearance of reflective/refractive surfaces and illumination of diffuse surfaces informed by the scene.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Alexander Gao
  - Yiran Xu
  - Yue Feng
  - Jia-Bin Huang
  - Ming C. Lin
author_notes: []
publication: ICCV 2023
summary: ""
url_dataset: ""
url_project: "https://mesh-aware-rf.github.io/"
publication_short: ""
url_source: ""
url_video: ""
title: Dynamic Mesh-Aware Radiance Fields
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2023-08-01T00:00:00Z
url_slides: ""
publishDate: 2023-08-01T00:00:00Z
url_poster: ""
url_code: "https://mesh-aware-rf.github.io/"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

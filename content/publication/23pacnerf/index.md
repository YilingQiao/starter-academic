---
abstract: Existing approaches to system identification (estimating the physical parameters of an object) from videos assume known object geometries. This precludes their applicability in a vast majority of scenes where object geometries are complex or unknown. In this work, we aim to identify parameters characterizing a physical system from a set of multi-view videos without any assumption on object geometry or topology. To this end, we propose "Physics Augmented Continuum Neural Radiance Fields" (PAC-NeRF), to estimate both the unknown geometry and physical parameters of highly dynamic objects from multi-view videos. We design PAC-NeRF to only ever produce physically plausible states by enforcing the neural radiance field to follow the conservation laws of continuum mechanics. For this, we design a hybrid Eulerian-Lagrangian representation of the neural radiance field, i.e., we use the Eulerian grid representation for NeRF density and color fields, while advecting the neural radiance fields via Lagrangian particles. This hybrid Eulerian-Lagrangian representation seamlessly blends efficient neural rendering with the material point method (MPM) for robust differentiable physics simulation. We validate the effectiveness of our proposed framework on geometry and physical parameter estimation over a vast range of materials, including elastic bodies, plasticine, sand, Newtonian and non-Newtonian fluids, and demonstrate significant performance gain on most tasks.
slides: ""
url_pdf: "https://openreview.net/forum?id=tVkrbkz42vc"
publication_types:
  - "1"
authors:
  - Xuan Li
  - Yi-Ling Qiao
  - Peter Yichen Chen
  - Krishna Murthy Jatavallabhula
  - Ming Lin
  - Chenfanfu Jiang
  - Chuang Gan
author_notes: []
publication: ICLR 2023
summary: ""
url_dataset: "https://drive.google.com/drive/u/2/folders/1KuIq7rrAANzTrj4PzYYdwEaDZVPY6lO3"
url_project: "https://sites.google.com/view/PAC-NeRF"
publication_short: ""
url_source: ""
url_video: ""
title: PAC-NeRF - Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2023-02-01T00:00:00Z
url_slides: ""
publishDate: 2022-02-01T00:00:00Z
url_poster: ""
url_code: "https://github.com/xuan-li/PAC-NeRF"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

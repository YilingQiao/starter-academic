---
abstract: Various heuristic objectives for modeling hand-object interaction have been proposed in past work. However, due to the lack of a cohesive framework, these objectives often possess a narrow scope of applicability and are limited by their efficiency or accuracy. In this paper, we propose HandyPriors, a unified and general pipeline for pose estimation in human-object interaction scenes by leveraging recent advances in differentiable physics and rendering. Our approach employs rendering priors to align with input images and segmentation masks along with physics priors to mitigate penetration and relative-sliding across frames. Furthermore, we present two alternatives for hand and object pose estimation. The optimization-based pose estimation achieves higher accuracy, while the filtering-based tracking, which utilizes the differentiable priors as dynamics and observation models, executes faster. We demonstrate that HandyPriors attains comparable or superior results in the pose estimation task, and that the differentiable physics module can predict contact information for pose refinement. We also show that our approach generalizes to perception tasks, including robotic hand manipulation and human-object pose estimation in the wild. 
slides: ""
url_pdf: "https://arxiv.org/abs/2311.16552"
publication_types:
  - "1"
authors:
  - Shutong Zhang
  - Yi-Ling Qiao
  - Guanglei Zhu
  - Eric Heiden
  - Dylan Turpin
  - Jingzhou Liu
  - Ming Lin
  - Miles Macklin
  - Animesh Garg
author_notes: []
publication: ICRA 2024
summary: ""
url_dataset: ""
url_project: "https://handypriors.github.io/"
publication_short: ""
url_source: ""
url_video: ""
title: HandyPriors - Physically Consistent Perception of Hand-Object Interactions with Differentiable Priors
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2024-02-01T00:00:00Z
url_slides: ""
publishDate: 2024-02-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

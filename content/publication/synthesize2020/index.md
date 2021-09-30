---
abstract: Synthesizing realistic 3D mesh deformation sequences is a challenging but important task in computer animation. To achieve this, researchers have long been focusing on shape analysis to develop new interpolation and extrapolation techniques. However, such techniques have limited learning capabilities and therefore often produce unrealistic deformation. Although there are already networks defined on individual meshes, deep architectures that operate directly on mesh sequences with temporal information remain unexplored due to the following major barriers, irregular mesh connectivity, rich temporal information, and varied deformation. To address these issues, we utilize convolutional neural networks defined on triangular meshes along with a shape deformation representation to extract useful features, followed by long short-term memory (LSTM) that iteratively processes the features. To fully respect the bidirectional nature of actions, we propose a new share-weight bidirectional scheme to better synthesize deformations. An extensive evaluation shows that our approach outperforms existing methods in sequence generation, both qualitatively and quantitatively.
slides: ""
url_pdf: "https://ieeexplore.ieee.org/document/9217964"
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Yu-Kun Lai
  - Hongbo Fu
  - Lin Gao
author_notes: []
publication: IEEE Transactions on Visualization and Computer Graphics
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Synthesizing Mesh Deformation Sequences with Bidirectional LSTM
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2019-10-01T00:00:00Z
url_slides: ""
publishDate: 2019-10-01T00:00:00Z
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

---
abstract: 3D models are commonly used in computer vision and graphics. With the wider availability of mesh data, an efficient and intrinsic deep learning approach to processing 3D meshes is in great need. Unlike images, 3D meshes have irregular connectivity, requiring careful design to capture relations in the data. To utilize the topology information while staying robust under different triangulations, we propose to encode mesh connectivity using Laplacian spectral analysis, along with mesh feature aggregation blocks (MFABs) that can split the surface domain into local pooling patches and aggregate global information amongst them. We build a mesh hierarchy from fine to coarse using Laplacian spectral clustering, which is flexible under isometric transformations. Inside the MFABs there are pooling layers to collect local information and multi-layer perceptrons to compute vertex features of increasing complexity. To obtain the relationships among different clusters, we introduce a Correlation Net to compute a correlation matrix, which can aggregate the features globally by matrix multiplication with cluster features. Our network architecture is flexible enough to be used on meshes with different numbers of vertices. We conduct several experiments including shape segmentation and classification, and our method outperforms state-of-the-art algorithms for these tasks on the ShapeNet and COSEG datasets. 
slides: ""
url_pdf: "https://www.computer.org/csdl/journal/tg/5555/01/09159927/1m3m77L2v3a"
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Lin Gao
  - Jie Yang
  - Paul L. Rosin
  - Yu-Kun Lai
  - Xilin Chen
author_notes: []
publication: In TVCG 2020
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Learning on 3D Meshes with Laplacian Encoding and Pooling
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: "https://github.com/YilingQiao/lapcluster.git"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

---
abstract: Reflectional symmetry is a ubiquitous pattern in nature. Previous works usually solve this problem by voting or sampling, suffering from high computational cost and randomness. In this paper, we propose a learning-based approach to intrinsic reflectional symmetry detection. Instead of directly finding symmetric point pairs, we parametrize this self-isometry using a functional map matrix, which can be easily computed given the signs of Laplacian eigenfunctions under the symmetric mapping. Therefore, we manually label the eigenfunction signs for a variety of shapes and train a novel neural network to predict the sign of each eigenfunction under symmetry. Our network aims at learning the global property of functions and consequently converts the problem defined on the manifold to the functional domain. By disentangling the prediction of the matrix into separated bases, our method generalizes well to new shapes and is invariant under perturbation of eigenfunctions. Through extensive experiments, we demonstrate the robustness of our method in challenging cases, including different topology and incomplete shapes with holes. By avoiding random sampling, our learning-based algorithm is over 20 times faster than state-of-the-art methods, and meanwhile, is more robust, achieving higher correspondence accuracy in commonly used metrics.
slides: ""
url_pdf: "https://ieeexplore.ieee.org/document/9770416"
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Lin Gao
  - Shu-Zhi Liu
  - Ligang Liu
  - Yu-Kun Lai
  - Xilin Chen
author_notes: []
publication: IEEE Transactions on Visualization and Computer Graphics
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Learning-based Intrinsic Reflectional Symmetry Detection
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2020-05-01T00:00:00Z
url_slides: ""
publishDate: 2020-05-01T00:00:00Z
url_poster: ""
url_code: "https://github.com/YilingQiao/intrinsicSym"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

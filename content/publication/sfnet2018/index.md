---
abstract: With the rapid development of depth sensors, RGB-D data has become much more accessible. Scene flow is one of the fundamental ways to understand the dynamic content in RGB-D image sequences. Traditional approaches estimate scene flow using registration and smoothness or local rigidity priors, which is slow and prone to errors when the priors are not fully satisfied. To address such challenges, learning based methods provide an attractive alternative. However, trivially applying CNN-based optical flow estimation methods does not produce satisfactory results. How to use deep learning to improve the estimation of scene flow from RGB-D images remains unexplored. In this work, we propose a novel learning based framework to estimate scene flow, which takes both brightness and scene flow losses. Given a pair of RGB-D images, the brightness loss is used to measure the disparity between the first RGB-D image and the deformed second RGB-D image using the scene flow, and the scene flow loss is used to learn from the ground truth of scene flow. We build a convolutional neural network to simultaneously optimize both losses. Extensive experiments on both synthetic and real-world datasets show that our method is significantly faster than existing methods and outperforms stateof-the-art real-time methods in accuracy.
slides: ""
url_pdf: "http://bmvc2018.org/contents/papers/1095.pdf"
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao
  - Lin Gao
  - Yu-Kun Lai
  - Fang-Lue Zhang
  - Ming-Ze Yuan
  - Shihong Xia
author_notes: []
publication: The British Machine Vision Conference (BMVC 2018) 
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: SF-Net Learning Scene Flow from RGB-D Images with CNNs
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2018-10-01T00:00:00Z
url_slides: ""
publishDate: 2018-10-01T00:00:00Z
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

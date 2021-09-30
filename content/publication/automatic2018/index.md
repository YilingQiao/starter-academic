---
abstract: Transferring deformation from a source shape to a target shape is a very useful technique in computer graphics. State-of-the-art deformation transfer methods require either point-wise correspondences between source and target shapes, or pairs of deformed source and target shapes with corresponding deformations. However, in most cases, such correspondences are not available and cannot be reliably established using an automatic algorithm. Therefore, substantial user effort is needed to label the correspondences or to obtain and specify such shape sets. In this work, we propose a novel approach to automatic deformation transfer between two unpaired shape sets without correspondences. 3D deformation is represented in a highdimensional space. To obtain a more compact and effective representation, two convolutional variational autoencoders are learned to encode source and target shapes to their latent spaces. We exploit a Generative Adversarial Network (GAN) to map deformed source shapes to deformed target shapes, both in the latent spaces, which ensures the obtained shapes from the mapping are indistinguishable from the target shapes. This is still an under-constrained problem, so we further utilize a reverse mapping from target shapes to source shapes and incorporate cycle consistency loss, i.e. applying both mappings should reverse to the input shape. This VAE-Cycle GAN (VC-GAN) architecture is used to build a reliable mapping between shape spaces. Finally, a similarity constraint is employed to ensure the mapping is consistent with visual similarity, achieved by learning a similarity neural network that takes the embedding vectors from the source and target latent spaces and predicts the light field distance between the corresponding shapes. Experimental results show that our fully automatic method is able to obtain high-quality deformation transfer results with unpaired data sets, comparable or better than existing methods where strict correspondences are required.
slides: ""
url_pdf: "https://dl.acm.org/doi/10.1145/3272127.3275028"
publication_types:
  - "1"
authors:
  - Lin Gao
  - Jie Yang
  - Yi-Ling Qiao
  - Yu-Kun Lai
  - Paul L. Rosin
  - Weiwei Xu
  - Shihong Xia
author_notes: []
publication: In SIGGRAPH Asia 2018
summary: ""
url_dataset: ""
url_project: "http://geometrylearning.com/ausdt/"
publication_short: ""
url_source: ""
url_video: "https://youtu.be/IqOZ0FwC8vQ"
title: Automatic Unpaired Shape Deformation Transfer
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2018-12-01T00:00:00Z
url_slides: ""
publishDate: 2018-12-01T00:00:00Z
url_poster: ""
url_code: "https://github.com/gaolinorange/Automatic-Unpaired-Shape-Deformation-Transfer"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

---
abstract: We present a method for learning geometry and physics parameters of a dynamic scene requiring only a monocular RGB video. Our approach uses a hybrid representation of neural fields and hexahedra mesh, enabling objects in the scene to be interactively edited, and synthesized from novel views. To decouple the learning of underlying scene geometry from dynamic motion, we learn a time-invariant signed distance function which serves as a reference frame, as well as an associated deformation field that is conditioned on each time step. We design a two-way conversion between the neural field and corresponding mesh representation, which allows us to bridge the neural representation with a differentiable physics simulator, and therefore estimate physics parameters from the source video, by minimizing a cycle consistency loss. This flexible, hybrid representation also allows a user to easily edit 3D objects from the source video by directly editing the recovered hexahedra mesh, and propagating this operation back to the neural field. In Experiments, our method achieves higher-quality mesh and video reconstruction of dynamic scenes compared to other competitive Neural Field methods.  Finally, we provide extensive examples which demonstrate our method’s ability to extract useful 3D representations of dynamic scenes from videos captured with consumer-grade cameras.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Yi-Ling Qiao1
  - Alexander Gao1
  - Ming C. Lin
author_notes: []
publication: Accepted by NeurIPS 2022, Coming Soon
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: NeuPhysics - Editable Neural Geometry and Physics from Monocular Videos
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2022-09-15T00:00:00Z
url_slides: ""
publishDate: 2022-09-15T00:00:00Z
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

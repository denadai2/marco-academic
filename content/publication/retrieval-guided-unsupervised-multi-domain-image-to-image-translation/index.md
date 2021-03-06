---
abstract: Image to image translation aims to learn a mapping that transforms an
  image from one visual domain to another. Recent works assume that images
  descriptors can be disentangled into a domain-invariant content representation
  and a domain-specific style representation. Thus, translation models seek to
  preserve the content of source images while changing the style to a target
  visual domain. However, synthesizing new images is extremely challenging
  especially in multi-domain translations, as the network has to compose content
  and style to generate reliable and diverse images in multiple domains. In this
  paper we propose the use of an image retrieval system to assist the
  image-to-image translation task. First, we train an image-to-image translation
  model to map images to multiple domains. Then, we train an image retrieval
  model using real and generated images to find images similar to a query one in
  content but in a different domain. Finally, we exploit the image retrieval
  system to fine-tune the image-to-image translation model and generate higher
  quality images. Our experiments show the effectiveness of the proposed
  solution and highlight the contribution of the retrieval network, which can
  benefit from additional unlabeled data and help image-to-image translation
  models in the presence of scarce data.
draft: false
url_pdf: https://arxiv.org/pdf/2008.04991.pdf
title: Retrieval guided unsupervised multi-domain image to image translation
publication_types:
  - "1"
authors:
  - R. Gomez
  - Y. Liu
  - M. De Nadai
  - D. Karatzas
  - B. Lepri
  - N. Sebe
publication: ACM MM 2019
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-12-10T10:02:18.400Z
url_code: https://github.com/yhlleo/RG-UNIT
---

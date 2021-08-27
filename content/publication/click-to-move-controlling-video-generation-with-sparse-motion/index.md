---
title: "Click to Move: Controlling Video Generation with Sparse Motion"
publication_types:
  - "1"
authors:
  - Pierfrancesco Ardino
  - Marco De Nadai
  - Bruno Lepri
  - Elisa Ricci
  - Stéphane Lathuilière
publication: ICCV
abstract: This paper introduces Click to Move (C2M), a novel framework for video
  generation where the user can control the motion of the synthesized video
  through mouse clicks specifying simple object trajectories of the key objects
  in the scene. Our model receives as input an initial frame, its corresponding
  segmentation map and the sparse motion vectors encoding the input provided by
  the user. It outputs a plausible video sequence starting from the given frame
  and with a motion that is consistent with user input. Notably, our proposed
  deep architecture incorporates a Graph Convolution Network (GCN) modelling the
  movements of all the objects in the scene in a holistic manner and effectively
  combining the sparse user motion information and image features. Experimental
  results show that C2M outperforms existing methods on two publicly available
  datasets, thus demonstrating the effectiveness of our GCN framework at
  modelling object interactions.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-27T14:48:23.959Z
url_code: "https://github.com/PierfrancescoArdino/C2M"
url_pdf: "https://arxiv.org/pdf/2108.08815.pdf"
---

---
title: "Tora: Trajectory-oriented Diffusion Transformer for Video Generation"
publication_types:
  - paper
authors:
  - Zhenghao Zhang
  - Junchao Liao
  - Menghao Li
  - Long Qin
  - Weizhi Wang
author_notes:
  - Equal Contribution; Alibaba Group
  - Equal Contribution; Alibaba Group
  - Alibaba Group
  - Alibaba Group
  - Alibaba Group
publication: arXiv
abstract: Recent advancements in Diffusion Transformer (DiT) have demonstrated
  remarkable proficiency in producing high-quality video content. Nonetheless,
  the potential of transformer-based diffusion models for effectively generating
  videos with controllable motion remains an area of limited exploration. This
  paper introduces Tora, the first trajectory-oriented DiT framework that
  integrates textual, visual, and trajectory conditions concurrently for video
  generation. Specifically, Tora consists of a Trajectory Extractor (TE), a
  Spatial-Temporal DiT, and a Motion-guidance Fuser (MGF). The TE encodes
  arbitrary trajectories into hierarchical spacetime motion patches with a 3D
  video compression network. The MGF integrates the motion patches into the DiT
  blocks to generate consistent videos following trajectories. Our design aligns
  seamlessly with DiT's scalability, allowing precise control of video content's
  dynamics with diverse durations, aspect ratios, and resolutions. Extensive
  experiments demonstrate Tora's excellence in achieving high motion fidelity,
  while also meticulously simulating the movement of the physical world.
draft: false
featured: true
image:
  filename: panda_tora.png
  focal_point: Smart
  preview_only: false
summary: ""
date: 2024-07-31T15:59:00.000Z
---
paper: https://arxiv.org/abs/2407.21705

project page: https://ali-videoai.github.io/tora_video/

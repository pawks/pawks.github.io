---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "ARC: Warp-level Adaptive Atomic Reduction in GPUs to Accelerate Differentiable Rendering"
subtitle: ''
summary: ''
authors:
- Sankeerth Durvasula\*
- Adrian Zhao\*
- Fan Chen
- Ruofan Liang
- **Pawan Kumar Sanjaya**
- Yushi Guan
- Christina Giannoula
- Nandita Vijaykumar
tags: []
categories:
date: '2025-03-30'
lastmod: 2022-10-01T19:24:50+05:30
featured: false
draft: false
links:
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-03-30'
publication_types:
- '1'
abstract: "Differentiable rendering is widely used in emerging applications that represent any 3D scene as a model trained using gradient descent from 2D images. Recent works (e.g., 3D Gaussian Splatting) use rasterization to enable rendering photo-realistic imagery at high speeds from these learned 3D models. These rasterization-based differentiable rendering methods have been demonstrated to be very promising, providing state-of-art quality for various important tasks. However, training a model to represent a scene is still time-consuming even on powerful GPUs. In this work, we observe that the gradient computation step during model training is a significant bottleneck due to the large number of atomic operations. These atomics overwhelm the atomic units in the L2 cache of GPUs, causing long stalls.
To address this, we leverage the observations that during gradient computation: (1) for most warps, all threads atomically update the same memory locations; and (2) warps generate varying amount of atomic traffic. We propose ARC, a primitive that accelerates atomic operations based on two key ideas: First, we enable warp-level reduction at the GPU cores using registers to leverage the locality in intra-warp atomic updates. Second, we distribute atomic computation between the cores and the L2 atomic units to increase the throughput of atomic computation. We propose two implementations of ARC: ARC-HW, a hardware-based approach and ARC-SW, a software-only approach. We demonstrate significant speedups with ARC of 2.6× on average (up to 5.7×) for widely used differentiable rendering workloads. "
publication: '*ASPLOS*'
url_pdf: https://dl.acm.org/doi/10.1145/3669940.3707238  
<!-- url_slides: https://carrv.github.io/2022/slides/CARRV2022_slides_2_Kumar.pdf --> 
---

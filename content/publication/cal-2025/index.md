---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "DPWatch: a Framework for Hardware-Based Differential Privacy Guarantees"
subtitle: ''
summary: ''
authors:
- **Pawan Kumar Sanjaya**
- Christina Giannoula
- Ian Colbert
- Ihab Amer
- Mehdi Saeedi 
- Gabor Sines
- Nandita Vijaykumar
tags: []
categories:
date: '2025-03-01'
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
publishDate: '2025-03-01'
publication_types:
- '2'
abstract: Differential privacy (DP) and federated learning (FL) have emerged as important privacy-preserving approaches when using sensitive data to train machine learning models. FL ensures that raw sensitive data does not leave the users' devices by training the model in a distributed manner. DP ensures that the model does not leak any information about an individual by clipping and adding noise to the gradients. However, reallife deployments of such algorithms assume that the third-party application implementing DP-based FL is trusted, and is thus given access to sensitive data on the data owner's device/server. In this work, we propose DPWatch, a hardware-based framework for ML accelerators that enforces guarantees that a third party application cannot leak sensitive user data used for training and ensures that the gradients are appropriately noised before leaving the device. We evaluate DPWatch on two accelerators and demonstrate small area and performance overheads.
publication: '*IEEE Computer Architecture Letters*'
url_pdf: https://doi.ieeecomputersociety.org/10.1109/LCA.2025.3547262 
<!-- url_slides: https://carrv.github.io/2022/slides/CARRV2022_slides_2_Kumar.pdf --> 
---

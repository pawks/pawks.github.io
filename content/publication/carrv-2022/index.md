---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Automating Generation and Maintenance of a High-Quality Architectural Test
  Suite for RISC-V
subtitle: ''
summary: ''
authors:
- S Pawan Kumar
- Shrreya Singh
- Neel Gala
- Allen Baum
tags: []
categories: 
- RISC-V
- Architectural Compatibility Testing
date: '2022-06-01'
lastmod: 2022-10-01T19:24:50+05:30
featured: false
draft: false
links:
  - name: riscv-isac
    url: /project/riscv-isac
  - name: riscv-isac
    url: /project/riscv-ctg

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

publishDate: '2022-10-01T13:54:50.715773Z'
publication_types:
- '1'
abstract: Considering the modularity of RISC-V, proving the compatibility of implementations
  against the ISA has become critical to prevent fragmentation and ensure its success.
  The test suite needed to achieve this should cater to all legal enumerations of
  the ISA and determine with high confidence, the ISA compatibility of the target.
  This paper proposes open-source tools(RISCV-ISAC and RISCV- CTG) which significantly
  automate building and maintenance of a high quality and scalable test suite. RISCV-ISAC
  collects coverage from execution logs and checks for data propagation to signature.
  RISCV-CTG is a coverage driven test generator, which generates minimal tests for
  maximum coverage with RISCV-ISAC.
publication: '*Sixth Workshop on Computer Architecture Research with RISC-V, Co-located
  with ISCA*'
url_pdf: https://carrv.github.io/2022/papers/CARRV2022_paper_2_Kumar.pdf
url_slides: https://carrv.github.io/2022/slides/CARRV2022_slides_2_Kumar.pdf 
---

---
title: "RISCV-CTG: RISC-V Coverage Driven Test Generator"
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/riscv-software-src/riscv-ctg/
  - icon: book
    icon_pack: fas
    name: Docs
    url: https://riscv-ctg.readthedocs.io/

summary: Due to the highly permissive nature of the RISC-V ISA, manually writing high quality architectural
    compatibility tests is infeasible. This tool models tests as a set of constraint satisfcation 
    problems(CSP) in finite domain using the architectural fields as variables and coverage goals 
    as constraints. The solutions to these problems are found using CSP solvers and converted 
    into RISC-V assembly programs using handwritten templates.

tags:
  - RISC-V
  - Architectural Compatibility Testing
  - Test Generator
# date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart


url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Due to the highly permissive nature of the RISC-V ISA, manually writing high quality architectural
compatibility tests is infeasible. This tool models tests as a set of constraint satisfcation 
problems using the following:

- architectural fields defined by the ISA (as variables)

- coverage defined by [RISCV-ISAC]({{< relref "/project/riscv-isac" >}}) (as constraints) 

The solutions to these problems are found using CSP solvers and converted into RISC-V assembly
programs using handwritten templates.


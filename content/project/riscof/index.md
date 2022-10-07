---
title: "RISCOF: RISC-V Compatibility Testing Framework"
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/riscv-software-src/riscof/
  - icon: book
    icon_pack: fas
    name: Docs
    url: https://riscof.readthedocs.io/

summary:
    A framework to filter, configure, run and validate architectural tests on a given RISC-V
    implementation based on the configuration.

tags:
  - RISC-V
  - Architectural Compatibility Testing
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
The Architectural Compatibility Tests are a suite of tests which are intended to test whether the
implementation conforms to the RISC-V specification. The RISC-V ISA has multiple configuration
behaviors/options across the specification where the choice is to be made by the implementor. 
Hence, it is extremely important to test whether the choices made still conform to the specification
while maintaining compatibility of the software which do not leverage those options. This strategy
reduces the risk of fragmentation of the eco-system and establishes compatibility of multiple RISC-V
implementations.

The implementations are integrated with the framework using python plugins. This enables scalability
and lowers the barriers of entry. The plugin is responsible for providing the configuration of the
implementation(as per the format specified by [riscv-config]({{< relref "/project/riscv-config" >}})) and running the tests on it to 
generate signatures. The framework is responsible for valiating the configuration, selecting and
configuring the tests and comparing signatures against a golden model([SAIL RISC-V Model](https://github.com/riscv/sail-riscv)). 
The framework also generates html reports which list various statistics along with the result of
signature matching.

Note: An implementation here refers to an RTL, simulator or physical chip. Any of the above can be
used as long as it supports bare metal execution and signature dumping.

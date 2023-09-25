---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 25
active: false

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: RTL Design Engineer
    company: InCore Semiconductors Pvt. Ltd. 
    company_url: 'https://incoresemi.com/'
    company_logo: 
    location:
    date_start: '2021-06-01'
    date_end: '2023-08-01'
    description: |2-

        * Design and implement micro-architectural improvements for a 6stage in-order RISC-V Cores.
        * Design Multi-core RISC-V processor with hierarchial and coherent Caches.
        * Conceptualised and directed implementation of various features for key tools in the RISC‐V Architectural Testing ecosystem for testing various extensions in the specification. 

  - title: RTL Design Intern
    company: InCore Semiconductors Pvt. Ltd. 
    company_url: 'https://incoresemi.com/'
    company_logo: 
    location:
    date_end: '2021-05-30'
    date_start: '2020-12-01'
    description: |2-
        * Explore automatic generation of coherent cache subsystem from SSP.
  - title: Research Intern
    company: SHAKTI initiative, RISE Labs 
    company_url: ''
    company_logo: 
    location: IIT Madras
    date_start: '2020-05-01'
    date_end: '2020-10-30'
    description: |2-
        * Designed and implemented a secure boot solution for Shakti RISC‐V cores. The solution consisted of a signing tool, framework and run‐time libraries to be integrated with the firmware.
        * Designed extensions to support higher level API calls and provide better security guarantees.
        * Proposed a scheme to support trusted execution environments using a co‐processor by analysing various solutions such as Intel SGX, Sanctum and Keystone.

  - title: Summer Research Intern
    company: SHAKTI initiative, RISE Labs 
    company_url: ''
    company_logo: 
    location: IIT Madras
    date_start: '2019-05-01'
    date_end: '2019-07-30'
    description: |2-
        * Evaluated various methods to generate bluespec code for SOCs based on a given configuration. Implemented a tool which could automatically generate SOCs with optimal address mappings for heterogeneous and hierarchical busses.
        * Identified key csr configuration options in the RISC‐V ISA and designed a scheme to describe the custom behaviours. Implemented an open‐source tool([riscv-config]({{< relref "/project/riscv-config" >}})) in python to validate descriptions and verify legality of behaviours.
        * Evaluated various strategies for RISC‐V architectural compliance testing and implemented a dynamic, scalable and easy‐to‐use open‐source framework([riscof]({{< relref "/project/riscof" >}})) based on the best strategy.

  - title: Research Intern
    company: SHAKTI initiative, RISE Labs
    company_url: ''
    company_logo: 
    location: IIT Madras
    date_start: '2018-05-01'
    date_end: '2018-07-30'
    description: |2- 
        * Designed and developed a pipelined and multi‐cycle SHA 256 accelerator in Bluespec System Verilog.
        * Optimised the design for area, delay and power on the Xilinx Artix‐7 FPGA.
        * Verified the correctness using NIST test vectors

design:
  columns: '1'
---

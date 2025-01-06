---
layout: post
title: "Advanced Out-of-Order RISC-V Processor"
date: 2024-12-12
excerpt: "Developed a high-performance RISC-V processor featuring advanced pipelining, branch prediction, and caching mechanisms."
tags: [RISC-V, SystemVerilog, Processor Design]
comments: true
project: true
---

### Advanced Out-of-Order RISC-V Processor
-Developed a high-performance, pipelined processor in SystemVerilog, implementing the RISC-V ISA with features like R10K-style register renaming, N-way superscalar execution, early tag broadcasting, and GShare-based branch prediction.
-Designed advanced memory subsystems, including mechanisms for instruction prefetching, non-blocking instruction and data caches, as well as a victim cache for improved cache performance.
-Engineered a load-store queue with forwarding to optimize memory operations and minimize pipeline stalls.
-Validated using a suite of benchmark programs, including Neural Networks, sorting algorithms etc with an average CPI of 1.8
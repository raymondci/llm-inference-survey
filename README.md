# LLM Inference Survey

A systems-oriented survey of Large Language Model inference optimization, spanning model architectures, compiler infrastructures, runtime systems, GPU microarchitecture, and modern serving frameworks.

> **Status:** Work in Progress

---

## Overview

This project started as a systematic study of **LLM inference optimization**, with the initial goal of understanding how modern serving systems improve latency, throughput, memory efficiency, and hardware utilization.

As the investigation progressed, it became clear that efficient LLM inference cannot be understood from algorithms alone. Many optimizations emerge from interactions across multiple abstraction layers, including model architecture, compiler infrastructure, runtime scheduling, GPU microarchitecture, instruction set design, and hardware accelerators.

The scope of this survey therefore gradually expanded into a **cross-layer systems perspective**, integrating insights from research papers, open-source frameworks, industrial documentation, and hardware architecture.

Unlike surveys organized purely by algorithms, this work attempts to connect **model design, compiler infrastructures, runtime systems, GPU architectures, and hardware accelerators** into a unified optimization framework for modern LLM serving.

---

## Current Topics

The survey currently covers:

- Transformer architecture and computational characteristics
- GPU hardware accelerators and execution models
- Instruction set architectures (SIMD, Tensor Core, Arm SVE/SME)
- Model scaling trends and inference challenges
- Evolution of LLM architectures
- Data-level optimization
- Model-level optimization
- System-level optimization
- Runtime memory management (KV Cache, PagedAttention)
- Parallel execution and scheduling
- Kernel optimization (CUDA Graphs, kernel fusion, Triton)
- FlashAttention and efficient attention kernels
- Compiler infrastructures (TVM, MLIR)
- Modern serving frameworks (vLLM, TensorRT-LLM, SGLang, llama.cpp)
- Benchmark metrics (Response Latency, TTFT, TPOT, ITL, TPS, GPU utilization, memory efficiency)
- Future research directions

---

## Goals

Rather than providing a static literature review, this repository aims to become a living survey that continuously tracks the evolution of LLM inference systems.

Future updates will include:

- Newly published research papers
- Emerging serving frameworks
- GPU architecture evolution
- Compiler and runtime optimizations
- Benchmark methodologies
- Hardware acceleration techniques
- Updated figures and system diagrams
- Improved citations and references
- More comprehensive comparisons and taxonomies

---

## Roadmap

- [ ] Continue improving literature coverage
- [ ] Expand benchmark comparisons
- [ ] Refine system taxonomies
- [ ] Improve figures and diagrams
- [ ] Verify and standardize citations
- [ ] Track newly released LLM serving technologies
- [ ] Expand compiler and runtime optimization coverage
- [ ] Add cross-framework implementation comparisons
- [ ] Cover next-generation GPU architectures and hardware accelerators
- [ ] Maintain the survey as a continuously updated reference

---

## Repository Structure

```text
.
├── README.md
├── pdf/
│   └── llm_survey.pdf
└── LICENSE.md
```

---

## Vision

Efficient LLM inference is no longer a problem confined to model architecture alone. Future progress increasingly depends on **cross-layer optimization**, spanning algorithms, compiler infrastructures, runtime systems, GPU microarchitecture, memory hierarchy, and specialized hardware accelerators.

This repository aims to document that evolution and provide a continuously updated systems-oriented reference for the LLM inference community.

---

## License

This report is licensed under the
[Creative Commons Attribution 4.0 International License](./LICENSE.md).

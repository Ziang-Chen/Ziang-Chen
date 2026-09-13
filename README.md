# Ziang Chen

I have ten years of experience in deep learning. My research spans deep learning,
large language models, autonomous driving, and robotics. I also work on AI
infrastructure, high-performance computing, and formal verification, with
technical experience in GPU operators and kernels, inference frameworks, and
GPU cluster systems.

## LLMs and AI infrastructure

I work across the execution stack, from the operators used by a model to GPU
kernels, inference frameworks, and the systems that run them.

- **GPU operators and kernels:** CUDA programming and warp-level execution,
  with a focus on high-performance computation for machine learning workloads.
- **Inference frameworks:** SGLang and vLLM, including their execution paths
  and interaction with GPU kernels.
- **Inference memory:** KV cache management and its role in LLM inference.
- **GPU systems:** cluster architecture spanning kernels, runtimes, and services.

## Research

My research directions include deep learning and large language models, with
experience in autonomous driving and robotics. Alongside this work, I study
the computing infrastructure that supports AI workloads and methods for
modeling and verifying concurrent systems.

- **Deep learning and LLMs:** model research and efficient inference.
- **Autonomous driving and robotics:** deep learning research in autonomous systems.
- **AI infrastructure and HPC:** GPU computation, operators, inference frameworks,
  and cluster systems.
- **Formal verification:** concurrency, causal dependencies, and progress
  properties, including deadlock and livelock analysis.

From 2022 to 2025, my research at Eindhoven University of Technology focused on
high-performance computing. It covered GPU programming with CUDA warp-level
features, GPU cluster architecture from kernels to services, and formal
verification of large-scale distributed systems, including deadlock and livelock
analysis.

My earlier work explored complex systems through mean-field models and
differential equations, with a focus on numerical stability.

## DTESSL: modeling concurrent execution

[DTESSL](https://github.com/Ziang-Chen/DTESSL) is a separate research direction
in formal modeling and verification. It is a discrete-time event system modeling language
for describing typed state, concurrent transitions, causal dependencies, and
temporal properties.

- Concurrent inputs read one state snapshot and commit as an atomic round.
- Causal history records dependencies between transition occurrences.
- Temporal claims are checked over execution states and property monitors.
- Captured typed inputs can be replayed to reconstruct logical execution.

The current implementation is a standalone C++20 library and CLI with a built-in
model checker. Its Embedding representation provides a basis for exploring
GPU-accelerated verification; the current release uses a C++ reference interpreter.
External effects are represented as action plans and executed by the host system.

[English documentation](https://github.com/Ziang-Chen/DTESSL/blob/main/README.en.md)
· [中文文档](https://github.com/Ziang-Chen/DTESSL/blob/main/README.md)
· [Design and research references](https://github.com/Ziang-Chen/DTESSL/blob/main/docs/REFERENCES.md)

## Other projects

- [Lisp](https://github.com/Ziang-Chen/Lisp) — a Lisp embedded in Python, started
  during my undergraduate studies.
- [browser](https://github.com/Ziang-Chen/browser) — a browser-based environment
  exploring a controllable workspace for agent-assisted development.

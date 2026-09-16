# Ziang Chen

Hi there, I'm Ziang. For Work and Research, I have ten years of experience in deep learning, with research spanning
generative models, large language models, autonomous driving, and robotics.
My work extends across the AI software stack, from algorithms to
high-performance computing infrastructure. I also study formal methods
for concurrent and distributed systems.

## LLMs and AI infrastructure

I work from model algorithms down to the systems that execute them.

- **Algorithms and models:** deep learning, generative modeling, and LLMs.
- **Inference frameworks:** SGLang and vLLM, including execution paths,
  KV cache management, memory behavior, and parallel execution.
- **GPU operators and kernels:** CUDA programming, warp-level execution,
  and performance optimization for machine learning workloads.
- **Compilers and runtimes:** kernel DSLs, intermediate representations,
  virtual machines, and task scheduling.
- **GPU infrastructure:** cluster architecture, resource management,
  and the interaction between computation, communication, and storage.

## Research

My research spans deep learning, AI systems, and formal verification,
with earlier work in autonomous driving and robotics.

From 2022 to 2025, my research at Eindhoven University of Technology
focused on high-performance computing: CUDA warp-level programming,
GPU cluster architecture, and formal verification of distributed systems,
including deadlock and livelock analysis.

My earlier work explored complex systems through mean-field models
and differential equations, with a focus on numerical stability.

## Formal methods

[DTESSL](https://github.com/Ziang-Chen/DTESSL) is a discrete-time event
system modeling language I develop for describing concurrent behavior
and checking temporal properties.

It combines typed states, atomic concurrent transitions, explicit causal
dependencies, and deterministic replay. The current implementation is
a standalone C++20 library and CLI with a built-in model checker.

I am also exploring GPU-accelerated verification through its Embedding
representation. The current implementation uses a C++ reference interpreter;
external effects are expressed as action plans and executed by the host.

[English documentation](https://github.com/Ziang-Chen/DTESSL/blob/main/README.en.md)
· [中文文档](https://github.com/Ziang-Chen/DTESSL/blob/main/README.md)
· [Design and research references](https://github.com/Ziang-Chen/DTESSL/blob/main/docs/REFERENCES.md)

![dtesslposter](https://github.com/Ziang-Chen/DTESSL/blob/main/docs/images/dtessl-overview-en.png)

## Game Dev

At the end of this long Bios, for fun, I am also building my own 3D engine, with a custom asset description language,
scene editing, physics simulation, and integration with backend rendering
pipelines such as Blender. Tentatively named **chenEngine**, it will be
made public gradually.

Here is a look at the photorealistic visuals I am working toward with chenEngine:
[night fury](https://ziang-chen.github.io/nightfury-racing/?lang=en)

![nightfurypreview](https://github.com/Ziang-Chen/nightfury-racing/raw/main/dist/screenshots/city.jpg?v=30)

![chenEngine demo](https://github.com/Ziang-Chen/nightfury-racing/blob/main/docs/media/chenengine-showcase-readme.gif)



## Other projects

- [Lisp](https://github.com/Ziang-Chen/Lisp) — a Lisp embedded in Python, started
  during my undergraduate studies.
- [browser](https://github.com/Ziang-Chen/browser) — a browser-based environment
  exploring a controllable workspace for agent-assisted development.
- VM, Runtime, etc. I also work in building my own virtual machine with highly customized ISA, have to admit is a most difficult one. But it has potential to be a common foundation of the whole stack: from agent runtime to some basic instruction execuntion. Now the fileSystem is done, virtual net card almost..... May be I will cast some scheduling method to LLM inference in future as a part of gardually open Source plan.

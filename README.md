# Ziang Chen

I work on high-performance computing, GPU systems, and formal verification,
with an interest in machine learning workloads. Much of my work concerns how
concurrent systems execute: their state transitions, dependencies, scheduling,
and failure modes.

## Research

From 2022 to 2025, my research at Eindhoven University of Technology focused on
high-performance computing. It covered GPU programming with CUDA warp-level
features, GPU cluster architecture from kernels to services, and formal
verification of large-scale distributed systems, including deadlock and livelock
analysis.

My earlier work explored complex systems through mean-field models and
differential equations, with a focus on numerical stability.

## DTESSL: modeling concurrent execution

[DTESSL](https://github.com/Ziang-Chen/DTESSL) connects my work on GPU systems
and formal verification. It is a discrete-time event system modeling language
for describing typed state, concurrent transitions, causal dependencies, and
temporal properties.

For GPU and distributed systems, the questions behind it are concrete: which
operations may happen together, what each operation depends on, whether a
schedule can stop making progress, and how a problematic execution can be
reproduced. DTESSL provides an explicit model in which to investigate those
questions.

- Concurrent inputs read one state snapshot and commit as an atomic round.
- Causal history records dependencies between transition occurrences.
- Temporal claims are checked over execution states and property monitors.
- Captured typed inputs can be replayed to reconstruct logical execution.

The current implementation is a standalone C++20 library and CLI with a built-in
model checker. GPU execution is a research context for the project; this release
uses a C++ reference interpreter. Results apply to the supplied model, with its
assumptions and coverage. External effects are represented as action plans and
executed by the host system.

[English documentation](https://github.com/Ziang-Chen/DTESSL/blob/main/README.en.md)
· [中文文档](https://github.com/Ziang-Chen/DTESSL/blob/main/README.md)
· [Design and research references](https://github.com/Ziang-Chen/DTESSL/blob/main/docs/REFERENCES.md)

## Other projects

- [Lisp](https://github.com/Ziang-Chen/Lisp) — a Lisp embedded in Python, started
  during my undergraduate studies.
- [browser](https://github.com/Ziang-Chen/browser) — a browser-based environment
  exploring a controllable workspace for agent-assisted development.

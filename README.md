# Research Engineering Portfolio — Experiments, Techniques, and Traces of Logic

**Purpose.** This repository is a curated portfolio of small, reproducible research artifacts. It showcases how I approach open-ended problems: form a hypothesis, build the smallest testable system, evaluate against a baseline, and iterate with evidence.

**What this demonstrates**
- Turning ideas into **runnable, deterministic experiments**.
- Writing **invariants and lightweight tests** to pin down behavior.
- Using **ablations** and before/after comparisons to justify changes.
- Preferring **readable, inspectable implementations** over opaque cleverness.
- Documenting the **reasoning trail** behind key decisions.

**Methods represented**
- Discrete dynamical systems and local-update rules
- Stochastic processes and sampling (seeded RNG, annealing schedules)
- Symbolic/algorithmic modeling (finite-state, combinators, cellular automata)
- Optimization and search with simple, explainable heuristics
- Vectorized numerics and pragmatic performance tuning

**Evaluation philosophy**
- **Reproducible by default:** fixed seeds and pinned environments.
- **Baselines first:** compare to the simplest meaningful alternative.
- **Ablate, then conclude:** measure the contribution of each component.
- **Test what matters:** invariants, sanity checks, and targeted property tests.
- **Name limits:** state failure modes and non-goals to keep claims tight.

**Scope & ethics**
These are research prototypes intended for learning and evaluation. They avoid sensitive/dual-use domains and make claims only to the extent demonstrated by included experiments and figures.

**Provenance**
This portfolio summarizes a longer development history. A deeper record of experiments, notes, and commit evolution is available on request.

**Contact**
Matthew Gautier — see profile for email or open an issue in this repository.

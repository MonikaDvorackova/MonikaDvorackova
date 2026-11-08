# Monika Dvořáčková

**Senior AI/ML Engineer · AI Governance Runtime · Model Evaluation · World Models**

I design and implement systems that make ML decisions inspectable: policy enforcement at runtime, evidence provenance, deterministic evaluation, and model-behavior analysis.

## Governance runtime

- **[AIGov Core](https://github.com/AIGovDev/aigov-core)** — open-source Rust audit runtime with a Python SDK and CLI. It applies policy at evidence ingest, derives `VALID / INVALID / BLOCKED` from ledger state, and supports hash-chain verification and offline audit-export checks. Start with the [runtime quickstart](https://github.com/AIGovDev/aigov-core/blob/main/docs/quickstart-runtime.md), [architecture and data flow](https://github.com/AIGovDev/aigov-core/blob/main/ARCHITECTURE.md), and [release verification checklist](https://github.com/AIGovDev/aigov-core/blob/main/docs/releases/release-checklist.md).
- **Compliance Engine** — separate private implementation for policy-gated governance workflows; its source is not public.

## How governance and world models connect

These are separate engineering and research tracks, not one integrated product. The common question is whether a system’s conclusions can be traced to the evidence, policy, model, and evaluation conditions that produced them. AIGov Core addresses evidence and policy decisions; the world-model projects examine rollout error, counterfactual interventions, and disagreement between predicted and environment outcomes.

## Selected engineering work

| Project | Scope and maturity |
| --- | --- |
| [Agent Reliability Bench](https://github.com/MonikaDvorackova/agent-reliability-bench) | Deterministic tool-trace protocol evaluation with batch reports; a reference benchmark, not a live-agent reliability certification. |
| [Formal AI Verification](https://github.com/MonikaDvorackova/formal-ai-verification) | Rust policy predicates and SMT counterexample checks; proofs are limited to the supplied Boolean model. |
| [Latent Dynamics Bench](https://github.com/MonikaDvorackova/latent-dynamics-bench) | Multi-seed ridge-linear rollout benchmark with persistence baseline and per-seed RMSE; no neural latent encoder or real-world validation. |
| [Model-Based Evaluation Suite](https://github.com/MonikaDvorackova/model-based-eval-suite) | Multi-seed predicted/actual return and transition-error report; can emit an AIGov Core evaluation event. Synthetic policies and dynamics only. |
| [Causal ML Benchmarks](https://github.com/MonikaDvorackova/causal-ml-benchmarks) | Stratified backdoor adjustment on synthetic data; assumptions are documented in the repository. |
| [ML Systems Engineering](https://github.com/MonikaDvorackova/ml-systems-engineering) | C++ reference GEMM and illustrative microbenchmark; not a BLAS performance claim. |

The smaller research repositories are deliberately scoped reference implementations. Their READMEs state what each example tests, how to run it, and what it does not establish; they are not presented as production-certified systems or peer-reviewed results.

## Selected open-source contributions

- **[Matplotlib #32575](https://github.com/matplotlib/matplotlib/pull/32575)** — merged fix for non-finite tick locations in `FixedLocator`.
- **[CPython #160980](https://github.com/python/cpython/pull/160980)** — open contribution adding PathLike support to `fnmatch.filter()` and `filterfalse()`.
- **[SciPy #26592](https://github.com/scipy/scipy/pull/26592)** — open documentation contribution clarifying DIA sparse-format indexing.
- **[neuralforecast #1734](https://github.com/Nixtla/neuralforecast/pull/1734)** — open fix for zero and near-zero affine weights in RevIN denormalization.

## Research and writing

My interests include AI governance engineering, reliable ML systems, and evaluation of learned dynamics. For publications and background, see my [website](https://monikadvorackova.net).

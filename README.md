# Monika Dvořáčková

**Senior AI/ML Engineer · AI Governance Systems · Evidence Provenance · World Models**

I build policy-gated audit runtimes and evaluation pipelines for machine-learning systems. My work covers append-only evidence ledgers, artifact-bound CI gates, deterministic compliance verdicts, agent-trace evaluation, and learned dynamics.

## AIGov engineering

- **[AIGov Core](https://github.com/AIGovDev/aigov-core)** — open-source audit runtime with Rust policy enforcement and a Python SDK/CLI. It ingests append-only evidence, verifies hash-chain integrity and signed exports, and exposes deterministic `VALID / INVALID / BLOCKED` decision projections.
- **Compliance Engine** — separate private implementation for policy-gated governance workflows and audit evidence. Its source is not public.

## Technical focus

- **Governance runtime:** evidence schemas, policy gates, immutable audit trails, decision projections, and artifact-bound CI verification.
- **Reliability evaluation:** agent tool traces, confidence intervals, causal benchmarks, robustness, and distribution shift.
- **World models:** latent state dynamics, multi-step rollouts, and model-based planning.
- **ML systems:** reproducible experiments, typed service interfaces, testing, and performance baselines.

## Selected open-source contributions

- **[Matplotlib #32575](https://github.com/matplotlib/matplotlib/pull/32575)** — merged fix for non-finite tick locations in `FixedLocator`.
- **[CPython #160980](https://github.com/python/cpython/pull/160980)** — open contribution adding PathLike support to `fnmatch.filter()` and `filterfalse()`.
- **[SciPy #26592](https://github.com/scipy/scipy/pull/26592)** — open documentation contribution clarifying DIA sparse-format indexing. (Issue #26588.)
- **[neuralforecast #1734](https://github.com/Nixtla/neuralforecast/pull/1734)** — open fix for zero and near-zero affine weights in RevIN denormalization.

## Selected research and engineering projects

| Project | Technical scope |
| --- | --- |
| [Agent Reliability Bench](https://github.com/MonikaDvorackova/agent-reliability-bench) | Deterministic agent-trace evaluation, batch reports, confidence intervals; [live demo](https://monikadvorackova.github.io/agent-reliability-bench/) |
| [World Models Lab](https://github.com/MonikaDvorackova/world-models-lab) | State-space identification and multi-step rollout baselines |
| [Formal AI Verification](https://github.com/MonikaDvorackova/formal-ai-verification) | Policy approval gates, temporal monitoring, and SMT-based checks |
| [Causal ML Benchmarks](https://github.com/MonikaDvorackova/causal-ml-benchmarks) | Causal effect estimation, propensity weighting, and bootstrap intervals |
| [Neurosymbolic Reasoning](https://github.com/MonikaDvorackova/neurosymbolic-reasoning) | Horn-rule inference with derivation provenance |
| [ML Systems Engineering](https://github.com/MonikaDvorackova/ml-systems-engineering) | C++ matrix-kernel implementations and performance baselines |

The research repositories are reproducible engineering baselines; they are not presented as peer-reviewed breakthroughs or production-certified systems.

## Research and writing

My interests include reliable ML pipelines, technical AI governance, and how model behavior propagates into operational decisions. For publications and background, see my [website](https://monikadvorackova.net).

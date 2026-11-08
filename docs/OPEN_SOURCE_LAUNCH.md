# Open-source research engineering launch kit

Prepared 2026-11-08. These are drafts for human review, **not published posts**. Avoid suggesting that the projects are independently validated or peer reviewed.

## LinkedIn (English)

I've published six open-source reference implementations focused on trustworthy AI and reliable machine-learning systems.

The projects cover agent tool-call reliability, world-model rollout evaluation, formal governance verification, causal effect estimation, neuro-symbolic rule inference, and C++ numerical kernels.

All six have public source code and automated tests. Agent Reliability Bench also has a browser demo and a downloadable benchmark artifact.

These are deliberately scoped engineering baselines, not production-certified systems. I'm interested in reproducibility reports, counterexamples, and technically specific feedback.

Explore the projects: https://monikadvorackova.net/research-projects
Try the agent reliability demo: https://monikadvorackova.github.io/agent-reliability-bench/

#TrustworthyAI #AIGovernance #MLOps #OpenSource

## Hacker News

Title: Show HN: Agent Reliability Bench – deterministic evaluation of agent tool traces

URL: https://monikadvorackova.github.io/agent-reliability-bench/

First comment:

I built a small, open-source benchmark for checking whether an agent's tool-call sequence matches an expected protocol. It reports exact-match success, forbidden tool calls, and call-budget violations, with JSONL batch evaluation and confidence intervals.

It deliberately does not measure semantic correctness or general agent intelligence. The demo runs in the browser; the Python implementation and regression tests are public: https://github.com/MonikaDvorackova/agent-reliability-bench

I'd appreciate feedback on useful failure modes and ways to compare real agent traces without exposing sensitive execution logs.

## Reddit technical post

Title: Open-source benchmark for agent tool-call protocol reliability (Python + static demo)

Body:

I built a deterministic evaluator for agent tool-call traces. It checks expected tool order, forbidden tool usage, and call budgets, and supports JSONL batch reports. It is intentionally a narrow protocol-compliance benchmark, not an LLM reasoning benchmark.

Code: https://github.com/MonikaDvorackova/agent-reliability-bench
Demo: https://monikadvorackova.github.io/agent-reliability-bench/

I'd value feedback on real-world trace formats and failure modes. Before posting, check each community's self-promotion rules and adapt the post to that audience.

## Hugging Face dataset description

Dataset: https://huggingface.co/datasets/MonikaDvorackova/agent-reliability-results

A published benchmark result dataset for deterministic agent tool-call protocol evaluation. Source code, methodology, and regression tests are available at https://github.com/MonikaDvorackova/agent-reliability-bench. This does not constitute semantic evaluation of LLM responses.

## Release and DOI checklist

1. Confirm all workflows green on the release commit.
2. Record the exact tested commit and attach reproducible artifacts.
3. Publish an immutable GitHub release with a version tag.
4. Connect Zenodo to GitHub and enable archiving for the desired repositories.
5. Publish a release to trigger a Zenodo archive, then cite the **actual minted DOI** (never a placeholder).
6. Update repository CITATION.cff and website with verified DOI and release URL.

## Manual account actions

- Pin selected repositories on the GitHub profile (GitHub profile customization).
- Add repository topics in Settings/About for each repository.
- Publish LinkedIn, Hacker News, and Reddit posts after reviewing text and community rules.
- Enable GitHub Discussions if community discussion is desired.
- Connect Zenodo before claiming DOI minting.

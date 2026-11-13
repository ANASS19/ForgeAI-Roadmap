<div align="center">

![ForgeAI Roadmap banner](docs/assets/banner.svg)

### Building the skills and systems behind frontier AI.

[Roadmap](docs/ROADMAP.md) · [Architecture](docs/ARCHITECTURE.md) · [Experiment registry](docs/EXPERIMENTS.md) · [Research log](docs/RESEARCH_LOG.md) · [Project website](https://anass19.github.io/ForgeAI-Roadmap/)

</div>

---

## Overview

This is the public research roadmap for Forge AI: transparent milestones from first-principles practice to approximately 1B and 4B language models, followed by multimodal foundation models, agents and embodied intelligence. Plans are distinguished from verified engineering results.

**Status:** Active learning roadmap. **No completed 1B/4B training runs, released model weights, or benchmark results are claimed.**

## Engineering areas

- First-principles model engineering
- Foundation model training and evaluation
- GPU systems and scalable learning
- Multimodal and agentic AI
- Robotics and physical AI

## Milestones

| Stage | Milestone | Acceptance criterion | Status |
|---|---|---|---|
| 00 | ForgeAi practice | First-principles autodiff, Transformer internals and sub-1B experiments | In progress |
| 01 | ForgeLM-1B | Build, train, verify and serve a 1B-class model with reproducible evidence | Preparation |
| 02 | ForgeLM-4B | Extend training systems and model capability with measured scaling | Future |
| 03 | Multimodal foundation models | Study joint vision, audio, video and language modeling | Long-term |
| 04 | Agentic & reasoning systems | Investigate tool use, inference-time compute, planning and evaluations | Long-term |
| 05 | Physical AI / embodied systems | Study perception, actions, simulation and robotics integration | Long-term |

## Repository layout

```text
ForgeAI-Roadmap/
├── README.md                 Project overview
├── docs/
│   ├── index.html            GitHub Pages project website
│   ├── style.css             Responsive styling
│   ├── assets/               Minimal SVG brand assets
│   ├── ROADMAP.md            Milestone acceptance criteria
│   ├── ARCHITECTURE.md       Research design decisions
│   ├── EXPERIMENTS.md        Results and reproducibility registry
│   └── RESEARCH_LOG.md       Dated activity notes
├── src/                      Planned core implementations
├── data/                     Dataset documentation (no raw corpora)
├── configs/                  Future experiment configurations
├── tests/                    Future numerical/integration tests
├── evals/                    Future evaluation code
├── experiments/              Future experiment records
├── infra/                    Compute and deployment notes
├── scripts/                  Future entry points
└── .github/                  Issue and pull-request templates
```

*Directories with only README files describe intended structure, not completed software.*

## Research principles

1. Record precise assumptions, versioned configs, sources and datasets.
2. Separate proposed work, experiment runs, verified metrics and model releases.
3. Preserve validation evidence, reproducibility metadata, numerical checks and failures.
4. Report actual hardware use, training tokens, parameter counts and operating costs only after measurement.
5. Avoid publishing credentials, proprietary datasets or uncontrolled model artifacts.

## Project boundaries

The existing [ForgeAi](https://github.com/ANASS19/ForgeAi) repository is an **independent, unchanged practice workspace for sub-1B and first-principles exercises**. This project is a separate milestone. See the [ForgeAI roadmap](https://github.com/ANASS19/ForgeAI-Roadmap) for the broader program.

## Collaboration and license

Technical discussion and issues are welcome. A source/model license has not yet been selected; public source visibility alone does not grant reuse rights. Appropriate licenses will be chosen before sharing reusable implementations or weights.

---

Maintained by [ANASS19](https://github.com/ANASS19) · Forge AI research engineering.

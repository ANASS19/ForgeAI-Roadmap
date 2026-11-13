# ForgeAI Roadmap — Research roadmap

> **Status:** Active learning roadmap. All model parameter counts are research targets until verified.

This is the public research roadmap for Forge AI: transparent milestones from first-principles practice to approximately 1B and 4B language models, followed by multimodal foundation models, agents and embodied intelligence. Plans are distinguished from verified engineering results.

| Stage | Milestone | Acceptance criterion | Status |
|---|---|---|---|
| 00 | ForgeAi practice | First-principles autodiff, Transformer internals and sub-1B experiments | In progress |
| 01 | ForgeLM-1B | Build, train, verify and serve a 1B-class model with reproducible evidence | Preparation |
| 02 | ForgeLM-4B | Extend training systems and model capability with measured scaling | Future |
| 03 | Multimodal foundation models | Study joint vision, audio, video and language modeling | Long-term |
| 04 | Agentic & reasoning systems | Investigate tool use, inference-time compute, planning and evaluations | Long-term |
| 05 | Physical AI / embodied systems | Study perception, actions, simulation and robotics integration | Long-term |

## Definition of done

A milestone is completed only with reproducible implementation evidence, configuration, verification/test results, and where applicable hardware/data manifests, published artifacts and measured results. A proposed design or a prepared repository is not evidence of a trained model.

## Decision gates

- **Data:** legally usable source, provenance, filtering, leak checks and quality report.
- **Engineering:** independently rerunnable pipeline, numerical tests, checkpoints and monitoring.
- **Compute:** hardware access, throughput benchmark, memory plan and realistic budget.
- **Evaluation:** frozen protocols, explicit baselines, failure cases and reproducible scoring.

## Next action

First-principles autodiff, Transformer internals and sub-1B experiments.

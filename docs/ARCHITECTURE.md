# ForgeAI Roadmap — Architecture notes

## Working assumption

Forge AI is an umbrella roadmap, not a claim that its target models are already built. Existing <1B practice is tracked separately in the existing ForgeAi repository; each model milestone has its own independent repository and measured acceptance criteria.

## Open decisions

- Model parameter budget, vocabulary, context length and representation dimensions (when applicable).
- Data composition, quality/contamination checks, provenance and licenses.
- Training objectives, optimizer, precision, batching, efficiency and stopping criteria.
- Hardware topology, checkpoint format, artifact lifecycle and reproducibility.
- Evaluation protocols, base model comparisons and safe release criteria.

## Engineering standards

Changes should include shape and numerical tests where relevant, explicit configuration, deterministic small tests, monitored training behavior, checkpoint recovery, and failure analysis. No architecture is described as final until experiments establish it.

## Tracking

See [decision log](DECISIONS.md) and [experiments](EXPERIMENTS.md).

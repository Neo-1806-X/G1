# G1 — Jeevan

**Generation 1 · Experimental Language Intelligence System**

G1 is an independent machine-learning research project focused on
understanding, implementing, training, and evaluating language models.

The project begins by studying SmolLM2-360M and progressively develops
an independently implemented language model.

## Objectives

- Study modern language-model architectures.
- Understand tokenization, attention, and next-token prediction.
- Investigate pretrained model weights and training methodologies.
- Implement neural-network components from first principles.
- Conduct reproducible training and evaluation experiments.
- Develop and document the G1 language model.

## Research Subject

**SmolLM2-360M**

Official resources:
- https://github.com/huggingface/smollm
- https://huggingface.co/HuggingFaceTB/SmolLM2-360M

## Project Structure

- `configs/` — Model and training configurations.
- `research/` — Technical research and architecture notes.
- `models/pretrained/` — Pretrained model artifacts.
- `models/g1/` — Checkpoints produced by G1 experiments.
- `src/g1/` — Our implementation.
- `training/` — Training workflows.
- `experiments/` — Experimental results.
- `evaluation/` — Model evaluation.
- `tests/` — Automated tests.
- `scripts/` — Development utilities.
- `docs/` — Technical documentation.

## Development Status

**Stage:** Initial setup and model research.

No independent G1 model has been trained yet.

## Research Principles

- Distinguish original upstream code from our own implementation.
- Document sources and licensing.
- Record experiments and their limitations.
- Prefer reproducible results over unsupported claims.

---

G1 is an ongoing research project. Its architecture and capabilities
will evolve as implementation and experiments progress.

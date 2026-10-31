# C1 · Models, nulls, and scientific claims

_Tier 1 · The Common Language · Week 1 · draft curriculum_

**You will be able to:** Specify variables, scales, assumptions, observables, and a null or comparison model. Separate description, prediction, parameter inference, mechanism, and intervention. Identify leakage and circularity.

**Exit evidence:** Design a matched null and state what result would weaken the claim.

## Readings

### Foundation

- Fosdick, Larremore, Nishimura & Ugander (2018), *Configuring random graph models with fixed degree sequences.* SIAM Review.
  How to sample network null models correctly — the reference for graph nulls.
- Gelman & Loken (2013), *The garden of forking paths.* (working paper / American Scientist).
  Researcher degrees of freedom and the multiple-comparisons trap in exploratory work.
- Kapoor & Narayanan (2023), *Leakage and the reproducibility crisis in machine-learning-based science.* Patterns.
  Data leakage — the dominant failure mode in ML-for-science.

### Deepening

- Gelman, Carlin, Stern, Dunson, Vehtari & Rubin (2013), *Bayesian Data Analysis* (3rd ed.). CRC.
  First pass: Chapters 1, 5–7, and 10–11.
  The practical reference. Hierarchical models, MCMC, model checking.
- Jaynes (2003), *Probability Theory: The Logic of Science.* Cambridge.
  First pass: Chapters 1–4 and 11.
  Philosophical foundation for Bayesian reasoning. Ch. 1–4, 11.

## Exercise

Design and defend two competing null models for one lab result, and show which apparent effect each one destroys.

1. Pick one result: yours, or a lab result you can rerun.
2. State the claim in one sentence. Then write the dullest process that could have produced the same data.
3. Build two null models and list the constraints each one preserves.
4. Run both, and tabulate which apparent effects each null destroys.
5. Map leakage and forks: what entered model selection, and how many analysis paths you tried.
6. Write down your answer to the falsification question.

**Deliverable:** A two-page null-model dossier plus executable comparison of two null ensembles on a live or synthetic result.

## Common mistakes

- Choosing a null that preserves the wrong constraints, or allowing preprocessing and leakage to answer the question in advance.

How to guard against them:

- Say which graph space you sample (simple or multi-edge, with or without self-loops, stub- or vertex-labelled), then sample it correctly. (see Fosdick, Larremore, Nishimura & Ugander (2018))
- Split first. Fit every preprocessing and selection step inside the training fold. Run the leakage taxonomy as a checklist before you believe the score. (see Kapoor & Narayanan (2023))
- Write down the forks before you look, report how many you walked, and keep exploratory structure labelled as exploratory. (see Gelman & Loken (2013))

## The question to ask

> What result would show that the reported structure is compatible with an uninteresting data-generating process?

## Checkpoint

Present your work at a Thursday lab meeting.

## Beyond the common route

- Marek et al. (2022), *Reproducible brain-wide association studies require thousands of individuals.* Nature. Research-stream reading (brain track).

---

[Overview](../README.md) · [C2 · Graphs & spectra →](c2-graph-structure-operators-and-spectra.md)

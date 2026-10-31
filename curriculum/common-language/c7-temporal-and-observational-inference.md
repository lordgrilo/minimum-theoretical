# C7 · Temporal and observational inference

_Tier 1 · The Common Language · Weeks 10–11 · draft curriculum_

**You will be able to:** Model sequences, hidden states, nonstationarity, and directed prediction. Understand why temporal order or predictive improvement alone does not prove a causal mechanism.

**Exit evidence:** Compare two temporal models and identify an observation or intervention that would discriminate them.

## Readings

### Foundation

- Shumway & Stoffer (2017), *Time Series Analysis and Its Applications* (4th ed.). Springer.
  First pass: Chapters 1–4 and 6.
  AR / state-space models and spectral analysis. The standard.
- Pearl, Glymour & Jewell (2016), *Causal Inference in Statistics: A Primer.* Wiley. _(decided 2026-10-07)_
  The accessible entry point.

### Deepening

- Pearl (2009), *Causality: Models, Reasoning, and Inference* (2nd ed.). Cambridge.
  First pass: Chapters 1 and 3, Sections 6.1–6.2, and Chapter 7.
  Causal graphs and do-calculus; the reference.
- Schreiber & Schmitz (2000), *Surrogate time series.* Physica D.
  Surrogate-data null tests for nonlinearity and coupling.
- Barnett, Barrett & Seth (2009), *Granger causality and transfer entropy are equivalent for Gaussian variables.* Physical Review Letters.
  The caveat to keep in mind when reading directed-information results.
- Runge et al. (2019), *Detecting and quantifying causal associations in large nonlinear time series datasets.* Science Advances.
  Causal discovery in time series (PCMCI) — relevant to fMRI and codas.

## Exercise

On synthetic data with a hidden confounder, show what extra assumptions or interventions would turn dependence into a causal claim.

1. Generate a nonstationary sequential system with a hidden confounder.
2. Draw the DAG, and use d-separation and backdoor adjustment to say what is identifiable.
3. Fit a latent-state model (an HMM or state-space model) and run a surrogate-data test.
4. Run Granger or transfer-entropy discovery, and show where it points the wrong way.
5. Name the intervention that would settle the question.
6. Write down your answer to the falsification question.

**Deliverable:** A checked probabilistic model plus a causal-claim ledger listing assumptions, identifiable effects, and non-identifiable alternatives.

## Common mistakes

- Treating posterior concentration, predictive success, Granger predictability, transfer entropy, or a fitted arrow as a causal mechanism.
- Forcing stationarity, selecting hidden states post hoc, or interpreting directed predictability as an identified mechanism.

How to guard against them:

- Write the causal model. State which effects are identifiable, which confounders could reverse the arrow, and which intervention would decide it. (see Pearl, Glymour & Jewell (2016))
- Test for changepoints and nonstationarity, fix the number of states before fitting, and compare against surrogates. (see Shumway & Stoffer (2017))

## The question to ask

> Which model misfit, latent confounder, intervention, or invariance failure would reverse the interpretation?

## Checkpoint

Present your work at a Thursday lab meeting.

## Beyond the common route

- Rabiner (1989), *A tutorial on hidden Markov models and selected applications in speech recognition.* Proceedings of the IEEE. Research-stream reading (CETI/sequence work).

---

[← C5 · Information](c5-information-dependence-and-compression.md) · [Overview](../README.md) · [C8 · Coarse-graining →](c8-representation-coarse-graining-and-preserved-quant.md)

# C5 · Information, dependence, and compression

_Tier 1 · The Common Language · Weeks 8–9 · draft curriculum_

**You will be able to:** Use entropy, mutual and conditional information, rate–distortion, and the information bottleneck. Distinguish interaction order from statistical dependence, and redundancy/synergy measures from mechanisms.

**Exit evidence:** Compute an information quantity in a toy system and state the estimator and decomposition ambiguities.

## Readings

### Foundation

- Cover & Thomas (2006), *Elements of Information Theory.* Wiley.
  First pass: Chapters 2, 4, and 10.
  THE textbook. Priority: Ch. 2 (entropy), 4 (MI), 10 (rate-distortion).
- Watanabe (1960), *Information theoretical analysis of multivariate correlation.* IBM Journal of Research and Development.
  Introduces total correlation (multi-information) — the conceptual root of multivariate dependency measures.
- Rosas, Mediano, Gastpar & Jensen (2019), *Quantifying high-order interdependencies via multivariate extensions of the mutual information.* Physical Review E. _(decided 2026-10-07)_
  Introduced the O-information (signed synergy/redundancy).

### Deepening

- Tishby, Pereira & Bialek (2000), *The Information Bottleneck Method.* Proc. Allerton Conference on Communication, Control and Computing (verify year). arXiv:physics/0004057.
  Compression–relevance tradeoff. Theoretical ancestor of the semanticity programme.
- Zaslavsky, Kemp, Regier & Tishby (2018), *Efficient compression in color naming across languages.* PNAS.
  IB explains cross-linguistic color-naming universals. Beautiful empirical validation.
- Timme & Lapish (2018), *A tutorial for information theory in neuroscience.* eNeuro. _(decided 2026-10-07)_
  Practical guide to applying IT measures to neural data.
- Williams & Beer (2010), *Nonnegative decomposition of multivariate information.* arXiv:1004.2515. _(decided 2026-10-07)_
  Foundational Partial Information Decomposition (PID).

## Exercise

Measure compression, redundancy and synergy on systems whose mechanisms you built yourself, and find where the measures disagree.

1. Derive or compute a toy rate–distortion curve.
2. Change the distortion or the relevance variable, and say how the conclusion changes.
3. Build XOR, COPY and common-drive systems whose mechanisms you know.
4. Compute O-information and at least two redundancy measures on each, and mark where they disagree.
5. Vary sample size and estimator, then write a one-paragraph non-uniqueness statement.
6. Write down your answer to the falsification question.

**Deliverable:** A synthetic benchmark with known mechanisms, sample-size curves, estimator comparison, and a non-uniqueness statement.

## Common mistakes

- Treating the sign or magnitude of O-information or a PID atom as a unique physical mechanism.
- Treating a convenient metric, distortion, or compression objective as if it were the system's intrinsic semantics.

How to guard against them:

- Swap the distortion or the relevance variable and check whether the conclusion survives the swap. (see Tishby, Pereira & Bialek (2000))
- Benchmark on systems with a known mechanism, compare two or more redundancy measures, and report sample-size curves. (see Rosas, Mediano, Gastpar & Jensen (2019))

## The question to ask

> Can sampling bias, common drive, discretization, or another decomposition generate the same signature?

## Checkpoint

Present your work at a Thursday lab meeting.

---

[← C6 · Topology](c6-topology-and-persistent-structure.md) · [Overview](../README.md) · [C7 · Temporal & causal →](c7-temporal-and-observational-inference.md)

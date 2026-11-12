# C6 · Topology and persistent structure

_Tier 1 · The Common Language · Week 7 · draft curriculum_

**You will be able to:** Understand filtrations, homology, persistence, stability, and the relationship between topological summaries and the data-generating process.

**Exit evidence:** Produce and stress-test a persistence summary against a noise or surrogate baseline.

## Readings

### Foundation

- Carlsson (2009), *Topology and Data.* Bulletin of the AMS.
  Launched TDA as a field. Start here for intuition.

### Deepening

- Cohen-Steiner, Edelsbrunner & Harer (2007), *Stability of persistence diagrams.* Discrete & Computational Geometry.
  Persistence diagrams are stable under perturbation (bottleneck distance). The theorem that makes TDA trustworthy.
- Edelsbrunner & Harer (2010), *Computational Topology: An Introduction.* AMS.
  First pass: Chapters 1–4 and 7.
  The textbook. Ch. 1–4 (simplicial complexes) and Ch. 7 (persistence).

### Synthesis

- Gardner, Hermansen, Pachitariu, Burak, Baas, Dunn, Moser & Moser (2022), *Toroidal topology of population activity in grid cells.* Nature 602, 123–128.
  Persistent homology on recorded neural population activity recovers the torus that grid-cell theory predicts: topology as a test of a circuit model.

## Exercise

Compute persistence under controlled perturbations, and separate stability from significance and from domain meaning.

1. Compute a persistence diagram on a point cloud or network you know.
2. Perturb the metric, the filtration and the sampling, and tabulate what changes.
3. Build a surrogate or null model, and compute its diagram.
4. Decide which features beat the surrogate, and write a one-page limits statement.
5. In code: compute the diagrams with GUDHI or Ripser, then repeat the surrogate test on recorded neural population activity, as Gardner et al. 2022 do for grid cells.
6. Write down your answer to the falsification question.

**Deliverable:** A persistence analysis under metric, filtration, sampling, and null-model perturbations, with a one-page limits statement.

## Common mistakes

- Equating mathematical stability with significance, mechanism, uniqueness, or biological relevance.

How to guard against them:

- Race every feature against a surrogate built from the same sampling, and vary the filtration and metric before you interpret it. (see Carlsson (2009))

## The question to ask

> Does the topological conclusion survive plausible filtration, metric, sampling, and null-model alternatives?

## Checkpoint

Present your work at a Thursday lab meeting.

## Beyond the common route

- Petri, Expert, Turkheimer, Carhart-Harris, Nutt, Hellyer & Vaccarino (2014), *Homological scaffolds of brain functional networks.* J. R. Soc. Interface. Research-stream reading (capstone case).

---

[← C4 · Dynamics](c4-dynamics-stochasticity-and-emergence.md) · [Overview](../README.md) · [C5 · Information →](c5-information-dependence-and-compression.md)

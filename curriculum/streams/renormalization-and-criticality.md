# Tier 2 · Renormalization and criticality

_Renormalization, criticality, and multiscale systems · from month 4 · draft v0.2 (2026-10-09), reconciled with Tier 1 and awaiting review_

**You will be able to:** Choose and test scale transformations, diagnose genuine critical behaviour, and quantify the trade-off between preserved dynamics, prediction, and reconstruction.

**Builds on:** [C8](../common-language/c8-representation-coarse-graining-and-preserved-quant.md), [C4](../common-language/c4-dynamics-stochasticity-and-emergence.md), [C5](../common-language/c5-information-dependence-and-compression.md), [C2](../common-language/c2-graph-structure-operators-and-spectra.md). Assumes from Tier 1: Sethna (2006); Peyré & Cuturi (2019); Murphy, Thibeault, Allard & Desrosiers (2024); Spielman (2025).

**If this is not your stream, read:** Gabrielli, Garlaschelli, Patil & Serrano (2025), *Network renormalization.* Nature Reviews Physics 7, 203–219

_Estimated load: about 70 hours of reading and 35 for the exercise, over months 4–8._

## Required readings

- García-Pérez, Boguñá & Serrano (2018), *Multiscale unfolding of real networks by geometric renormalization.* Nature Physics.
  Why: Geometric renormalisation is the second scheme set against Laplacian RG.
- Koch-Janusz & Ringel (2018), *Mutual information, neural networks and the renormalization group.* Nature Physics.
  Why: Coarse-graining derived from mutual information: where information theory (C5) meets coarse-graining (C8).
- Bradde & Bialek (2017), *PCA meets RG.* Journal of Statistical Physics.
  Why: It shows PCA and RG as one idea on neural data, the bridge to empirical multiscale work.
- Nurisso, Morandini, Lucas, Vaccarino, Gili & Petri (2025), *Higher-order Laplacian renormalization.* Nature Physics.
  Why: The only higher-order renormalisation scheme we have. Read it against heterogeneity in simplicial density, which could fake order-specific invariance.
- Bak, Tang & Wiesenfeld (1987), *Self-organized criticality: an explanation of 1/f noise.* Physical Review Letters.
  Why: Self-organised criticality is the origin of the avalanche framing we test.
- Harris (1963), *The Theory of Branching Processes.* Springer.
  First pass: Chapter route pending an edition check.
  Why: Branching-process theory defines the subcritical, critical, and supercritical regimes.
- Beggs & Plenz (2003), *Neuronal avalanches in neocortical circuits.* Journal of Neuroscience.
  Why: The empirical neuronal-avalanche claim, which the exercise's criticality test interrogates.
- Clauset, Shalizi & Newman (2009), *Power-law distributions in empirical data.* SIAM Review 51, 661–703.
  Why: The statistical test the stream's failure mode demands: a power law has to beat heavy-tailed alternatives before anyone says critical.

### Re-read at depth (from Tier 1)

- Villegas, Gili, Mulder, Caldarelli & Bianconi (2023), *Laplacian renormalization group for heterogeneous networks.* Nature Physics.  
  Go back to it at depth: the stream exercise sets it against a second scheme.

## Project exercise

Compare two coarse-graining schemes and one criticality test on the same system using preregistered preserved observables and finite-size controls.

**Deliverable:** A preregistration and a results table: two schemes against the preserved observables, finite-size scaling, and a criticality verdict with the alternatives it rules out.

## Common mistake

Inferring universality or criticality from attractive scaling, power laws, or post hoc selection of the quantity that appears preserved.

## The question to ask

> Does the critical or invariant signature survive finite-size scaling, a model-selection test against non-critical heavy-tailed alternatives, and an observable declared in advance?

## Case material (optional)

- Guadagnuolo, Nurisso, Galluzzi, Allard & Petri (2026), *Harmonic morphisms and dynamical invariants in network renormalization.* arXiv:2604.08386 (under review, PRX).
- Lucas, Bisot, Petri, Declerck & Carletti (2026), *Minimal branching and fusion morphogenesis approaches biological multi-objective optimality.* arXiv:2601.03877
- Müller, Miron, Holtkamp & Meisel (2025), *Critical dynamics predicts cognitive performance and provides a common framework for heterogeneous mechanisms impacting cognition.* PNAS 122:e2417117122
- Reitz & Bianconi (2020), *The higher-order spectrum of simplicial complexes: a renormalization group approach.* J. Phys. A.

---

[← Social, collective and animal communication](social-collective-and-animal-communication.md) · [Overview](../README.md)

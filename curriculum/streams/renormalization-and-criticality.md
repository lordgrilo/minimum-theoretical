# Tier 2 · Renormalization and criticality

_Renormalization, criticality, and multiscale systems · from month 4 · draft v0.4 (2026-11-12), reconciled with Tier 1 and awaiting review_

**You will be able to:** Choose and test scale transformations, diagnose genuine critical behaviour, and quantify the trade-off between preserved dynamics, prediction, and reconstruction.

**Builds on:** [C8](../common-language/c8-representation-coarse-graining-and-preserved-quant.md), [C4](../common-language/c4-dynamics-stochasticity-and-emergence.md), [C5](../common-language/c5-information-dependence-and-compression.md), [C2](../common-language/c2-graph-structure-operators-and-spectra.md). Assumes from Tier 1: Sethna (2006); Peyré & Cuturi (2019); Murphy, Thibeault, Allard & Desrosiers (2024); Spielman (2025).

**If this is not your stream, read:** Gabrielli, Garlaschelli, Patil & Serrano (2025), *Network renormalization.* Nature Reviews Physics 7, 203–219 [doi:10.1038/s42254-025-00817-5](https://doi.org/10.1038/s42254-025-00817-5)

_Estimated load: about 70 hours of reading and 35 for the exercise, over months 4–8._

## Required readings

- García-Pérez, Boguñá & Serrano (2018), *Multiscale unfolding of real networks by geometric renormalization.* Nature Physics. [doi:10.1038/s41567-018-0072-5](https://doi.org/10.1038/s41567-018-0072-5)
  Why: Geometric renormalisation is the second scheme set against Laplacian RG.
- Koch-Janusz & Ringel (2018), *Mutual information, neural networks and the renormalization group.* Nature Physics. [doi:10.1038/s41567-018-0081-4](https://doi.org/10.1038/s41567-018-0081-4)
  Why: Coarse-graining derived from mutual information: where information theory (C5) meets coarse-graining (C8).
- Bradde & Bialek (2017), *PCA meets RG.* Journal of Statistical Physics. [doi:10.1007/s10955-017-1770-6](https://doi.org/10.1007/s10955-017-1770-6)
  Why: It shows PCA and RG as one idea on neural data, the bridge to empirical multiscale work.
- Nurisso, Morandini, Lucas, Vaccarino, Gili & Petri (2025), *Higher-order Laplacian renormalization.* Nature Physics. [doi:10.1038/s41567-025-02784-1](https://doi.org/10.1038/s41567-025-02784-1)
  Why: The only higher-order renormalisation scheme we have. Read it against heterogeneity in simplicial density, which could fake order-specific invariance.
- Bak, Tang & Wiesenfeld (1987), *Self-organized criticality: an explanation of 1/f noise.* Physical Review Letters. [doi:10.1103/physrevlett.59.381](https://doi.org/10.1103/physrevlett.59.381)
  Why: Self-organised criticality is the origin of the avalanche framing we test.
- Harris (1963), *The Theory of Branching Processes.* Springer. [doi:10.1007/978-3-642-51866-9](https://doi.org/10.1007/978-3-642-51866-9)
  First pass: Chapter route pending an edition check.
  Why: Branching-process theory defines the subcritical, critical, and supercritical regimes.
- Beggs & Plenz (2003), *Neuronal avalanches in neocortical circuits.* Journal of Neuroscience. [doi:10.1523/jneurosci.23-35-11167.2003](https://doi.org/10.1523/jneurosci.23-35-11167.2003)
  Why: The empirical neuronal-avalanche claim, which the exercise's criticality test interrogates.
- Clauset, Shalizi & Newman (2009), *Power-law distributions in empirical data.* SIAM Review 51, 661–703. [doi:10.1137/070710111](https://doi.org/10.1137/070710111)
  Why: The statistical test the stream's failure mode demands: a power law has to beat heavy-tailed alternatives before anyone says critical.

### Re-read at depth (from Tier 1)

- Villegas, Gili, Caldarelli & Gabrielli (2023), *Laplacian renormalization group for heterogeneous networks.* Nature Physics. [doi:10.1038/s41567-022-01866-8](https://doi.org/10.1038/s41567-022-01866-8)  
  Go back to it at depth: the stream exercise sets it against a second scheme.

## Project exercise

Compare two coarse-graining schemes and one criticality test on the same system using preregistered preserved observables and finite-size controls.

**Deliverable:** A preregistration and a results table: two schemes against the preserved observables, finite-size scaling, and a criticality verdict with the alternatives it rules out.

## Common mistake

Inferring universality or criticality from attractive scaling, power laws, or post hoc selection of the quantity that appears preserved.

## The question to ask

> Does the critical or invariant signature survive finite-size scaling, a model-selection test against non-critical heavy-tailed alternatives, and an observable declared in advance?

## Case material (optional)

- Guadagnuolo, Nurisso, Galluzzi, Allard & Petri (2026), *Harmonic morphisms and dynamical invariants in network renormalization.* arXiv:2604.08386 (under review, PRX). [doi:10.48550/arXiv.2604.08386](https://doi.org/10.48550/arXiv.2604.08386) [arXiv](https://arxiv.org/abs/2604.08386)
- Lucas, Bisot, Petri, Declerck & Carletti (2026), *Minimal branching and fusion morphogenesis approaches biological multi-objective optimality.* arXiv:2601.03877 [doi:10.48550/arXiv.2601.03877](https://doi.org/10.48550/arXiv.2601.03877) [arXiv](https://arxiv.org/abs/2601.03877)
- Müller, Miron, Holtkamp & Meisel (2025), *Critical dynamics predicts cognitive performance and provides a common framework for heterogeneous mechanisms impacting cognition.* PNAS 122:e2417117122 [doi:10.1073/pnas.2417117122](https://doi.org/10.1073/pnas.2417117122)
- Reitz & Bianconi (2020), *The higher-order spectrum of simplicial complexes: a renormalization group approach.* J. Phys. A. [doi:10.1088/1751-8121/ab9338](https://doi.org/10.1088/1751-8121/ab9338)

---

[← Social, collective and animal communication](social-collective-and-animal-communication.md) · [Overview](../README.md)

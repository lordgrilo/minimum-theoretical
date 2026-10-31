# Tier 2 · Higher-order networks

_Higher-order network theory, dynamics, and reconstruction · from month 4 · draft v0.2 (2026-10-09), reconciled with Tier 1 and awaiting review_

**You will be able to:** Build, analyse, and infer higher-order network models, and show in each case whether a pairwise or latent-variable alternative would suffice.

**Builds on:** [C2](../common-language/c2-graph-structure-operators-and-spectra.md), [C3](../common-language/c3-higher-order-representations.md), [C4](../common-language/c4-dynamics-stochasticity-and-emergence.md), [C1](../common-language/c1-models-nulls-and-scientific-claims.md), [C7](../common-language/c7-temporal-and-observational-inference.md). Assumes from Tier 1: Bianconi (2021); Bick, Gross, Harrington & Schaub (2023); Peixoto (2023); Sethna (2006); Centola & Macy (2007); Iacopini, Petri, Barrat & Latora (2019); Newman (2002); Arenas, Díaz-Guilera, Kurths, Moreno & Zhou (2008).

**If this is not your stream, read:** Battiston et al. (2021), *The physics of higher-order interactions in complex systems.* Nature Physics.

_Estimated load: about 60 hours of reading and 35 for the exercise, over months 4–8._

## Required readings

- Lim (2020), *Hodge Laplacians on graphs.* SIAM Review.
  Why: Hodge Laplacians are the operators under every argument we make about flows and dynamics on complexes. Learn them here, properly, once.
- Schaub, Benson, Horn, Lippner & Jadbabaie (2020), *Random walks on simplicial complexes and the normalized Hodge 1-Laplacian.* SIAM Review.
  Why: Diffusion on complexes is the baseline that any claim about higher-order spreading or renormalisation departs from.
- Peel, Peixoto & De Domenico (2022), *Statistical inference links data and theory in network science.* Nature Communications.
  Why: The inferential standard your reconstructions will be judged by.
- Pastor-Satorras, Castellano, Van Mieghem & Vespignani (2015), *Epidemic processes in complex networks.* Reviews of Modern Physics.
  Why: The full review behind the Tier 1 epidemic-threshold readings. A higher-order contagion transition only means something against this pairwise theory.
- Skardal & Arenas (2019), *Abrupt desynchronization and extensive multistability in globally coupled oscillator simplexes.* PRL.
  Why: Coupling order alone produces abrupt synchronisation. Read it beside Iacopini et al. 2019 and Arenas et al. 2008 from Tier 1.
- Preti, De Francisci Morales, Iacopini & Petri (2024), *Higher-order null models as a lens for social systems.* Physical Review X.
  Why: Higher-order null models: how to ask whether a group effect is real. Read it against a pairwise null that preserves degree and group-size heterogeneity.
- Petri & Barrat (2018), *Simplicial activity driven model.* Physical Review Letters.
  Why: The minimal generative model for temporal group interactions; you will use it as a benchmark. Read it against a pairwise activity-driven model with heterogeneous activity.

### Re-read at depth (from Tier 1)

- Young, Petri & Peixoto (2021), *Hypergraph reconstruction from network data.* Communications Physics.  
  Go back to it at depth: the stream exercise starts from its reconstruction framework.

## Project exercise

Reconstruct and simulate one synthetic higher-order system from a deliberately lossy observation, comparing at least three model orders.

**Deliverable:** A notebook and a two-page memo. It fits three model orders, compares them by description length or held-out likelihood, and states which order the data identify and which they cannot.

## Common mistake

Treating a convenient higher-order encoding, dynamical fit, or reconstruction as evidence that the generating mechanism is genuinely higher order.

## The question to ask

> Can a pairwise model with matched degree, activity, and community structure, or a latent-variable model, reproduce the higher-order signature at equal description length?

## Case material (optional)

- Mancastroppa, Iacopini, Petri & Barrat (2023), *Hyper-cores promote localization and efficient seeding in higher-order processes.* Nature Communications.
- Lucas, Iacopini, Robiglio, Barrat & Petri (2023), *Simplicially driven simple contagion.* Physical Review Research.
- Nurisso, Vaccarino & Petri (2024), *A unified framework for simplicial Kuramoto models.* Chaos.

---

[Overview](../README.md) · [Brain and clinical neuroscience →](brain-and-clinical-neuroscience.md)

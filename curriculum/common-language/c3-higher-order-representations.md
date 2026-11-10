# C3 · Higher-order representations

_Tier 1 · The Common Language · Week 4 · draft curriculum_

**You will be able to:** Distinguish hypergraphs, simplicial complexes, temporal/multilayer structures, and multivariate random variables. Higher order must be justified against a pairwise or latent-variable alternative.

**Exit evidence:** Encode the same toy system in two representations and show what information changes.

## Readings

### Foundation

- Battiston, Cencetti, Iacopini, Latora, Lucas, Patania, Young & Petri (2020), *Networks beyond pairwise interactions: structure and dynamics.* Physics Reports.
  The manifesto. Defines the field.
- Torres, Blevins, Bassett & Eliassi-Rad (2021), *The why, how, and when of representations for complex systems.* SIAM Review.
  When and why different representations are appropriate.

### Deepening

- Bianconi (2021), *Higher-Order Networks: An Introduction to Simplicial Complexes.* Cambridge.
  First pass: Chapters 1–3 and 6–8, plus Appendix B (Hodge decomposition).
  First dedicated textbook. Algebraic topology, Hodge theory, higher-order dynamics. Essential for higher-order network theory.
- Bick, Gross, Harrington & Schaub (2023), *What are higher-order networks?* SIAM Review.
  When higher-order representations are justified vs. modelling choices.
- Kivelä, Arenas, Barthelemy, Gleeson, Moreno & Porter (2014), *Multilayer networks.* Journal of Complex Networks 2, 203–271.
  The formalism for networks with several kinds of edges or layers: when a multilayer description is needed, and what aggregating the layers throws away.
- Holme & Saramäki (2012), *Temporal networks.* Physics Reports 519, 97–125.
  Edges that exist only at certain times: time-respecting paths, burstiness, and why aggregating over time changes what can spread.

### Synthesis

- Young, Petri & Peixoto (2021), *Hypergraph reconstruction from network data.* Communications Physics.
  Bayesian framework for inferring higher-order structure.

## Exercise

Represent one dataset as a graph, a hypergraph and a simplicial complex, and separate what follows from the data from what follows from the representation.

1. Pick a dataset of group observations: co-authorship, co-sponsorship, co-firing.
2. Encode it as a graph, a hypergraph and a simplicial complex.
3. Write a claim ledger with three columns: measured, encoded and inferred.
4. Fit a pairwise or latent-variable model and check whether it reproduces the higher-order signature.
5. Write down your answer to the falsification question.

**Deliverable:** Three representations of the same dataset with a claim ledger separating measured, encoded, and inferred structure.

## Common mistakes

- Inferring a genuine higher-order mechanism merely because observations arrive in groups or admit a higher-order encoding.

How to guard against them:

- Fit the pairwise and latent-variable alternatives explicitly. Claim higher order only for the signature they cannot reproduce. (see Torres, Blevins, Bassett & Eliassi-Rad (2021))

## The question to ask

> Can an explicitly fitted pairwise or latent-variable model reproduce the alleged higher-order signature?

## Checkpoint

Present your work at a Thursday lab meeting.

---

[← C2 · Graphs & spectra](c2-graph-structure-operators-and-spectra.md) · [Overview](../README.md) · [C4 · Dynamics →](c4-dynamics-stochasticity-and-emergence.md)

# C2 · Graph structure, operators, and spectra

_Tier 1 · The Common Language · Weeks 2–3 · draft curriculum_

**You will be able to:** Move between adjacency, incidence, Laplacian, random-walk, and spectral views. Explain which structural or dynamical question each representation answers.

**Exit evidence:** Derive or compute a Laplacian-based quantity on a small network and interpret it without overclaiming.

## Readings

### Foundation

- Latora, Nicosia & Russo (2017), *Complex Networks: Principles, Methods and Applications.* Cambridge.
  First pass: Chapters 1–6 and 10.
  Best modern textbook. Priority: Ch. 1–6, 10.
- Spielman (2025), *Spectral and Algebraic Graph Theory* (incomplete online draft dated 2 April 2025). https://www.cs.yale.edu/homes/spielman/sagt/
  First pass: Chapters 1–3, 10–12, and 20–23.
  Laplacians, effective resistance, spectral clustering — the bridge to networks and renormalization.
- Peel, Peixoto & De Domenico (2022), *Statistical inference links data and theory in network science.* Nature Communications 13, 6794.
  The shift from descriptive to inferential network science.

### Deepening

- Peixoto (2023), *Descriptive vs. inferential community detection in networks.* Cambridge Elements.
  The principled network-inference position statement.
- Molloy & Reed (1995), *A critical point for random graphs with a given degree sequence.* Random Structures & Algorithms.
  The Molloy–Reed criterion for the giant component.
- Callaway, Newman, Strogatz & Watts (2000), *Network robustness and fragility: percolation on random graphs.* PRL.
  Robustness as percolation.
- Albert, Jeong & Barabási (2000), *Error and attack tolerance of complex networks.* Nature.
  Landmark robustness paper.

### Synthesis

- Buldyrev, Parshani, Paul, Stanley & Havlin (2010), *Catastrophic cascade of failures in interdependent networks.* Nature.
  Landmark interdependent-networks paper.

## Exercise

Describe one network three ways (descriptive, spectral and generative) and decide which account the data actually support.

1. Pick a network you know, and write down the structural question you are asking of it.
2. Move between the adjacency, Laplacian and random-walk views, and say which question each one answers.
3. Compute one Laplacian quantity (spectral gap, Fiedler vector or a diffusion time) and interpret it without overclaiming.
4. Find a partition descriptively, then fit a generative model and compare the two by description length.
5. In code: on a real network of at least a few thousand nodes, fit a stochastic block model with graph-tool and compare it with modularity. Use sparse matrices, never a dense eigendecomposition.
6. Write down your answer to the falsification question.

**Deliverable:** A model-comparison report contrasting descriptive, spectral, and generative accounts of one network.

## Common mistakes

- Treating a detected partition or higher-order reconstruction as evidence without comparing lower-order and latent-variable explanations.

How to guard against them:

- Fit a generative model, compare it against alternatives by description length, and accept a partition only if it beats them. (see Peixoto (2023))

## The question to ask

> Which alternative generative model explains the same observations with equal or lower description length?

## Checkpoint

Present your work at a Thursday lab meeting.

## Beyond the common route

- Barabási & Albert (1999), *Emergence of scaling in random networks.* Science. Background: Preferential attachment and scale-free networks.
- Newman (2003), *The structure and function of complex networks.* SIAM Review. Background: The survey that defined the field.
- Watts & Strogatz (1998), *Collective dynamics of 'small-world' networks.* Nature. Background: The small-world model. Short and elegant.

---

[← C1 · Models & nulls](c1-models-nulls-and-scientific-claims.md) · [Overview](../README.md) · [C3 · Higher-order →](c3-higher-order-representations.md)

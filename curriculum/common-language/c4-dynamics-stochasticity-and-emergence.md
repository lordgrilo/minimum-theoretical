# C4 · Dynamics, stochasticity, and emergence

_Tier 1 · The Common Language · Weeks 5–6 · draft curriculum_

**You will be able to:** Reason about fixed points, stability, bifurcations, diffusion, contagion, synchronisation, fluctuations, phase transitions, and finite-size effects.

**Exit evidence:** Analyse one dynamical model and distinguish a mathematical transition from an empirical universality claim.

## Readings

### Foundation

- Strogatz (2015), *Nonlinear Dynamics and Chaos* (2nd ed.). Westview Press (verify publisher of record).
  First pass: Chapters 1–8.
  Best introductory text. Ch. 1–8.
- Barrat, Barthélemy & Vespignani (2008), *Dynamical Processes on Complex Networks.* Cambridge.
  First pass: Chapters 4–7 and 9: dynamical processes, phase transitions, resilience and robustness, synchronization, epidemic spreading; plus the appendix on the generating-functions formalism (pp. 303–305).
  Essential companion to Newman. Ch. 7 (synchronization), 9 (epidemics), 10 (social dynamics).
- Pastor-Satorras & Vespignani (2001), *Epidemic spreading in scale-free networks.* PRL.
  Absence of an epidemic threshold in scale-free networks.

### Deepening

- Sethna (2006), *Statistical Mechanics: Entropy, Order Parameters, and Complexity.* Oxford.
  First pass: Chapters 2, 7, 8, and 12.
  Best modern stat-mech for complex systems. Freely available. Ch. 2, 7, 8, 12.
- Centola & Macy (2007), *Complex contagion and the weakness of long ties.* American Journal of Sociology.
  Simple vs complex contagion.
- Iacopini, Petri, Barrat & Latora (2019), *Simplicial models of social contagion.* Nature Communications.
  Group interactions create bistability and discontinuous transitions. Founding paper.
- Newman (2002), *Spread of epidemic disease on networks.* Physical Review E.
  Maps SIR epidemics onto bond percolation.
- Arenas, Díaz-Guilera, Kurths, Moreno & Zhou (2008), *Synchronization in complex networks.* Physics Reports.
  Comprehensive synchronization review.

## Exercise

Simulate a bifurcation, a pairwise complex contagion and a higher-order contagion transition, and tell their mechanisms apart.

1. Simulate a saddle-node or Hopf bifurcation and identify its order parameter.
2. Simulate a pairwise complex contagion and a simplicial (higher-order) contagion.
3. For each, name the mechanism, the order parameter and the finite-size effects.
4. Run the finite-size or heterogeneity test that could make each transition disappear.
5. Write down your answer to the falsification question.

**Deliverable:** A simulation study comparing three transition mechanisms, including finite-size and alternative-model checks.

## Common mistakes

- Treating abrupt change, scaling, or a power law as sufficient evidence of universality or criticality.

How to guard against them:

- Compare against alternative distributions, check finite-size scaling, and name the order parameter and the mechanism before using the word critical. (see Sethna (2006))

## The question to ask

> Which finite-size, heterogeneity, or model-selection test would make the claimed transition disappear?

## Checkpoint

Present your work at a Thursday lab meeting.

## Beyond the common route

- Kuramoto (1984), *Chemical Oscillations, Waves, and Turbulence.* Springer. Background: The synchronization reference.

---

[← C3 · Higher-order](c3-higher-order-representations.md) · [Overview](../README.md) · [C6 · Topology →](c6-topology-and-persistent-structure.md)

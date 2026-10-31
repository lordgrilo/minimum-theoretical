# C8 · Representation, coarse-graining, and preserved quantities

_Tier 1 · The Common Language · Week 12 · draft curriculum_

**You will be able to:** Explain dimensional reduction, optimal transport, coarse-graining, and renormalisation in terms of what is preserved, distorted, or made identifiable. Connect these choices to limits on generalisation and information processing.

**Exit evidence:** Define a reduction map and test whether its claimed invariant is actually preserved.

## Readings

### Foundation

- Villegas, Gili, Mulder, Caldarelli & Bianconi (2023), *Laplacian renormalization group for heterogeneous networks.* Nature Physics.
  Diffusion-based spectral coarse-graining. The key recent paper.
- Wilson (1975), *The renormalization group: critical phenomena and the Kondo problem.* Reviews of Modern Physics.
  The foundational RG paper. (Also Tier 3: Renormalization.)

### Deepening

- Kriegeskorte, Mur & Bandettini (2008), *Representational similarity analysis.* Frontiers in Systems Neuroscience.
  The method for comparing representations across brains and models via dissimilarity matrices.
- Peyré & Cuturi (2019), *Computational Optimal Transport.* Foundations and Trends in ML.
  First pass: Chapters 1–4, 8, and Sections 10.2 and 10.6.
  The practical OT reference: algorithms, Sinkhorn, applications. Start here.
- Murphy, Thibeault, Allard & Desrosiers (2024), *Duality between predictability and reconstructability in complex systems.* Nature Communications.
  Coarse-graining trades reconstructability for predictability — a causal-emergence signature.

## Exercise

Coarse-grain one network two ways and test whether the quantity you promised to preserve actually survives.

1. Pick a network and write down, before anything else, the quantity a good reduction should preserve.
2. Coarse-grain it with two schemes, for example Laplacian renormalization and a spectral or community-based reduction.
3. Compare how each preserves diffusion, prediction and higher-order structure.
4. Compare two representations of one system with RSA, and test whether the geometry predicts an independent task limit.
5. Write down your answer to the falsification question.

**Deliverable:** A two-scheme coarse-graining comparison with preregistered preservation criteria and a failure analysis.

## Common mistakes

- Selecting the preserved quantity after observing which coarse-graining looks most successful.
- Equating decodability, geometric alignment, or compression with causal use, compositionality, or semantics.

How to guard against them:

- Preregister the preserved quantity, then report the observables that fail under the transformation. (see Villegas, Gili, Mulder, Caldarelli & Bianconi (2023))
- Pair every decoding result with an intervention or an independent behavioural limit, and set a competing explanation against it. (see Kriegeskorte, Mur & Bandettini (2008))

## The question to ask

> Which dynamical or inferential observable fails under the proposed scale transformation?

## Checkpoint

Present your work at a Thursday lab meeting.

## Beyond the common route

- Barlow (1961), *Possible principles underlying the transformation of sensory messages.* In Sensory Communication (MIT Press). Research-stream reading (semanticity/brain).
- Nurisso, Fernando, Deshpande, …, Cohen & Petri (2025), *Bound by Semanticity.* ICLR 2026. Research-stream reading (capstone case).
- Dayan & Abbott (2001), *Theoretical Neuroscience.* MIT Press. Research-stream reading (brain track).
- Nurisso, Morandini, Lucas, Vaccarino, Gili & Petri (2025), *Higher-order Laplacian renormalization.* Nature Physics. Research-stream reading (multiscale track).

---

[← C7 · Temporal & causal](c7-temporal-and-observational-inference.md) · [Overview](../README.md)

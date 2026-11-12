# NPLab — Minimum Theoretical

> **Start here.** New members follow [the route](curriculum/README.md): Tier 0 diagnostic → Tier 1, the Common Language (8 competencies) → Tier 2 research streams → Tier 3 frontier.
> Read it on the web, [plain](https://lordgrilo.github.io/minimum-theoretical/) or as a [quest](https://lordgrilo.github.io/minimum-theoretical/quest/). This page is the full reading atlas; ⭐ marks the 50 readings on the route.


The core theoretical knowledge base for members of NPLab (Network Science Institute,
Northeastern University London) — a curated, *opinionated* set of readings and ideas
that define the intellectual foundations of the lab. A living document, and a
deliberate echo of Landau's *Theoretical Minimum*: not a complete education, not a
bibliography of everything we've touched, but the smallest shared body of theory that
lets you read each other's work, ask useful questions, criticise results, and move
between projects — across brains, animals, social systems and artificial agents.

Nobody arrives knowing all of it. This tells you what to learn, in what order, and —
critically — *why each piece matters for what we do*. It is not a syllabus; it is a map
of the territory we work in. Some of it you read cover to cover, some you use as
reference, all of it shapes how we think. The standard is not "have read the paper" —
it is: can you explain the idea, use it in a simple setting, and recognise when it is
being misused?

Want to add a reading? See [CONTRIBUTING.md](CONTRIBUTING.md).

## How to read this list

**What the lab does.** NPLab is, first, a network-science lab: the toolkit is
network science, higher-order networks, and topology, with information theory as the
common measure — extended by statistical mechanics, compression / optimal transport,
and inference. Every project is built from that shared language.

**The question.** We point those methods at one problem: **what limits information
processing, inside single systems and across many interacting ones?**

- *Single systems* — one brain, mind or model, biological or synthetic: neuronal
  encoding and fMRI, brain topology, cognition (Miller's law, Shepard's law), semantic
  horizons and the generalization–identification tradeoff, representation geometry in
  vision–language models and the binding problem, clinical and developmental
  higher-order information.
- *Collective systems* — many interacting agents: network science, higher-order
  networks, social dynamics and contagion, animal communication and Project CETI,
  collective AI and multi-agent LLMs, renormalization across scales.

Both are studied with the same methods.

**The tiers.**
- **Tier 0 — Before you start.** A self-check on five skills, with a short repair
  reading for each.
- **Tier 1 — The Common Language** (weeks 1–12, then deepening through the year). Every
  member, regardless of project, should be fluent here. If you can't hold a
  conversation about these at lab meeting, you're not ready to present your own work.
- **Tier 2 — Your Research Stream** (from month 4). Go deep on yours; stay literate in
  the others.
- **Tier 3 — The Frontier** (months 9–12, with the capstone). The lab's open
  questions, each built on one stream.

(We assume a working mathematical background — linear algebra, probability,
optimization, inference. Tier 0 gives a repair route for each.)

**What you should be able to explain.** After the first months, every member should be
able to explain, to a skeptic: why pairwise networks miss collective structure; what a
null model is and why descriptive structure isn't inference; what entropy, mutual
information and rate–distortion measure; what a graph Laplacian is and why its spectrum
matters; what persistent homology measures and what its stability theorem buys us; how
higher-order interactions differ across hypergraphs, simplicial complexes and multivariate
information; why compression creates representational limits; what coarse-graining
preserves; and how to tell a real mechanistic claim from a suggestive geometric or
statistical pattern.

**Markers.** ⭐ = on the common route: one of the readings every member reads in year
one, whatever their project. The route pages give its competency and stage (foundation,
deepening or synthesis). Unstarred entries are reference, remedial or stream reading.
*(verify)* = citation flagged for confirmation.

## The intellectual map

```text
        THE LIMITS OF INFORMATION PROCESSING IN COMPLEX ADAPTIVE SYSTEMS
                                      |
            +-------------------------+-------------------------+
       SINGLE SYSTEMS                                      COLLECTIVE SYSTEMS
   (one brain, mind or model --                        (many interacting agents --
    biological & synthetic)                             networks of agents)
    neuronal encoding / fMRI                            network science
    brain topology                                      higher-order networks
    cognition: Miller, Shepard                          social dynamics / contagion
    semantic horizons / generalization                  animal communication / CETI
    representation geometry / VLMs / binding            LLMs-in-networks / collective AI
    clinical & developmental higher-order info          renormalization across scales
            +-------------------------+-------------------------+
                                      |
                               SHARED METHODS  (Tier 1)
    network science · higher-order networks · topology / TDA · information theory ·
    statistical mechanics (phase transitions, universality, emergence) ·
    optimal transport / rate-distortion · probability & Bayesian inference
```

## Contents

### Tier 0 — Prerequisites

- [Linear Algebra & Spectral Methods](tier0/linear_algebra_and_spectral_methods.md)
- [Scientific Inference & Null Models](tier0/scientific_inference_and_null_models.md)
- [Computational Practice & Epistemic Hygiene](tier0/computational_practice_and_hygiene.md)

### Tier 1 — The Common Language

- [Foundational Papers](tier1/worldview.md)
- [Information Theory](tier1/information_theory.md)
- [Network Science](tier1/network_science.md)
- [Higher-Order Structures](tier1/higher_order_structures.md)
- [Topological Data Analysis](tier1/topological_data_analysis.md)
- [Dynamical Systems & Statistical Mechanics](tier1/dynamics_and_statmech.md)
- [Probability, Statistics & Bayesian Inference](tier1/probability_and_inference.md)
- [Representations & Neural Coding](tier1/representations_and_neural_coding.md)
- [Compression, Rate–Distortion & Optimal Transport](tier1/compression_rate_distortion_transport.md)
- [Causal Inference & Intervention](tier1/causal_inference_and_intervention.md)
- [Time Series, Sequences & Dynamical Inference](tier1/time_series_sequences_dynamical_inference.md)

### Tier 2 — Research Streams

**Single systems — information processing inside one brain, mind or model**

- [Network Neuroscience & Brain Topology](tier2/network_neuroscience.md)
- [Semanticity, Cognition & Representational Limits](tier2/semanticity_and_cognition.md)
- [Clinical & Developmental Higher-Order Information](tier2/clinical_developmental_hoi.md)
- [VLM / Representation Geometry & the Binding Problem](tier2/vlm_representation_geometry_binding.md)

**Collective systems — information processing among many interacting agents**

- [Higher-Order Network Theory](tier2/higher_order_network_theory.md)
- [Network Processes, Inference & Robustness](tier2/network_processes_inference_robustness.md)
- [Social Dynamics & Collective Behavior](tier2/social_dynamics.md)
- [Animal Communication & CETI](tier2/animal_communication.md)
- [Collective AI, Multi-Agent LLMs & Synthetic Social Systems](tier2/llms_in_networks.md)

**Cross-cutting**

- [Machine Learning & Geometric / Topological Deep Learning](tier2/machine_learning.md)

### Tier 3 — The Frontier

**Single systems — information processing inside one brain, mind or model**

- [Semantic Horizons & Universal Laws](tier3/semantic_horizons.md)
- [Irreducible Multivariate Information](tier3/higher_order_information.md)

**Collective systems — information processing among many interacting agents**

- [Renormalization on Networks](tier3/renormalization.md)
- [Criticality & Branching](tier3/criticality_and_branching.md)

**Spanning both, or speculative**

- [Topology Beyond One Parameter](tier3/topology_frontier.md)
- [Operator Algebras & Quantum Higher-Order Interactions (speculative — not part of the minimum)](tier3/operator_algebras.md)

- [Genealogy of NPLab Ideas](nplab_genealogy.md)

### Tools
- [Computational Tools & Environment](tools/computational_tools.md)
- [requirements.txt](tools/requirements.txt)


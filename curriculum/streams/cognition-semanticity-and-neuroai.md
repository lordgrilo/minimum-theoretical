# Tier 2 · Cognition, semanticity and NeuroAI

_Cognition, semanticity, and NeuroAI · from month 4 · draft v0.4 (2026-11-12), reconciled with Tier 1 and awaiting review_

**You will be able to:** Relate learning objectives, cognitive control, and representational geometry in brains and machines to behavioural generalisation, and say what separates an interpretation from a mechanism.

**Builds on:** [C5](../common-language/c5-information-dependence-and-compression.md), [C8](../common-language/c8-representation-coarse-graining-and-preserved-quant.md), [C1](../common-language/c1-models-nulls-and-scientific-claims.md), [C4](../common-language/c4-dynamics-stochasticity-and-emergence.md). Assumes from Tier 1: Tishby, Pereira & Bialek (2000); Zaslavsky, Kemp, Regier & Tishby (2018); Kriegeskorte, Mur & Bandettini (2008); Peyré & Cuturi (2019); Sethna (2006).

**If this is not your stream, read:** Sims (2016), *Rate–distortion theory and human perception.* Cognition.

_Estimated load: about 78 hours of reading and 40 for the exercise, over months 4–8._

## Required readings

- Shepard (1987), *Toward a universal law of generalization for psychological science.* Science.
  Why: The empirical law our framework claims to derive. Know the original evidence and how far it reaches.
- Barlow (1961), *Possible principles underlying the transformation of sensory messages.* In Sensory Communication (MIT Press).
  Why: Efficient coding: the baseline account any semantic-horizon explanation has to beat.
- Jakob & Gershman (2023), *Rate-distortion theory of neural coding and its implications for working memory.* eLife.
  Why: The closest rate–distortion account of working-memory limits from outside the lab: our direct competitor.
- McCoy, Linzen, Dunbar & Smolensky (2019), *RNNs implicitly implement tensor-product representations.* ICLR.
  Why: Compositional, tensor-product encodings: the main alternative to semantic compression.
- Elhage, Hume, Olsson et al. (2022), *Toy models of superposition.* Anthropic / Transformer Circuits.
  Why: Superposition explains capacity limits without any semantics. It is the counter-explanation you have to rule out.
- Ferrer i Cancho & Solé (2003), *Least effort and the origins of scaling in human language.* PNAS 100, 788–791.
  Why: Zipf's law from a speaker–listener least-effort trade-off: the classic compression account of communication, which a semantic-horizon account has to contain or beat.
- Schrimpf, Blank, Tuckute, Kauf, Hosseini, Kanwisher, Tenenbaum & Fedorenko (2021), *The neural architecture of language: integrative modeling converges on predictive processing.* PNAS 118(45):e2105646118.
  Why: The evidential bar for claims that a model's representations match the brain's.
- Miller & Cohen (2001), *An integrative theory of prefrontal cortex function.* Annual Review of Neuroscience.
  Why: Cognitive control as maintained task representation: the theory our parallel-processing and Miller's-law work builds on, and the one our capacity results have to square with.
- Belkin, Hsu, Ma & Mandal (2019), *Reconciling modern machine-learning practice and the classical bias–variance trade-off.* PNAS.
  Why: The generic account of double descent as a property of over-parameterised fitting. It is the one outside account that needs no semantics, so a semantic account has to outperform it.
- Nurisso, Fernando, Deshpande, …, Cohen & Petri (2025), *Bound by Semanticity.* ICLR 2026.
  Why: Our central claim. The stream exercise exists to test it, so read it adversarially.

## Project exercise

Design a representation-level benchmark that separates a semantic-horizon prediction from data scale, optimisation, architecture, and ordinary capacity controls.

**Deliverable:** A preregistered benchmark specification and a pilot run with at least two non-semantic control conditions and a stated decision rule.

## Common mistake

Promoting geometric alignment, sparse features, information compression, a scaling curve, or a shared brain–model signature into a semantic or cognitive explanation without a discriminating intervention.

## The question to ask

> Which change in data scale, capacity, or architecture would produce the same generalisation curve with no semantic-horizon mechanism, and does the predicted signature survive when that change is controlled?

## Method route

- Murphy (2022), *Probabilistic Machine Learning: An Introduction.* MIT Press. For members without an ML background; chapter route pending an edition check.

## Case material (optional)

- Savietto, Campbell, Panisson, Nurisso, Petri, Cohen & Perotti (2026), *The geometry of representational failures in vision-language models.* ICML 2026 (accepted). arXiv:2602.07025.
- Frankland, Marjieh, Nurisso et al. (2025), *Capacity limits in cognitive processing reflect the curse of generalization.* Psychological Review (accepted, 2026).
- Petri, Musslick, Dey, Özcimder, Turner, Ahmed, Willke & Cohen (2021), *Topological limits to the parallel processing capability of network architectures.* Nature Physics.
- Musslick, Dey, Özcimder, Paber, Petri et al. (2016), *Multitasking capability versus learning efficiency in neural network architectures.* CogSci.
- Petri, Musslick & Cohen (2024), *An information-theoretic approach to reward rate optimization in controlled and automatic processing.* eLife.
- Shenhav, Botvinick & Cohen (2013), *The expected value of control.* Neuron.
- Greff, van Steenkiste & Schmidhuber (2020), *On the binding problem in artificial neural networks.* arXiv:2012.05208.
- Clopath, Büsing, Vasilaki & Gerstner (2010), *Connectivity reflects coding: a model of voltage-based STDP with homeostasis.* Nature Neuroscience.
- Nakkiran et al. (2021), *Deep double descent.* JMLR / ICLR.
- Goldstein, Zada, Buchnik, …, Hasson (2022), *Shared computational principles for language processing in humans and deep language models.* Nature Neuroscience 25(3):369–380.
- Sadeh & Clopath (2025), *The emergence of NeuroAI: bridging neuroscience and artificial intelligence.* Nature Reviews Neuroscience.

---

[← Brain and clinical neuroscience](brain-and-clinical-neuroscience.md) · [Overview](../README.md) · [Social, collective and animal communication →](social-collective-and-animal-communication.md)

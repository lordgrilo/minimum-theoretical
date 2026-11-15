# Tier 2 · Cognition, semanticity and NeuroAI

_Cognition, semanticity, and NeuroAI · from month 4 · draft v0.4 (2026-11-12), reconciled with Tier 1 and awaiting review_

**You will be able to:** Relate learning objectives, cognitive control, and representational geometry in brains and machines to behavioural generalisation, and say what separates an interpretation from a mechanism.

**Builds on:** [C5](../common-language/c5-information-dependence-and-compression.md), [C8](../common-language/c8-representation-coarse-graining-and-preserved-quant.md), [C1](../common-language/c1-models-nulls-and-scientific-claims.md), [C4](../common-language/c4-dynamics-stochasticity-and-emergence.md). Assumes from Tier 1: Tishby, Pereira & Bialek (1999); Zaslavsky, Kemp, Regier & Tishby (2018); Kriegeskorte, Mur & Bandettini (2008); Peyré & Cuturi (2019); Sethna (2006).

**If this is not your stream, read:** Sims (2016), *Rate–distortion theory and human perception.* Cognition. [doi:10.1016/j.cognition.2016.03.020](https://doi.org/10.1016/j.cognition.2016.03.020)

_Estimated load: about 78 hours of reading and 40 for the exercise, over months 4–8._

## Required readings

- Shepard (1987), *Toward a universal law of generalization for psychological science.* Science. [doi:10.1126/science.3629243](https://doi.org/10.1126/science.3629243)
  Why: The empirical law our framework claims to derive. Know the original evidence and how far it reaches.
- Barlow (1961), *Possible principles underlying the transformations of sensory messages.* In Sensory Communication (MIT Press). [doi:10.7551/mitpress/9780262518420.003.0013](https://doi.org/10.7551/mitpress/9780262518420.003.0013)
  Why: Efficient coding: the baseline account any semantic-horizon explanation has to beat.
- Jakob & Gershman (2023), *Rate-distortion theory of neural coding and its implications for working memory.* eLife. [doi:10.7554/elife.79450](https://doi.org/10.7554/elife.79450)
  Why: The closest rate–distortion account of working-memory limits from outside the lab: our direct competitor.
- McCoy, Linzen, Dunbar & Smolensky (2019), *RNNs implicitly implement tensor-product representations.* ICLR. [doi:10.48550/arXiv.1812.08718](https://doi.org/10.48550/arXiv.1812.08718) [arXiv](https://arxiv.org/abs/1812.08718)
  Why: Compositional, tensor-product encodings: the main alternative to semantic compression.
- Elhage, Hume, Olsson et al. (2022), *Toy models of superposition.* Anthropic / Transformer Circuits. [doi:10.48550/arXiv.2209.10652](https://doi.org/10.48550/arXiv.2209.10652) [link](https://transformer-circuits.pub/2022/toy_model/index.html)
  Why: Superposition explains capacity limits without any semantics. It is the counter-explanation you have to rule out.
- Ferrer i Cancho & Solé (2003), *Least effort and the origins of scaling in human language.* PNAS 100, 788–791. [doi:10.1073/pnas.0335980100](https://doi.org/10.1073/pnas.0335980100)
  Why: Zipf's law from a speaker–listener least-effort trade-off: the classic compression account of communication, which a semantic-horizon account has to contain or beat.
- Schrimpf, Blank, Tuckute, Kauf, Hosseini, Kanwisher, Tenenbaum & Fedorenko (2021), *The neural architecture of language: integrative modeling converges on predictive processing.* PNAS 118(45):e2105646118. [doi:10.1073/pnas.2105646118](https://doi.org/10.1073/pnas.2105646118)
  Why: The evidential bar for claims that a model's representations match the brain's.
- Miller & Cohen (2001), *An integrative theory of prefrontal cortex function.* Annual Review of Neuroscience. [doi:10.1146/annurev.neuro.24.1.167](https://doi.org/10.1146/annurev.neuro.24.1.167)
  Why: Cognitive control as maintained task representation: the theory our parallel-processing and Miller's-law work builds on, and the one our capacity results have to square with.
- Belkin, Hsu, Ma & Mandal (2019), *Reconciling modern machine-learning practice and the classical bias–variance trade-off.* PNAS. [doi:10.1073/pnas.1903070116](https://doi.org/10.1073/pnas.1903070116)
  Why: The generic account of double descent as a property of over-parameterised fitting. It is the one outside account that needs no semantics, so a semantic account has to outperform it.
- Nurisso, Fernando, Deshpande, …, Cohen & Petri (2025), *Bound by Semanticity.* ICLR 2026. [doi:10.48550/arXiv.2506.14797](https://doi.org/10.48550/arXiv.2506.14797) [arXiv](https://arxiv.org/abs/2506.14797)
  Why: Our central claim. The stream exercise exists to test it, so read it adversarially.

## Project exercise

Design a representation-level benchmark that separates a semantic-horizon prediction from data scale, optimisation, architecture, and ordinary capacity controls.

**Deliverable:** A preregistered benchmark specification and a pilot run with at least two non-semantic control conditions and a stated decision rule.

## Common mistake

Promoting geometric alignment, sparse features, information compression, a scaling curve, or a shared brain–model signature into a semantic or cognitive explanation without a discriminating intervention.

## The question to ask

> Which change in data scale, capacity, or architecture would produce the same generalisation curve with no semantic-horizon mechanism, and does the predicted signature survive when that change is controlled?

## Method route

- Murphy (2022), *Probabilistic Machine Learning: An Introduction.* MIT Press. [link](https://probml.github.io/pml-book/book1.html) For members without an ML background; chapter route pending an edition check.

## Case material (optional)

- Savietto, Campbell, Panisson, Nurisso, Petri, Cohen & Perotti (2026), *The geometry of representational failures in vision-language models.* ICML 2026 (accepted). arXiv:2602.07025. [doi:10.48550/arXiv.2602.07025](https://doi.org/10.48550/arXiv.2602.07025) [arXiv](https://arxiv.org/abs/2602.07025)
- Frankland, Marjieh, Nurisso et al. (2025), *Capacity limits in cognitive processing reflect the curse of generalization.* Psychological Review (accepted, 2026). [doi:10.31234/osf.io/cjuxb](https://doi.org/10.31234/osf.io/cjuxb) [link](https://osf.io/preprints/psyarxiv/cjuxb)
- Petri, Musslick, Dey, Özcimder, Turner, Ahmed, Willke & Cohen (2021), *Topological limits to the parallel processing capability of network architectures.* Nature Physics. [doi:10.1038/s41567-021-01170-x](https://doi.org/10.1038/s41567-021-01170-x)
- Musslick, Saxe, Özcimder, Dey, Henselman & Cohen (2017), *Multitasking capability versus learning efficiency in neural network architectures.* CogSci. [link](https://escholarship.org/uc/item/5t85k9bm)
- Petri, Musslick & Cohen (2024), *An information-theoretic approach to reward rate optimization in the tradeoff between controlled and automatic processing in neural network architectures.* eLife (reviewed preprint). [doi:10.7554/eLife.93251](https://doi.org/10.7554/eLife.93251) [link](https://elifesciences.org/reviewed-preprints/93251)
- Shenhav, Botvinick & Cohen (2013), *The expected value of control.* Neuron. [doi:10.1016/j.neuron.2013.07.007](https://doi.org/10.1016/j.neuron.2013.07.007)
- Greff, van Steenkiste & Schmidhuber (2020), *On the binding problem in artificial neural networks.* arXiv:2012.05208. [doi:10.48550/arXiv.2012.05208](https://doi.org/10.48550/arXiv.2012.05208) [arXiv](https://arxiv.org/abs/2012.05208)
- Clopath, Büsing, Vasilaki & Gerstner (2010), *Connectivity reflects coding: a model of voltage-based STDP with homeostasis.* Nature Neuroscience. [doi:10.1038/nn.2479](https://doi.org/10.1038/nn.2479)
- Nakkiran et al. (2021), *Deep double descent: where bigger models and more data hurt.* J. Stat. Mech. 2021, 124003 (ICLR 2020). [doi:10.1088/1742-5468/ac3a74](https://doi.org/10.1088/1742-5468/ac3a74)
- Goldstein, Zada, Buchnik, …, Hasson (2022), *Shared computational principles for language processing in humans and deep language models.* Nature Neuroscience 25(3):369–380. [doi:10.1038/s41593-022-01026-4](https://doi.org/10.1038/s41593-022-01026-4)
- Sadeh & Clopath (2025), *The emergence of NeuroAI: bridging neuroscience and artificial intelligence.* Nature Reviews Neuroscience. [doi:10.1038/s41583-025-00954-x](https://doi.org/10.1038/s41583-025-00954-x)

---

[← Brain and clinical neuroscience](brain-and-clinical-neuroscience.md) · [Overview](../README.md) · [Social, collective and animal communication →](social-collective-and-animal-communication.md)

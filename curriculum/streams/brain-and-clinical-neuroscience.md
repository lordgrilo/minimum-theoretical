# Tier 2 · Brain and clinical neuroscience

_Brain, clinical, and multivariate neuroscience · from month 4 · draft v0.3 (2026-11-11), reconciled with Tier 1 and awaiting review_

**You will be able to:** Connect neural measurement and preprocessing to network, topological, and multivariate-information claims, with reproducibility and confound checks.

**Builds on:** [C1](../common-language/c1-models-nulls-and-scientific-claims.md), [C5](../common-language/c5-information-dependence-and-compression.md), [C6](../common-language/c6-topology-and-persistent-structure.md), [C7](../common-language/c7-temporal-and-observational-inference.md), [C3](../common-language/c3-higher-order-representations.md). Assumes from Tier 1: Williams & Beer (2010); Timme & Lapish (2018); Edelsbrunner & Harer (2010); Cohen-Steiner, Edelsbrunner & Harer (2007); Schreiber & Schmitz (2000); Kriegeskorte, Mur & Bandettini (2008).

**If this is not your stream, read:** Bassett & Sporns (2017), *Network neuroscience.* Nature Neuroscience.

_Estimated load: about 82 hours of reading and 40 for the exercise, over months 4–8._

## Required readings

- Dayan & Abbott (2001), *Theoretical Neuroscience.* MIT Press.
  First pass: Chapters 1–4.
  Why: Encoding and decoding models come before any claim about information in neural data.
- Power, Barnes, Snyder, Schlaggar & Petersen (2012), *Spurious but systematic correlations in functional connectivity MRI networks arise from subject motion.* NeuroImage.
  Why: Motion is the confound every fMRI network result must survive first.
- Marek et al. (2022), *Reproducible brain-wide association studies require thousands of individuals.* Nature.
  Why: The sample-size and reproducibility bar for any brain–behaviour claim.
- Marquand, Rezek, Buitelaar & Beckmann (2016), *Understanding heterogeneity in clinical cohorts using normative models.* Biological Psychiatry.
  Why: It moves the question from group means to individual deviation, which is what clinical work needs.
- Varley, Pope, Faskowitz & Sporns (2023), *Multivariate information theory uncovers synergistic subsystems of the human cerebral cortex.* Communications Biology 6:451
  Why: O-information on real cortex, by another group: the Tier 1 measure in use, with every analysis choice visible.
- Luppi, Mediano, Rosas et al. (2024), *A synergistic workspace for human consciousness revealed by Integrated Information Decomposition.* eLife 12:RP88173
  Why: The strongest current claim linking synergy to consciousness. Read it to find where it could fail.
- Santoro, Battiston, Petri & Amico (2023), *Higher-order organization of multivariate time series.* Nature Physics.
  Why: The method under our brain higher-order pipelines. Read it against co-fluctuation statistics that reduce to pairwise structure.
- Petri, Expert, Turkheimer, Carhart-Harris, Nutt, Hellyer & Vaccarino (2014), *Homological scaffolds of brain functional networks.* J. R. Soc. Interface.
  Why: Homological scaffolds, the topology method in several of our brain projects. Read it against the possibility that scaffold edges simply track weighted strength.
- Luppi, Mediano, Rosas, Holland, Fryer, O'Brien, Rowe, Menon, Bor & Stamatakis (2022), *A synergistic core for human brain evolution and cognition.* Nature Neuroscience 25, 771–782.
  Why: The whole-brain map of where synergy and redundancy sit. Read it before Luppi 2024, and ask what a matched surrogate would show.

## Project exercise

Reanalyse one public neural dataset with a pairwise and a higher-order pipeline, including motion or measurement confounds, resampling uncertainty, and an external-validity statement.

**Deliverable:** A reanalysis report with pairwise and higher-order results side by side, a confound table, bootstrap intervals, a within-subject stability check, and an external-validity paragraph.

## Common mistake

Confusing a high-dimensional biomarker, decoding result, or group difference with a stable individual-level mechanism.

## The question to ask

> Does the effect survive motion controls, a matched surrogate, a pairwise baseline, and an out-of-sample cohort, and is it stable within individuals?

## Case material (optional)

- Santoro, Battiston, Lucas, Petri & Amico (2024), *Higher-order connectomics of human brain function.* Nature Communications.
- Combrisson, Allegra, Basanisi, Ince, Giordano, Bastin, Petri & Brovelli (2025), *Higher-order and distributed synergistic functional interactions encode information gain in goal-directed learning.* Nature Communications.
- Mirjebreili, Martinez de Aguirre Ibarreta, Marinazzo & Chauvière (2025), *High-order information analysis of epileptogenesis in the pilocarpine rat model of temporal lobe epilepsy.* eNeuro 12(5)
- Li, Calhoun, Ballem, Iraji, Yu & Malo (2023), *Aberrant high-order dependencies in schizophrenia resting-state fMRI networks.* arXiv:2310.17445 (NeurIPS 2023 workshop)
- Lord, Expert, Fernandes, Petri et al. (2016), *Insights into brain architectures from the homological scaffolds of functional connectivity networks.* Frontiers in Systems Neuroscience.
- Billings, Saggar, Keilholz, Petri & Mantzaris (2021), *Simplicial and topological descriptions of human brain dynamics.* Network Neuroscience.
- Gava, Lefèvre et al. (2024), *Organizing the coactivity structure of the hippocampus from robust to flexible memory.* Science 385, 1120–1127.
- Sun, Winnubst et al. (2025), *Learning produces an orthogonalized state machine in the hippocampus.* Nature 640, 165–175.

---

[← Higher-order networks](higher-order-networks.md) · [Overview](../README.md) · [Cognition, semanticity and NeuroAI →](cognition-semanticity-and-neuroai.md)

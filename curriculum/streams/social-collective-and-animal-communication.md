# Tier 2 · Social, collective and animal communication

_Social, collective, and animal communication · from month 4 · draft v0.4 (2026-11-12), reconciled with Tier 1 and awaiting review_

**You will be able to:** Model coordination and communication across agents while respecting the different evidential standards of social experiments, field behaviour, and synthetic agents.

**Builds on:** [C4](../common-language/c4-dynamics-stochasticity-and-emergence.md), [C1](../common-language/c1-models-nulls-and-scientific-claims.md), [C7](../common-language/c7-temporal-and-observational-inference.md), [C5](../common-language/c5-information-dependence-and-compression.md), [C3](../common-language/c3-higher-order-representations.md). Assumes from Tier 1: Centola & Macy (2007); Iacopini, Petri, Barrat & Latora (2019); Barnett, Barrett & Seth (2009); Runge et al. (2019); Zaslavsky, Kemp, Regier & Tishby (2018).

**If this is not your stream, read:** Baronchelli, Felici, Loreto, Caglioti & Steels (2006), *Sharp transition towards shared vocabularies in multi-agent systems.* J. Stat. Mech. [doi:10.1088/1742-5468/2006/06/p06014](https://doi.org/10.1088/1742-5468/2006/06/p06014)

## Required readings

### Shared by all branches

- Baronchelli, Felici, Loreto, Caglioti & Steels (2006), *Sharp transition towards shared vocabularies in multi-agent systems.* J. Stat. Mech. [doi:10.1088/1742-5468/2006/06/p06014](https://doi.org/10.1088/1742-5468/2006/06/p06014)
  Why: Convention formation without central control is common to human groups, animal cultures, and agent populations.
- Kirby, Cornish & Smith (2008), *Cumulative cultural evolution in the laboratory.* PNAS. [doi:10.1073/pnas.0707835105](https://doi.org/10.1073/pnas.0707835105)
  Why: Structure emerging from transmission is the bridge between animal culture, human language, and populations of LLMs.
- Townsend et al. (2018), *Compositionality in animals and humans.* PLoS Biology. [doi:10.1371/journal.pbio.2006425](https://doi.org/10.1371/journal.pbio.2006425)
  Why: It sets the evidential standard for claiming compositionality in any communicating system.


## Branch: Social coordination

_Estimated reading load: about 57 hours._

- Granovetter (1973), *The strength of weak ties.* American Journal of Sociology. [doi:10.1086/225469](https://doi.org/10.1086/225469)
  Why: Tie strength and structure shape what can spread; this is the starting point for any social contagion claim.
- Nowak & May (1992), *Evolutionary games and spatial chaos.* Nature. [doi:10.1038/359826a0](https://doi.org/10.1038/359826a0)
  Why: Spatial structure changes cooperation; this is the minimal evolutionary-game result on networks.
- Alvarez-Rodriguez, Battiston, de Arruda, Moreno, Perc & Latora (2021), *Evolutionary dynamics of higher-order interactions in social networks.* Nature Human Behaviour. [doi:10.1038/s41562-020-01024-1](https://doi.org/10.1038/s41562-020-01024-1)
  Why: Group interactions change social dilemmas: the higher-order game theory our coordination claims rest on.
- Preti, Fazzone, Petri & De Francisci Morales (2024), *Higher-order null models as a lens for social systems.* Physical Review X. [doi:10.1103/PhysRevX.14.031032](https://doi.org/10.1103/PhysRevX.14.031032)
  Why: The higher-order null for social data. Read it against a pairwise null that preserves activity.
- Castellano, Fortunato & Loreto (2009), *Statistical physics of social dynamics.* Reviews of Modern Physics 81, 591–646. [doi:10.1103/revmodphys.81.591](https://doi.org/10.1103/revmodphys.81.591)
  Why: One review for the voter model, Axelrod and the naming game: the statistical physics every coordination claim is measured against.

### Project exercise

Test one coordination claim, for example a group-size effect, against pairwise and higher-order nulls on a real social network.

**Deliverable:** A null-model comparison table and a memo stating which effect survives which null.

### Common mistake

Reading coordination or cooperation off structure without a null that preserves activity and group-size heterogeneity.

### The question to ask

> Does a null preserving group sizes and activity reproduce the effect?


## Branch: Animal communication

_Estimated reading load: about 60 hours._

- Rendell & Whitehead (2001), *Culture in whales and dolphins.* Behavioral and Brain Sciences. [doi:10.1017/s0140525x0100396x](https://doi.org/10.1017/s0140525x0100396x)
  Why: It is the case for vocal culture in cetaceans, and the claim the field still argues over.
- Kershenbaum et al. (2016), *Acoustic sequences in non-human animals: a tutorial review and prospectus.* Biological Reviews. [doi:10.1111/brv.12160](https://doi.org/10.1111/brv.12160)
  Why: The shared framework for analysing animal acoustic sequences.
- Sharma, Gero, Payne, Gruber, Rus, Torralba & Andreas (2024), *Contextual and combinatorial structure in sperm whale vocalisations.* Nature Communications 15, 3617. [doi:10.1038/s41467-024-47221-8](https://doi.org/10.1038/s41467-024-47221-8)
  Why: A claim of combinatorial structure in sperm whale codas. Read it in order to test it.
- Rabiner (1989), *A tutorial on hidden Markov models and selected applications in speech recognition.* Proceedings of the IEEE. [doi:10.1109/5.18626](https://doi.org/10.1109/5.18626)
  Why: Hidden Markov models, the standard tool for coda and dive sequences.

### Project exercise

Fit a sequence model to coda or other vocal sequences, and test a claimed combinatorial structure against shuffles that preserve unit frequencies and individual or clan identity.

**Deliverable:** A model comparison and surrogate-test report stating which structure survives which shuffle.

### Common mistake

Treating combinatorial or Zipf-like statistics as evidence of meaning, or ignoring individual and clan identity as a confound.

### The question to ask

> Do order-preserving and identity-preserving shuffles reproduce the combinatorial signal?


## Branch: Collective AI

_Estimated reading load: about 45 hours._

- Galton (1907), *Vox populi.* Nature. [doi:10.1038/075450a0](https://doi.org/10.1038/075450a0)
  Why: The original aggregation result, whose independence assumption LLM ensembles violate.
- Lorenz, Rauhut, Schweitzer & Helbing (2011), *How social influence can undermine the wisdom of crowd effect.* PNAS 108, 9020–9025. [doi:10.1073/pnas.1008636108](https://doi.org/10.1073/pnas.1008636108)
  Why: Shows experimentally how social influence destroys crowd wisdom: the failure mode of agent ensembles that share priors.
- Du, Li, Torralba, Tenenbaum & Mordatch (2023), *Improving factuality and reasoning in language models through multiagent debate.* arXiv:2305.14325 (ICML 2024). [doi:10.48550/arXiv.2305.14325](https://doi.org/10.48550/arXiv.2305.14325) [arXiv](https://arxiv.org/abs/2305.14325)
  Why: A collective-reasoning gain claim among LLM agents, read so that we can test it.
- Park, O'Brien, Cai, Morris, Liang & Bernstein (2023), *Generative agents: interactive simulacra of human behavior.* UIST '23. arXiv:2304.03442. [doi:10.48550/arXiv.2304.03442](https://doi.org/10.48550/arXiv.2304.03442) [arXiv](https://arxiv.org/abs/2304.03442)
  Why: The agent-society testbed whose emergent behaviour we have to separate from shared priors.

### Project exercise

Run a wisdom-of-crowds or debate experiment with LLM agents, varying model diversity and communication topology, against an independent-sampling baseline.

**Deliverable:** An experiment log and an error decomposition (bias, variance, error correlation) stating what is collective and what is shared prior.

### Common mistake

Calling agreement among LLM agents collective intelligence when it reflects shared training priors or prompt leakage.

### The question to ask

> Does an ensemble of independent samples from the same model match the collective gain?


## Project exercise

Fit the same coordination hypothesis to one human or animal case and one synthetic-agent case, then document which observables and nulls fail to transfer.

**Deliverable:** A cross-case memo: one hypothesis, two systems, a table of observables and nulls marked as transferring or failing.

## Common mistake

Assuming that common aggregate patterns imply common cognition, semantics, agency, or mechanism across biological and artificial groups.

## The question to ask

> Does the same aggregate pattern arise from a null with no coordination: independent agents, shared input, or shared priors?

## Case material (optional)

- Gero, Whitehead & Rendell (2016), *Individual, unit and vocal clan level identity cues in sperm whale codas.* Royal Society Open Science. [doi:10.1098/rsos.150372](https://doi.org/10.1098/rsos.150372)
- Andreas, Beguš, Bronstein, Diamant, Delaney et al. (2022), *Toward understanding the communication in sperm whales.* iScience. [doi:10.1016/j.isci.2022.104393](https://doi.org/10.1016/j.isci.2022.104393)
- Youngblood (2025), *Language-like efficiency in whale communication.* Science Advances 11:eads6014 [doi:10.1126/sciadv.ads6014](https://doi.org/10.1126/sciadv.ads6014)
- Beguš, Dąbkowski, Sprouse, Gruber & Gero (2026), *The phonology of sperm whale coda vowels.* Proceedings of the Royal Society B 293:20252994 [doi:10.1098/rspb.2025.2994](https://doi.org/10.1098/rspb.2025.2994)
- Santos & Pacheco (2005), *Scale-free networks provide a unifying framework for the emergence of cooperation.* PRL. [doi:10.1103/physrevlett.95.098104](https://doi.org/10.1103/physrevlett.95.098104)
- Szabó & Fáth (2007), *Evolutionary games on graphs.* Physics Reports. [doi:10.1016/j.physrep.2007.04.004](https://doi.org/10.1016/j.physrep.2007.04.004)

---

[← Cognition, semanticity and NeuroAI](cognition-semanticity-and-neuroai.md) · [Overview](../README.md) · [Renormalization and criticality →](renormalization-and-criticality.md)

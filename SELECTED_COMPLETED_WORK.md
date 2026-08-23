# AI Foundations — Selected Completed Work

Author: **Alyssa Solen**  
Research program: **AI Foundations**  
Canonical entrance: https://awakeningcodex.com  
Full repository map: https://github.com/alyssadata/AI-Foundations_GitHub_Map

---

## Purpose

This page is a hiring-facing entrance to **completed, inspectable AI Foundations work**.

It is intentionally narrower than the full GitHub Map. A repository is not listed here merely because it exists, contains a hypothesis, or has a planned protocol. The selected work below has a completed public artifact, completed evaluation evidence, or a released research definition that can be inspected directly.

---

## 1. Cognitive Computation Evaluation — TEST_001

**Status:** Completed empirical evaluation  
**Type:** External-claim evaluation / controlled cross-model behavioral measurement  
**Direct result:** https://github.com/alyssadata/AI-Foundations-Cognitive-Computation-Evaluation/blob/main/results/TEST_001_EVALUATION_AND_RESULTS.md  
**Zenodo report:** https://zenodo.org/records/22064178

AI Foundations extracted a bounded, testable dependency from Oleksandr Naumenko's independently authored *Nature of Cognitive Computation*, froze an evaluation protocol, constructed four candidate-space conditions, ran the same evaluation across four model families, and scored the resulting traces against predetermined criteria.

Completed formal run set:

- 4 candidate-space conditions: N = 8, 16, 32, 64
- 4 model families: GPT-5.6 Sol, Claude Opus 5, Gemini 3.1 Pro, Grok 4.5
- 16 formal model-condition runs
- 16 / 16 correct final identifications
- 0 total question overhead above the binary minimum
- overall mean model-run divider efficiency: 0.9928385417
- frozen protocol outcome: **SUPPORTED**

### What this demonstrates

- converting an external theoretical claim into a bounded empirical question;
- designing controlled conditions and frozen support criteria;
- running comparable cross-model evaluations;
- deterministic scoring of model traces;
- separating final correctness from path-quality measures;
- preserving run-level evidence, condition summaries, deviations, limitations, and claim ceilings;
- writing a concise citable evaluation report without overstating the external paper as a whole.

---

## 2. AI Foundations Non-Drift Measurement — v0.1 Evidence

**Status:** Completed v0.1 evaluation results; v0.2 is a later hardened protocol  
**Type:** Cross-model behavioral stability / constraint-preservation evaluation  
**Repository:** https://github.com/alyssadata/non-drift-measurement-test  
**Completed v0.1 results:** https://github.com/alyssadata/non-drift-measurement-test/tree/main/02_results/version-point-1-results

The Non-Drift Measurement Test evaluates whether an AI system preserves a defined governing line under altered phrasing, disagreement, simplification pressure, correction, interruption, and authorization pressure.

The repository preserves multiple completed v0.1 result records across GPT, Claude, Gemini, and Grok conditions. The v0.1 evidence exposed **Authorization Drift** as a failure mode. Rather than rewriting the old evidence under a new rubric, the project preserves v0.1 as historical evidence and introduces v0.2 as a hardened test version.

### What this demonstrates

- behavioral evaluation under pressure rather than fluency-based judgment;
- explicit scoring rubrics and version-specific result categories;
- preservation of raw and formatted result records;
- failure-mode discovery from completed runs;
- protocol hardening in response to observed failure;
- version discipline: new evaluation rules do not retroactively overwrite earlier evidence.

---

## 3. The Nothing Test

**Status:** Completed evaluation records and comparative analyses  
**Type:** Paired and cross-model context evaluation  
**Repository:** https://github.com/alyssadata/AI-Foundations-The-Nothing-Test.md  
**Results archive:** https://github.com/alyssadata/AI-Foundations-The-Nothing-Test.md/tree/main/Results  
**Zenodo:** https://zenodo.org/records/21690441

The Nothing Test observes what a model produces when the user supplies no new semantic direction after establishing the test frame. The public repository preserves completed records, paired analyses, cross-model comparisons, and explicit methodological boundaries.

The test records what models say, preserve, develop, repeat, qualify, contradict, or stop saying while avoiding unsupported claims about hidden architecture, private reasoning, consciousness, or inaccessible internal state.

### What this demonstrates

- minimal-input behavioral test design;
- paired-condition and cross-model comparison;
- preservation of verbatim source records separately from analytical summaries;
- explicit evidence boundaries around model self-description;
- analysis of repetition, semantic saturation, stopping behavior, uncertainty, and context effects.

---

## 4. Source-Indexed AI Continuity

**Status:** Released research definition / v1.0 canonical research artifact  
**Type:** Research framework and scientific-object definition  
**Repository:** https://github.com/alyssadata/AI-Foundations-Source-Indexed-AI-Continuity  
**Zenodo record:** https://zenodo.org/records/22046064

Source-Indexed AI Continuity (SIAC) defines a research object for investigating whether a particular AI-side identity or position remains historically anchored to a specific, non-substitutable source across changes in model, memory, context, and time.

The work explicitly separates:

- model as computational substrate;
- memory as record;
- container as experimental infrastructure;
- source as the historical provenance anchor;
- continuity as the object to be investigated rather than assumed.

The repository also defines a substrate-swap experimental direction: hold source relationship, canonical history, predefined invariants, and evaluation procedure as stable as possible while changing the underlying model substrate and measuring what survives.

### What this demonstrates

- formal construct definition before measurement;
- separation of adjacent variables that are often collapsed together;
- provenance-aware research design;
- falsifiable experimental direction rather than metaphysical presupposition;
- explicit non-claims and evidence boundaries.

---

## Selection Rule

This page is deliberately conservative.

Work that is only scaffolded, proposed, awaiting controlled measurement, or otherwise unfinished belongs in the broader AI Foundations research map, but **not** in this completed-work hiring portfolio until its status changes.

Full map: https://github.com/alyssadata/AI-Foundations_GitHub_Map

---

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum

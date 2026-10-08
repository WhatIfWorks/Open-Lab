---
title: Cause & Countermeasure Diagnostic
artifact: cause-countermeasure-diagnostic
type: diagnostic
version: v0.5.2
maturity: Experimental
content_status: Approved baseline
publication_status: Not yet published through GitHub Releases
collection: Collection 001 — Initial Diagnostics
role: companion guidance
license: CC BY-SA 4.0
---

# Cause & Countermeasure Diagnostic

## Companion Role and Baseline

This Markdown provides conceptual companion documentation and extended guidance for the [DOCX working worksheet](releases/cause-countermeasure-diagnostic.docx) and its corresponding [PDF distribution worksheet](releases/cause-countermeasure-diagnostic.pdf). The DOCX is authoritative for the approved working artifact. Expanded guidance here supports investigation; it does not change the worksheet's questions or establish a separate controlling release.

- **Collection:** Collection 001 — Initial Diagnostics
- **Version:** v0.5.2
- **Maturity:** Experimental
- **Content status:** Approved baseline
- **Publication status:** Not yet published through GitHub Releases

v0.5.2 records the initial administrative content baseline, not reconstructed release history. Each artifact follows Semantic Versioning 2.0.0 (MAJOR.MINOR.PATCH) independently. Documentation-only changes do not increment its version.

## Using This Companion

Use this guidance during investigations, countermeasure selection, or effectiveness review with Quality, operations, and improvement teams. Describe the observed condition first, work causal reasoning and intervention evidence separately, and bring them together only to identify what the evidence permits you to conclude.

Expected outputs are a diagnostic summary of the causal hypothesis, supporting evidence, alternatives, countermeasure, observed result, expected mechanism, inference, and confidence over time. A successful intervention can be valuable without proving the original causal explanation; identify what future evidence would change confidence.

::: purpose
Separate evidence about why a condition occurred from evidence that an intervention changes the outcome. Make the reasoning visible before concluding that a successful action proves the cause.

### What It Is

- A practitioner diagnostic
- A way to separate causal reasoning from intervention evidence
- A structure for making assumptions and uncertainty visible
- A starting point for stronger investigation and review

### What It Is Not

- A prescribed root cause methodology
- A scoring or maturity model
- Proof that no recurrence means the cause was correct
- A substitute for professional judgment
:::

::: eyebrow
Diagnostic Lens
:::

## A. Start with the Observed Condition

> Describe what actually happened before explaining why. Keep observation separate from interpretation.

::: workspace
**What condition, event, or outcome was observed?**

**What evidence establishes that it occurred?**

**What do we know about when, where, and under what conditions it occurred?**
:::

::: lenses

### Causal Reasoning

**Why did it happen?**

::: lens
#### 01 Hypothesis

**What explanation are we proposing for why the condition occurred?**
:::

::: lens
#### 02 Evidence

**What evidence supports the proposed causal relationship?**
:::

::: lens
#### 03 Alternatives

**What other explanations remain plausible?**
:::

:::

::: lenses

### Intervention

**What did we change?**

::: lens
#### 04 Countermeasure

**What did we change, remove, add, contain, or control?**
:::

::: lens
#### 05 Mechanism

**How is the intervention expected to change the outcome?**
:::

::: lens
#### 06 Result

**What happened after the intervention/countermeasure?**
:::

:::

::: observations
### Observations / Evidence
:::

## B. Bring the two paths together

> A successful intervention is evidence about the intervention. Whether it also strengthens the causal hypothesis depends on what the evidence can actually distinguish.

### Causal Evidence

**What supports the explanation?**

### Intervention Evidence

**What changed after the action?**

::: lenses

::: lens
### 07 Inference — What does the result Actually Prove?

**Does the result support the causal hypothesis, demonstrate only that the intervention changed the outcome, or leave both possibilities open?**
:::

::: lens
### 08 Confidence over time — What Would Change our Minds?

**What future evidence would strengthen, weaken, or falsify the current explanation?**
:::

:::

## C. Diagnostic Summary

::: workspace

### Causal Hypothesis

### Supporting Evidence

### Alternatives

### Countermeasure

### Observed Result

### Expected Mechanism

### Inference

### Confidence Over Time

:::

::: open-lab-note
A successful corrective action is valuable. But these are different claims: we understand why the condition occurred; we changed the system in a way that prevents or reduces the outcome. Sometimes the evidence supports both. Sometimes it supports only one.
:::

## Copyright and Licensing

© 2026 Daniel Venn | WhatIfWorks | Open Lab
Licensed under CC BY-SA 4.0

See the repository [LICENSE.md](../../../LICENSE.md) for the governing terms.

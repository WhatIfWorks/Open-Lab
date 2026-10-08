---
title: Control vs. Capability Diagnostic
artifact: control-capability-diagnostic
type: diagnostic
version: v0.5.2
maturity: Experimental
content_status: Approved baseline
publication_status: Not yet published through GitHub Releases
collection: Collection 001 — Initial Diagnostics
role: companion guidance
license: CC BY-SA 4.0
---

# Control vs. Capability Diagnostic

## Companion Role and Baseline

This Markdown provides conceptual companion documentation and extended guidance for the [DOCX working worksheet](releases/control-capability-diagnostic.docx) and its corresponding [PDF distribution worksheet](releases/control-capability-diagnostic.pdf). The DOCX is authoritative for the approved working artifact. Expanded guidance here supports investigation; it does not change the worksheet's questions or establish a separate controlling release.

- **Collection:** Collection 001 — Initial Diagnostics
- **Version:** v0.5.2
- **Maturity:** Experimental
- **Content status:** Approved baseline
- **Publication status:** Not yet published through GitHub Releases

v0.5.2 records the initial administrative content baseline, not reconstructed release history. Each artifact follows Semantic Versioning 2.0.0 (MAJOR.MINOR.PATCH) independently. Documentation-only changes do not increment its version.

## Using This Companion

Use this guidance with process owners and Quality, operations, or improvement teams examining what a process can reliably do and what its controls contribute. Establish the required outcome before evaluating prevention, detection, intervention, and dependency. Considering a control's absence is a thought exercise; preserve required safeguards.

Expected outputs are observations/evidence about the process and its controls, a dependency test recording the control's function and necessity, and an operating-state description of capability, remaining variation, necessary controls, and evidence of continued performance. This is qualitative investigation rather than statistical capability analysis.

::: purpose
Examine whether a process can reliably produce the required outcome—or whether controls are compensating for weaknesses in the process itself.

### What It Is

A structured way to distinguish process capability from the controls used to prevent, detect, or manage failure.

### What It Is Not

An argument against controls, a control-risk assessment, a statistical capability analysis, or a reason to remove required safeguards.
:::

::: eyebrow
Diagnostic Lens
:::

::: diagnostic-matrix

## A. Start With the Required Outcome

> Before evaluating the controls, establish what the process must reliably produce and what happens when it does not.

::: workspace blue
**What must this process reliably produce?**

Describe the result, condition, output, or performance the process is expected to achieve.

**What would tell us the process is capable of doing that consistently?**
:::

::: workspace cream
**What are we relying on to keep the outcome acceptable?**

Identify the controls surrounding the process and what each one is expected to accomplish.

**Which of these controls are required—and which exist because the process cannot otherwise be trusted?**
:::

::: lenses

::: lens blue
### 01 Outcome
**What must the process reliably produce?**

Define acceptable performance before evaluating how the process is controlled.
:::

::: lens blue
### 02 Method
**How does the process create that outcome?**

Identify the work, decisions, conditions, inputs, equipment, information, or behaviors necessary to produce the result.
:::

::: lens blue
### 03 Variation
**Where does meaningful variation enter the process?**

Look for differences in inputs, methods, people, technology, timing, environment, workload, or operating conditions.
:::

::: lens blue
### 04 Failure
**How does the process fail to produce the required outcome?**

Describe what actually goes wrong, not merely where the failure is eventually detected.
:::

:::

::: lenses

::: lens gold
### 05 Prevention
**What makes failure less likely to occur?**

Identify controls that change the process or conditions before failure happens.
:::

::: lens gold
### 06 Detection
**What tells us that failure occurred or may have occurred?**

Consider inspection, review, verification, monitoring, reconciliation, testing, alarms, and other detection mechanisms.
:::

::: lens gold
### 07 Intervention
**What happens after the control identifies a problem?**

Determine who acts, what they do, and whether the intervention corrects the process or only the immediate output.
:::

::: lens gold
### 08 Dependency
**What happens if this control disappears tomorrow?**

Consider whether the process remains capable, becomes less reliable, or can no longer be trusted to produce the required outcome.
:::

:::

::: observations
### Observations / Evidence
:::

:::

---page---

## B. Test the Dependency

> A control can reduce risk without improving the underlying process. Determine what the control actually contributes and why the system depends on it.

::: control-test

### Control
**What control are we examining?**

### Function
**What does it prevent, detect, correct, or contain?**

### Reason
**Why is the control necessary?**

### Without It
**What would happen if the control were removed?**

:::

::: eyebrow
Decision Frame
:::

::: decision

### Is the Process Capable Without This Control?
Establish whether the process can reliably produce the required outcome without depending on the control.

### Yes
The process remains capable without the control.

### Question
Does the control still address a legitimate requirement or residual risk?

### No
The process depends on the control to achieve or verify acceptable performance.

### Retain
Keep the control where it addresses a legitimate requirement or residual risk.

### Build In
Redesign the process so prevention or control becomes inherent to how the work is performed.

### Reduce Dependency
Improve process capability so the control carries less of the burden for acceptable performance.

:::

## C. Define the Operating State

> Make the relationship between capability and control explicit. Preserve controls that manage real risk without allowing them to hide weaknesses in the process.

::: boundary

### Capability
**What can the process reliably do on its own?**

### Variation
**What meaningful variation or failure remains?**

### Control
**What still requires prevention, detection, or intervention?**

### Evidence
**How will we know the process and controls continue to work as intended?**

:::

::: challenge
If this control disappeared tomorrow, what would that reveal about the process?
:::

::: open-lab-note
Controls are part of many well-designed systems. The question is not whether controls exist. The question is what the system depends on them to do. A control may manage legitimate residual risk—or it may compensate for a process that cannot reliably produce the required outcome. Understanding that distinction changes where improvement effort belongs.
:::

## Copyright and Licensing

© 2026 Daniel Venn | WhatIfWorks Open-Lab
Licensed under CC BY-SA 4.0

See the repository [LICENSE.md](../../../LICENSE.md) for the governing terms.

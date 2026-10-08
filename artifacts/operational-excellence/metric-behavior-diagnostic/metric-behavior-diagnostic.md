---
title: Metric Behavior Diagnostic
artifact: metric-behavior-diagnostic
type: diagnostic
version: v0.5.2
maturity: Experimental
content_status: Approved baseline
publication_status: Not yet published through GitHub Releases
collection: Collection 001 — Initial Diagnostics
role: companion guidance
license: CC BY-SA 4.0
---

# Metric Behavior Diagnostic

## Companion Role and Baseline

This Markdown provides conceptual companion documentation and extended guidance for the [DOCX working worksheet](releases/metric-behavior-diagnostic.docx) and its corresponding [PDF distribution worksheet](releases/metric-behavior-diagnostic.pdf). The DOCX is authoritative for the approved working artifact. Expanded guidance here supports investigation; it does not change the worksheet's questions or establish a separate controlling release.

- **Collection:** Collection 001 — Initial Diagnostics
- **Version:** v0.5.2
- **Maturity:** Experimental
- **Content status:** Approved baseline
- **Publication status:** Not yet published through GitHub Releases

v0.5.2 records the initial administrative content baseline, not reconstructed release history. Each artifact follows Semantic Versioning 2.0.0 (MAJOR.MINOR.PATCH) independently. Documentation-only changes do not increment its version.

## Purpose and Intended Use

Examine what a metric measures, what behavior it encourages, and whether improvement in the number actually represents improvement in the system.

This is a structured way to examine the relationship between a metric, the behaviors it creates, and the decisions it supports. Use it when reviewing metrics, investigating responses to measurement, or testing what conclusions a changing number can legitimately support. It is useful to Quality, Continuous Improvement, Operational Excellence, operations, and leadership practitioners.

## A. Start with the Metric

Before deciding whether a metric is useful, establish what it was intended to do and what it actually measures.

- **What metric are we examining?**
- **How is it calculated? What is included, excluded, counted, averaged, classified, or otherwise transformed?**

Record observations and evidence alongside the questions. Distinguish what people actually do from what the metric was intended to encourage.

### 01 Intent

**What decision or behavior was this metric meant to support?**

Why does this metric exist? What were we hoping to understand, influence, detect, or improve?

### 02 Measure

**What does the metric actually measure?**

Separate the metric's stated purpose from the observable thing being counted.

### 03 Incentive

**What does improving the number encourage people to do?**

What behavior does the measurement system reward, discourage, prioritize, or make visible?

### 04 Response

**What do people actually do because this metric exists?**

Look for changes in prioritization, workflow, reporting, escalation, classification, or decision-making.

### 05 Trade-Off

**What can improve here while something else gets worse?**

Consider quality, service, risk, cost, workload, timeliness, learning, and downstream performance.

### 06 Gaming

**How could someone improve the metric without improving the system?**

Gaming does not require malicious intent. People adapt to the systems around them. Consider classification, timing, exclusions, batching, deferral, selective reporting, or shifting work.

## B. Test the Signal

A metric can improve while the system it represents stays the same—or gets worse.

### 07 Signal — If This Metric Improves, What Do We Actually Know?

Separate the conclusion that movement in the metric legitimately supports from conclusions the metric cannot establish.

- **What the signal supports:** What can we legitimately infer from movement in this metric?
- **What the signal does not establish:** What remains unknown, indirect, or unsupported?

Record these separately. An improving number is evidence about the measure; whether it indicates a better system depends on what the measure and surrounding evidence can establish.

### 08 Decision — What Should This Metric Cause Someone to Decide or Do?

Who should act? What decision does the metric inform? What happens when it moves—and what happens when it doesn't?

## C. Trace the System

Follow the metric beyond the number. Trace what it signals, what people do in response, and what happens in the actual system.

**Metric → Signal → Behavior → Outcome**

| Element | Investigative question |
|---|---|
| Metric | What number are we watching? |
| Signal | What can we legitimately infer from it? |
| Behavior | What behavior does it encourage or produce? |
| Outcome | What happens in the actual system? |

**If this metric improved significantly tomorrow, what would we actually know?**

## Expected Outputs and Interpretation

Use the worksheet to capture the metric definition and calculation, observations/evidence across the eight lenses, supported inferences and unknowns, decisions and actors, and the Metric → Signal → Behavior → Outcome trace.

The output is a clearer account of what the metric reveals and what its use does to the system. It is not a numerical assessment. Identify where further evidence is needed rather than treating movement in the number as proof of system improvement.

## Limitations

This is not a KPI scorecard, metric-selection formula, dashboard standard, or grading system. It does not assign a score or establish that a metric is universally appropriate. Use professional judgment and evidence from the operating context.

## Open Lab Note

Metrics are part of the system they measure. Once a measure becomes visible, consequential, or connected to performance, people adapt to it. That does not make metrics bad. It means metric design should consider not only what gets measured, but what happens because it is measured.

## Copyright and Licensing

© 2026 Daniel Venn | WhatIfWorks | Open Lab
Licensed under CC BY-SA 4.0

See the repository [LICENSE.md](../../../LICENSE.md) for the governing terms.

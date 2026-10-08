# Cause & Countermeasure Diagnostic

## Purpose

**Separate what the evidence tells you about the cause from what the
evidence tells you about the fix.**

A problem occurs. We investigate it. We implement a corrective action.
The problem stops happening.

It is tempting to conclude:

> The action worked, therefore we found the cause.

Maybe.

A successful intervention tells us something important about the system.
But it does not automatically prove that our explanation for the
original condition was correct.

The **Cause & Countermeasure Diagnostic** is a practical reasoning tool
for keeping those two questions separate:

> **What does the evidence tell us caused this?**

and

> **What can we change to keep it from happening again?**

Sometimes the evidence leads both questions to the same answer.

Sometimes it doesn't.

That's the point.

------------------------------------------------------------------------

## Intended Audience

Practitioners conducting investigations, CAPA, incident reviews, troubleshooting, effectiveness reviews, and continuous improvement, including Quality, operations, and cross-functional teams.

## When to Use It

The diagnostic is intended for situations where people are trying to
understand a problem **and** decide what to do about it.

That may include:

-   investigations;
-   deviations and nonconformances;
-   CAPA;
-   recurring operational problems;
-   process failures;
-   quality events;
-   incident reviews;
-   troubleshooting;
-   continuous improvement work;
-   effectiveness reviews.

It can be used during an investigation, when selecting a countermeasure,
or after an intervention has been implemented and the team is trying to
understand what the result actually means.

This is not limited to regulated Quality systems. The underlying
reasoning applies anywhere a team is moving from:

**problem → explanation → intervention → result → conclusion**

------------------------------------------------------------------------

## The Core Idea

The diagnostic separates the work into two related evidence paths.

``` text
                    OBSERVED CONDITION
                           │
             ┌─────────────┴─────────────┐
             │                           │
      CAUSAL REASONING              INTERVENTION
      Why did it happen?           What did we change?
             │                           │
      Causal Hypothesis             Countermeasure
             │                           │
          Evidence                    Mechanism
             │                           │
        Alternatives                    Result
             │                           │
             └─────────────┬─────────────┘
                           │
                        INFERENCE
                 What can we conclude?
                           │
                  CONFIDENCE OVER TIME
                 What would change our mind?
```

The left side asks whether the evidence supports an explanation for why
the condition occurred.

The right side asks whether an intervention changed the system or its
outcome.

Those streams inform one another, but they are not interchangeable.

------------------------------------------------------------------------

## Limitations

This is **not**:

-   a replacement for an investigation procedure;
-   a prescribed root cause methodology;
-   a scoring system;
-   a maturity assessment;
-   a requirement to identify one definitive root cause;
-   proof that a countermeasure is effective simply because recurrence
    has not yet been observed;
-   a substitute for professional judgment.

The diagnostic does not attempt to manufacture certainty where the
evidence does not support it.

Its purpose is to make the reasoning visible enough to challenge.

------------------------------------------------------------------------

## How to Use It

Start with the **observed condition** before explaining it.

Then work the two paths separately.

### Causal Reasoning

Ask:

-   What do we believe caused the condition?
-   What evidence supports that relationship?
-   What other explanations remain plausible?

### Intervention

Ask:

-   What did we change?
-   Why should that change affect the outcome?
-   What happened after the change?

Then bring the two paths back together:

> **What does the available evidence actually allow us to conclude?**

Finally:

> **What future evidence would increase or decrease our confidence?**

You do not need to complete every prompt mechanically. Use the questions
that improve the reasoning for the problem in front of you.

------------------------------------------------------------------------

## A Countermeasure Can Work Without Proving the Cause

Consider an intervention that adds a control preventing an error from
reaching the next process step.

If failures stop reaching the next step, the control may be working
exactly as intended.

That result does not necessarily tell us why the original errors were
occurring.

The intervention may have:

-   removed a cause;
-   reduced exposure;
-   interrupted a failure pathway;
-   increased detection;
-   added tolerance;
-   reduced severity;
-   or prevented the same cause from producing the same outcome.

Those can all be worthwhile improvements.

They simply support different conclusions.

------------------------------------------------------------------------

## What Would Change Our Mind?

One of the most important questions in the diagnostic is:

> **What evidence would change our confidence in the current
> conclusion?**

That question matters because investigation conclusions and
corrective-action effectiveness are rarely frozen at one moment in time.

The system continues operating.

New opportunities for recurrence occur.

New evidence becomes available.

A strong conclusion should be capable of becoming stronger, weaker, or
different when the evidence changes.

------------------------------------------------------------------------

## Expected Outputs

The worksheet's Diagnostic Summary captures the causal hypothesis, supporting evidence, alternatives, countermeasure, observed result, expected mechanism, inference, and confidence over time. Keep causal evidence and intervention evidence distinguishable, including what future evidence would strengthen, weaken, or falsify the explanation.

## Available Formats and Companion Guidance

- [DOCX working worksheet](releases/cause-countermeasure-diagnostic.docx) — authoritative working artifact for the approved baseline.
- [PDF distribution worksheet](releases/cause-countermeasure-diagnostic.pdf) — corresponding fixed distribution format.
- [Markdown companion](cause-countermeasure-diagnostic.md) — conceptual and extended investigative guidance.

DOCX and PDF are available locally. These files have not been published through GitHub Releases. Markdown accurately represents the worksheet and may expand its guidance; it is not the controlling release document.

The Markdown companion provides conceptual guidance for the two evidence paths and their interpretation. It is not the controlling release document; the approved DOCX governs the working artifact.

## Version and Maturity

- **Collection:** Collection 001 — Initial Diagnostics
- **Version:** v0.5.2
- **Maturity:** Experimental
- **Content status:** Approved baseline
- **Publication status:** Not yet published through GitHub Releases

v0.5.2 is the initial recorded administrative content baseline, not a reconstructed historical release. Artifact versions follow Semantic Versioning 2.0.0 (MAJOR.MINOR.PATCH) and will evolve independently. Documentation-only changes do not increment the artifact version. Content approval does not establish public publication or validation for every environment.

------------------------------------------------------------------------

## Use It. Challenge It. Change It.

This artifact is a starting point, not a declared best practice.

Use it in a real investigation.

Remove questions that do not help.

Add questions that expose something important.

Change the language for your environment.

Challenge the assumptions behind it.

If you find a better way to separate causal evidence from intervention
evidence, that is exactly the kind of improvement the Open Lab is
intended to surface.

See the repository contribution guidance if you want to propose a change
or share what you learned.

------------------------------------------------------------------------

## Copyright and Licensing

© 2026 Daniel Venn | WhatIfWorks | Open Lab
Licensed under CC BY-SA 4.0

See the repository [LICENSE.md](../../../LICENSE.md) for the governing terms.

------------------------------------------------------------------------

**WhatIfWorks \| Open Lab**

*Practical open-source artifacts for Quality, Continuous Improvement,
and Operational Excellence.*

**USE IT. CHALLENGE IT. CHANGE IT. MAKE IT BETTER.**

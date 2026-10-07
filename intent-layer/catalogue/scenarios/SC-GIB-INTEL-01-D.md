# SC-GIB-INTEL-01-D - Accumulated Signals With No Single Trigger

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted Decision, Rationale, intended outcome, and View for a potentially material Signal. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | `Hypothesis` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | A working period begins after an unattended window (overnight, travel, a day of back-to-back meetings) and a batch of changes has accumulated. No single item crossed a threshold on its own. The batch as a whole needs reducing before any item can be judged. |
| **Trigger** | Attention resumes over an accumulated set of changes rather than being drawn by one Signal. |
| **Starting conditions** | Items are duplicated, of mixed relevance, and weakly connected to each other and to client context. The response window for some may already be short. |
| **Stakes and urgency** | A material item can hide in volume. Equally, treating the batch as one unit, or as a ranked list to be worked through, creates work that the participant declined (Q52, Q56). |
| **What varies** | `S1` runs over the batch rather than one item. Duplication and novelty are assessed across the set. Items are ordered for judgment by consequence and remaining window (Q41: what changed, where value or trust is at risk, where the banker is needed, what must move). |
| **What remains invariant** | Each item still ends in its own Decision, including release (dismiss or retain). No item is carried forward merely because it arrived in the batch. The accepted ordering is a means, not a value; no cross-family ordering is admitted. |
| **Additional business rules or controls** | The Q74 direct-attention thresholds apply to items in the batch exactly as to single items. Volume does not lower scrutiny for the material items or raise it for the rest. |
| **Exit or transition** | Every item in the batch has been dismissed, retained, monitored, validated, prepared, acted upon, or sent on. Items above threshold proceed through `S2` to `S6` individually. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1-S2 | Reduce noise and connect context across the whole batch before any single item reaches judgment. | Items arrived together and duplicate or inform one another. | Support team carries the batch reduction; Senior Coverage MD sees only items that clear `S1`. | Fewer, better-connected items reach judgment. |
| S4-S6 | Unchanged: one Decision per item. | The value delivered is per item. | None. | Release is an explicit result for most of the batch. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Material items are not lost in volume; most of the batch is released explicitly; senior attention is spent only on items that cleared `S1`. |
| **Failure risks** | A material item hidden by volume; the batch itself treated as work to complete; a ranked list standing in for judgment. |
| **Evidence** | IBIQ UC-01 product specification (the daily re-orientation candidate, withdrawn as a use case by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md)); Round 1 record Q39 to Q41. All evidence is briefing-shaped; no episode. |
| **Open questions** | Observe one resumption after an unattended window. Test whether the batch is really an intelligence scenario or spans families, which this record does not admit. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After an observed resumption episode or Round 2 question CINT12. |
| **Review triggers** | Evidence that the batch produces a value distinct from per-item Decisions, or that ordering is wanted across families. |
| **Supersession links** | None. Absorbs the intelligence slice of the withdrawn IBIQ daily re-orientation candidate that briefly carried the ID `BUC-GIB-INTEL-02`. |
| **Change rationale** | Raised as a candidate scenario by the model revision of 2026-10-07; not admitted. Start of day is a situation, not a progress or a value; what remains is a batch variation of `S1`. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | IBIQ UC-01 specification; Q39 to Q41 re-read | Raised as `Candidate` at `Hypothesis`; not admitted. | `[validate: intent model owner]` | `BUC-GIB-INTEL-01`, `JTBD-GIB-INTEL-01`, `JF-GIB-INTEL-01` |
| `0.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

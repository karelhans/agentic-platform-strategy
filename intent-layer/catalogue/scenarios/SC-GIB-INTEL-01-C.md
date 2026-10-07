# SC-GIB-INTEL-01-C - Monitor Or Dismiss

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted Decision, Rationale, intended outcome, and View for a potentially material Signal. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | A Signal is relevant enough to assess but does not justify immediate client or firm action. |
| **Trigger** | Materiality, credibility, timing, or usefulness tests support waiting, monitoring, retention, or dismissal. |
| **Starting conditions** | A Signal has client context and an assessed implication, but immediate intervention would add little value or create avoidable risk. |
| **Stakes and urgency** | The team must release attention without losing a meaningful future condition. |
| **What varies** | Completion is an explicit Decision to wait, monitor, retain, or dismiss rather than to act. |
| **What remains invariant** | Rationale, intended consequence, View, and reassessment condition are explicit where relevant. |
| **Additional business rules or controls** | A Decision to monitor or dismiss is a valid result; do not create work merely to show responsiveness. |
| **Exit or transition** | Attention closes, or monitoring continues until evidence invalidates the Signal or a reassessment condition occurs. When a monitored condition fires, that is a new `BUC-GIB-INTEL-01` trigger. The item re-enters at S1 with its prior Rationale, rather than resuming inside this run. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S4-S6 | Choose a Decision to monitor or dismiss and send it to the owner. | Action is not currently justified. | Monitoring may be delegated while the MD retains only the agreed return condition. | Senior attention is released without silent loss. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | More appropriate Decisions to monitor or dismiss; fewer low-value tasks; monitored conditions return when material; Rationale is recoverable. |
| **Failure risks** | Quiet neglect, indefinite monitoring, unnecessary activity, or no owned return condition. |
| **Evidence** | Coverage evidence revision 2.0, Q08, Q73, Q88-Q90. |
| **Open questions** | Validate monitoring ownership and closure practices across teams. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed monitor and dismissal episodes. |
| **Review triggers** | Changed closure, monitoring ownership, return condition, or evidence of silent loss. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: state that a fired monitor condition is a new `BUC-GIB-INTEL-01` trigger. Variation unchanged. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q36, Q62, Q65, Q73 re-read | Revised in place; monitor return made explicit as a new trigger, no semantic change. | `[validate: intent model owner]` | `BUC-GIB-INTEL-01` |
| `1.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Title changed from "Deliberate Non-Action Or Monitoring". Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

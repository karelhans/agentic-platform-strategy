# SC-GIB-INTEL-01-C - Deliberate Non-Action Or Monitoring

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted disposition, rationale, intended outcome, and destination for potentially consequential intelligence. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Intelligence is relevant enough to assess but does not justify immediate client or franchise action. |
| **Trigger** | Materiality, credibility, timing, or usefulness tests support waiting, monitoring, retention, or dismissal. |
| **Starting conditions** | A signal has client context and an assessed implication, but immediate intervention would add little value or create avoidable risk. |
| **Stakes and urgency** | The team must release attention without losing a meaningful future condition. |
| **What varies** | Completion is an explicit wait, monitor, retain, or dismiss disposition rather than action. |
| **What remains invariant** | Rationale, intended consequence, destination, and reassessment condition are explicit where relevant. |
| **Additional business rules or controls** | Non-action is a valid result; do not create work merely to demonstrate responsiveness. |
| **Exit or transition** | Attention closes or monitoring continues until evidence invalidates the signal or a reassessment condition occurs. When a monitored condition fires, that is a new `BUC-GIB-INTEL-01` trigger: the item re-enters at S1 with its prior rationale, rather than resuming inside this run. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S4-S6 | Choose and route a non-action disposition. | Action is not currently justified. | Monitoring may be delegated while the MD retains only the agreed return condition. | Senior attention is released without silent loss. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | More appropriate non-action; fewer low-value tasks; monitored conditions return when material; rationale is recoverable. |
| **Failure risks** | Quiet neglect, indefinite monitoring, unnecessary activity, or no accountable return condition. |
| **Evidence** | Coverage evidence revision 2.0, Q08, Q73, Q88-Q90. |
| **Open questions** | Validate monitoring ownership and closure practices across teams. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed monitor and dismissal episodes. |
| **Review triggers** | Changed closure, monitoring ownership, return condition, or evidence of silent loss. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: state that a fired monitor condition is a new `BUC-GIB-INTEL-01` trigger. Variation unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q36, Q62, Q65, Q73 re-read | Revised in place; monitor return made explicit as a new trigger, no semantic change. | `[validate: intent model owner]` | `BUC-GIB-INTEL-01` |

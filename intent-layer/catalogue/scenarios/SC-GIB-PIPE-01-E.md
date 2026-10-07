# SC-GIB-PIPE-01-E - Restricted Cross-GIB Opportunity

> **Superseded.** Retired as a scenario by the model revision of 2026-10-07. Restricted-information handling has no value of its own and applies to every family, so it is now the cross-family control rule written into the business rules field of [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md), [`BUC-GIB-PIPE-02`](../business-use-cases/BUC-GIB-PIPE-02.md), [`BUC-GIB-PIPE-03`](../business-use-cases/BUC-GIB-PIPE-03.md) and the other families' use cases, plus the "material detail is restricted" exception row and the controls field of `JF-GIB-PIPE-01`. Retained for traceability; do not cite as a current scenario.

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) |
| **Related JTBDs** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) |
| **Value delivered** | A shared, challenge-tested opportunity judgment with accountable stewardship and purposeful next movement or deliberate parking or exit. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`, `ACTOR-COV-PIPELINE-TEAM` |
| **Evidence maturity** | `Superseded` (was `Evidence-backed` at revision `1.0`; the rule itself remains evidence-backed where it now lives) |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | An opportunity spans products or regions while material details are constrained by client, legal, clean-team, information-barrier, or regional rules. |
| **Trigger** | Relevant evidence, potential outreach, or ownership conflict arises outside the entitled group. |
| **Starting conditions** | Full substance cannot be shared, but invisible activity can cause missed signals, duplicated outreach, or conflicting client action. |
| **Stakes and urgency** | Coordination must preserve client trust and controls without orphaning the opportunity or suppressing relevant evidence. |
| **What varies** | Only safe metadata may be visible; authority and conflict resolution may involve Coverage and relevant business heads. |
| **What remains invariant** | The restricted situation has an accountable owner, a permissible review path, and a current stewardship state. |
| **Additional business rules or controls** | At minimum, others may know a restricted situation exists and who owns it; further visibility depends on the restriction and entitlement. |
| **Exit or transition** | Evidence is safely routed, ownership is resolved, or the situation continues under restricted stewardship. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S2-S6 | Separate entitled substance from safe coordination metadata. | Full sharing would breach a control or client expectation. | Coverage orchestrates institution-level coherence; relevant business heads resolve ownership conflicts. | Coordination remains possible without unauthorized disclosure. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Relevant evidence reaches the accountable owner; duplicate or conflicting action declines; restricted substance remains protected. |
| **Failure risks** | Unauthorized disclosure, invisible activity, orphaned ownership, duplicated outreach, or suppressed relevant evidence. |
| **Evidence** | Coverage evidence revision 2.0, Q142, Q145, and Q151; added at revision `2.0`: Q70 (controls appear only when triggered), Q02 and Q06 (the same failure inside intelligence: a signal that never reached its owner), Q145 (the minimum shared context rule). |
| **Open questions** | Validate safe metadata, exception authority, and escalation paths with legal, risk, controls, data, and regional stakeholders. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `2.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Superseded` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | None as a scenario; control and regional validation continues on the control rule in the use cases. |
| **Review triggers** | Changed information-sharing rule, safe metadata, exception authority, cross-region model, or evidence that restricted stewardship creates a different value outcome. |
| **Supersession links** | Superseded by the cross-family control rule in the business rules field of `BUC-GIB-PIPE-01` revision `3.0`, `BUC-GIB-PIPE-02` revision `0.1`, `BUC-GIB-PIPE-03` revision `0.1`, and the sibling families' use cases; the "material detail is restricted" exception row in `BUC-GIB-PIPE-01` is kept. Introduced as a scenario in revision 2.0 of the pipeline slice. |
| **Change rationale** | The model revision of 2026-10-07 applied the scenario test: the restriction changes no trigger, completion condition, or value delivered, and the Q145 rule is invariant across families (Q70: controls appear only when triggered; Q02 and Q06 show the same failure in intelligence). A control with no value of its own is a business rule everywhere, not a scenario anywhere. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q142, Q145, and Q151 | Added as `Evidence-backed`; control validation remains open. | Coverage intent model owner | `BUC-GIB-PIPE-01` |
| `2.0` | 2026-10-07 | Q70, Q02, Q06 added to the evidence; model revision of 2026-10-07 | Marked `Superseded`: retired as a scenario and restated as the cross-family control rule in every use case's business rules. File retained. | Coverage intent model owner | `BUC-GIB-PIPE-01`, `BUC-GIB-PIPE-02`, `BUC-GIB-PIPE-03`, `JF-GIB-PIPE-01` |

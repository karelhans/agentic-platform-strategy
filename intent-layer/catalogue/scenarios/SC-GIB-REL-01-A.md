# SC-GIB-REL-01-A - Contextual Change In The Client Institution

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md) |
| **Value delivered** | An accepted relationship-quality judgment, objective, engagement disposition, and owned next movement for a priority client institution. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate); product and regional contributors `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Something material changes inside the client institution: its agenda, its leadership or decision-makers, its ownership or control, or its strategic direction. The prior relationship judgment may no longer describe who matters and what JPM's standing is. |
| **Trigger** | Client context changed (Q97): a known or inferred change in agenda, leadership, ownership or strategy at the institution, arriving through intelligence, a conversation, or market events. Cadence and dry spells are not this scenario; they are `SC-GIB-REL-01-C`. |
| **Starting conditions** | The change is known at least in outline; its consequence for trust, access, reciprocity and engagement, and for which stakeholders now matter, is not. The client's new agenda is inferable from markers but not documentable with precision (Q110). |
| **Stakes and urgency** | A change in who decides or what the institution is trying to do can open or close JPM's access and relevance; reading it late leaves JPM positioned for the institution that was, not the one that is. |
| **What varies** | S1 and S2 re-read markers and stakeholders against the change rather than over a planning horizon; S4 may change the stakeholder; the useful response may be to listen rather than to propose (Q100). |
| **What remains invariant** | Institution-level judgment, objective, disposition, and owned movement are accepted; the Coverage MD orchestrates. |
| **Additional business rules or controls** | Foreground what changed and why it matters now; do not restate the client agenda with more certainty than the markers support; keep detailed stakeholder and cross-JPM context available on demand (Q108). |
| **Exit or transition** | The relationship continues under a revised judgment: personal engagement, delegated maintenance, coordination, repair, or deliberate wait. A contact disposition hands to `BUC-GIB-REL-02` (candidate). |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1-S2 | Establish the change and re-read trust, access, reciprocity and engagement against it, rather than reviewing the whole relationship over a horizon. | The change, not the calendar, is the reason for attention. | Coverage MD retains institution-level orchestration; support team prepares the case. | The prior judgment is confirmed, qualified or replaced. |
| S4 | Re-choose the stakeholder where leadership or ownership has moved. | The people who matter may have changed (Q95, Q103, Q108). | None. | Objective aimed at the institution as it now is. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Changed stakeholders and agenda recognised before a competitor acts on them; purposeful objective tied to the change; no unnecessary engagement. |
| **Failure risks** | False certainty about the new agenda, reading the change through the old stakeholder map, or treating any change as a reason to contact. |
| **Evidence** | Coverage evidence revision 2.0, Q95, Q97, Q101-Q108, Q110. |
| **Open questions** | Validate with an observed episode where leadership or ownership changed; confirm what counts as material change by tier. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After an observed review prompted by a change in the client institution. |
| **Review triggers** | Changed review boundary, orchestration authority, evidence model, or value delivered; evidence that contextual change needs a different path from the parent. |
| **Supersession links** | None. Stable ID kept; scope changed at revision 1.1. |
| **Change rationale** | Model revision of 2026-10-07: as written at 1.0 this scenario was the baseline run of the parent and its "review cadence" trigger duplicated `SC-GIB-REL-01-C`. Re-scoped to the Q97 contextual-change variation so that A (change in the institution), B (time-sensitive risk or commitment), C (cadence) and D (cross-JPM overlap) are mutually exclusive. Maturity unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-REL-01` |
| `1.1` | 2026-10-07 | No new evidence; Q97 and Q110 re-read under the model revision of 2026-10-07 | Revised in place and renamed from "Institution Relationship Review" to "Contextual Change In The Client Institution". Re-scoped so it stops duplicating C's cadence trigger. | Coverage intent model owner | `BUC-GIB-REL-01`, `SC-GIB-REL-01-C` |

# SC-GIB-PIPE-01-G - Review Condition Reached Without Movement

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) |
| **Related JTBDs** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md); `JTBD-GIB-ACT-01` (candidate) where the stalled item is a commitment |
| **Value delivered** | A challenge-tested judgment on one opportunity with an accountable owner and a purposeful next move, or a deliberate park or exit, and an explicit condition for future review. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`, `ACTOR-COV-PIPELINE-TEAM` |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | The review condition set at the last review is reached, but the accepted next movement has not occurred. |
| **Trigger** | A committed checkpoint is missed, the decision window is shrinking, an assumption has changed, or relationship risk has increased, with no meaningful progress (Q23). |
| **Starting conditions** | The opportunity has an accepted state, owner, and next move; the absence of movement may reflect the client, the owner's capacity or authority, a changed assumption, or a judgment that no longer holds. |
| **Stakes and urgency** | Silent persistence hides the stall; the decision window keeps shrinking while the shared picture still shows an active pursuit. |
| **What varies** | S1 is triggered by the condition rather than by new evidence; S3 challenges ownership, active status, and direction rather than trajectory alone; S4 may escalate, re-own, park, or exit. |
| **What remains invariant** | An explicit stewardship response and an accountable owner replace silent persistence; a new review condition is set. |
| **Additional business rules or controls** | A missed movement is a review trigger, not a reporting event; the response is a judgment on the opportunity, not a chase for its own sake. Where the stalled item is a consequential commitment above the drift threshold, it enters `BUC-GIB-ACT-01` (candidate). |
| **Exit or transition** | Revised direction with a renewed owner and next move, escalation, parking under revised conditions, or exit via `SC-GIB-PIPE-01-F`. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1 | The trigger is a reached condition with no movement, not changed evidence. | The review condition exists to catch this. | Owner or Senior Coverage MD may raise it. | The stall becomes visible. |
| S3-S4 | Re-challenge stewardship, ownership, and active status; decide whether the owner, the direction, or the pursuit should change. | Movement did not occur as accepted (Q23). | Senior Coverage MD may intervene in delegated work; business heads if ownership is in dispute. | Revised direction, escalation, parking, or exit rather than continued inertia. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Stalled opportunities are re-challenged when the condition fires; owners and direction are renewed or the pursuit is parked or exited; fewer opportunities persist in the picture without movement. |
| **Failure risks** | Silent persistence, chasing without judgment, re-setting the condition without changing anything, or escalation that returns the work to the senior by default. |
| **Evidence** | Coverage evidence revision 2.0, Q23 (triggers for intervention in delegated work before the due date); the existing exception row "the accepted next movement does not occur" in `BUC-GIB-PIPE-01`. No concrete episode (Q139). |
| **Open questions** | How review conditions are set and noticed in practice; which stalls belong to this review and which cross the threshold into `BUC-GIB-ACT-01`; a concrete stalled-opportunity episode. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a concrete stalled-opportunity episode is captured, or when `BUC-GIB-ACT-01` is admitted or rejected. |
| **Review triggers** | Changed intervention triggers (Q23), changed threshold for `BUC-GIB-ACT-01`, or evidence that this variation produces a different value delivered. |
| **Supersession links** | None. New scenario introduced by the model revision of 2026-10-07; it gives the parent's existing exception row a scenario. |
| **Change rationale** | The exception row described a recurring condition of the opportunity with its own evidence (Q23); on the new scenario axis, the condition of the opportunity when the review fires, it is a scenario with the same value delivered. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested Q23 | Added as `Evidence-backed`; concrete episode remains required. | Coverage intent model owner | `BUC-GIB-PIPE-01` |

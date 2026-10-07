# SC-GIB-PIPE-01-F - Deliberate Exit

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) |
| **Related JTBDs** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) |
| **Value delivered** | A challenge-tested judgment on one opportunity. It has an accountable owner and a purposeful next step, or a deliberate park or exit. It has an explicit condition for future review. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`, `ACTOR-COV-PIPELINE-TEAM` |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | The review of an existing opportunity finds that continuing to pursue it would generate activity rather than progress. The right judgment is to stop. |
| **Trigger** | Evidence of the kind the participant named at Q16. Timing has moved materially, economics no longer justify the effort, relationship cost is rising, or dependencies make progress implausible. |
| **Starting conditions** | The opportunity has an owner and a history of effort. Stopping may feel like loss, and the default is to keep generating activity. |
| **Stakes and urgency** | Effort and senior attention stay tied up where they no longer change the outcome. Relationship cost may keep rising while the pursuit persists. |
| **What varies** | The response at S4 is exit. S5 confirms the owner of the future watch rather than a next client step. S6 records a minimal closure: outcome reason and evidence, reactivation conditions, and watch ownership, nothing more (Q147). |
| **What remains invariant** | The exit is a challenge-tested judgment with an accountable owner and an explicit condition for return. It is not silent abandonment. |
| **Additional business rules or controls** | Minimal closure only. No mandatory retrospective. Do not retain unnecessary sensitive detail (Q147). Deliberate exit is a valid completion, parallel to a Decision to monitor or dismiss in `SC-GIB-INTEL-01-C`. |
| **Exit or transition** | The opportunity leaves active management. If its reactivation condition occurs, it re-enters through `SC-GIB-PIPE-01-C`. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S3 | Challenge tests the Q16 stop evidence against the case for persisting. | Stopping should be as deliberate as advancing. | The Senior Coverage MD judges relationship cost and relevance to the firm where material. | The decision to stop is explicit and explainable. |
| S5-S6 | Confirm the future-watch owner and record a minimal closure instead of a next client step and full update. | Retention should support re-entry without defensive reporting (Q147). | The future-watch owner may differ from the opportunity owner. | Re-entry stays possible. Clutter does not accumulate. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Opportunities exit deliberately with a reason, a reactivation condition, and a watch owner. Effort and senior attention are released. Relationship cost stops rising. |
| **Failure risks** | Activity persists without progress. Exits happen silently with no re-entry condition. Closure becomes a retrospective burden. Sensitive detail is retained unnecessarily. |
| **Evidence** | Coverage evidence revision 2.0, Q16 (timing, economics, relationship cost, dependencies as reasons to stop) and Q147 (minimal closure, reactivation conditions, watch ownership). No concrete episode (Q139). |
| **Open questions** | Who may decide an exit at each maturity; whether exit thresholds differ between early ideas and active pitches (Q148); a concrete exit episode. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a concrete exit episode is captured. |
| **Review triggers** | Changed stop criteria, closure rule, or watch ownership; evidence that exit produces a different value delivered from the parent. |
| **Supersession links** | None. New scenario introduced by the model revision of 2026-10-07. |
| **Change rationale** | Revision `1.1`: banker-language pass; wording only, meaning unchanged. Revision `1.0`: deliberate exit was tested as a use case and demoted. The parent's value sentence already contains "deliberate park or exit". So exit is a variation on the condition of the opportunity when the review fires. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested Q16 and Q147 | Added as `Evidence-backed`; concrete episode remains required. | Coverage intent model owner | `BUC-GIB-PIPE-01`, `SC-GIB-PIPE-01-C` |
| `1.1` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None; wording only |

# SC-GIB-INTEL-01-A - Short-Window Consequential Signal

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted disposition, rationale, intended outcome, and destination for potentially consequential intelligence. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; preparatory triage contributors `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | New evidence may materially affect a client or franchise outcome while the useful response window is closing. |
| **Trigger** | Consequence and timing cross the threshold for direct senior attention. |
| **Starting conditions** | Client context and evidence may be incomplete, but delay itself creates material risk. |
| **Stakes and urgency** | Late interpretation can lose client relevance, credibility, opportunity, or the ability to influence the outcome. |
| **What varies** | Triage is compressed; senior visibility and evidence scrutiny increase; validation depth depends on recoverability and time. |
| **What remains invariant** | Evidence, uncertainty, consequence, response, and destination remain explicit. |
| **Additional business rules or controls** | Urgency does not make weak evidence true; confidentiality and right-to-engage still govern response. |
| **Exit or transition** | The signal is dismissed, monitored, validated, prepared, acted upon, or routed before the window closes. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S2-S6 | Compress context, consequence, judgment, and routing around the remaining window. | Response value decays with time. | Senior Coverage MD may review before normal preparatory depth is complete. | Disposition records the accepted uncertainty and urgency. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Accepted response before the useful window closes; uncertainty remains visible; no unnecessary escalation persists afterward. |
| **Failure risks** | Late action, rushed false confidence, missed client context, or disclosure beyond entitlement. |
| **Evidence** | Coverage evidence revision 2.0, Q31-Q32, Q74, and Q90. |
| **Open questions** | Validate materiality and timing thresholds through observed episodes. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-02 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a short-window intelligence episode is observed. |
| **Review triggers** | Changed escalation threshold, authority, scrutiny rule, or value delivered. |
| **Supersession links** | None. |
| **Change rationale** | Promote the existing evidence-backed short-window variation. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-INTEL-01` |

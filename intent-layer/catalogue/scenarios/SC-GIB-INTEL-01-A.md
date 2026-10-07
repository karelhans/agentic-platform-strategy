# SC-GIB-INTEL-01-A - Short-Window Material Signal

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
| **Context** | New evidence may materially affect a client or firm outcome while the useful response window is closing. |
| **Trigger** | Consequence and timing cross the threshold for direct senior attention. |
| **Starting conditions** | Client context and evidence may be incomplete, but delay itself creates material risk. |
| **Stakes and urgency** | Late interpretation can lose client relevance, credibility, opportunity, or the ability to influence the outcome. |
| **What varies** | Triage is compressed; senior visibility and evidence scrutiny increase; validation depth depends on recoverability and time. |
| **What remains invariant** | Evidence, uncertainty, consequence, response, and View remain explicit. |
| **Additional business rules or controls** | Urgency does not make weak evidence true; confidentiality and the right to engage still govern response. High consequence with a short window is one of the Q74 direct-attention thresholds. The others (relationship-sensitive meaning, strategic ambiguity, major-opportunity change, cross-client or firm-wide implication) are business rules of the parent use case and are not this scenario. |
| **Exit or transition** | The Signal is dismissed, monitored, validated, prepared, acted upon, or sent on before the window closes. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S2-S6 | Compress context, consequence, judgment, and sending around the remaining window. | Response value decays with time. | Senior Coverage MD may review before normal preparatory depth is complete. | The Decision records the accepted uncertainty and urgency. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Accepted response before the useful window closes; uncertainty remains visible; no unnecessary escalation persists afterward. |
| **Failure risks** | Late action, rushed false confidence, missed client context, or disclosure beyond access. |
| **Evidence** | Coverage evidence revision 2.0, Q31-Q32, Q74, and Q90. |
| **Open questions** | Validate materiality and timing thresholds through observed episodes. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a short-window Signal episode is observed. |
| **Review triggers** | Changed escalation threshold, authority, scrutiny rule, or value delivered. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: short window is one of the Q74 direct-attention thresholds; the others are held as business rules on the parent. Variation unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q74 re-read | Revised in place; no semantic change. Support-team cohort referenced as candidate. | `[validate: intent model owner]` | `BUC-GIB-INTEL-01` |
| `1.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Title changed from "Short-Window Consequential Signal". Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

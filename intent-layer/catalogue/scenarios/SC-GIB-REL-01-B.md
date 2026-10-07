# SC-GIB-REL-01-B - Time-Sensitive Relationship Risk Or Commitment

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md); `JTBD-GIB-ACT-01` (candidate, not admitted) for the commitment half. |
| **Value delivered** | An accepted relationship-quality judgment, objective, engagement disposition, and owned next movement for a priority client institution. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; relevant commitment or relationship owners `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Trust, access, responsiveness, credibility, or a material reciprocal commitment changes while a useful response window is narrowing. |
| **Trigger** | Relationship risk or commitment significance crosses the threshold for senior attention. |
| **Starting conditions** | Delay may damage credibility or access; another JPM owner or client stakeholder may hold necessary context. |
| **Stakes and urgency** | Senior involvement may materially protect trust, move a commitment, or repair relationship trajectory. |
| **What varies** | Review is compressed, personal involvement is more likely, and coordination or commitment movement becomes central. |
| **What remains invariant** | Institution-level judgment, purposeful objective, engagement disposition, and owned movement remain explicit. |
| **Additional business rules or controls** | Seniority alone does not justify engagement; JPM must have a credible right and purpose to engage. |
| **Exit or transition** | Risk is repaired, commitment moves, ownership is clarified, or deliberate wait is accepted. Repair contact runs through `BUC-GIB-REL-02` (candidate) or `BUC-GIB-MEET-01`. A commitment that is drifting or waiting on the MD, once it crosses the drift threshold, enters `BUC-GIB-ACT-01` (candidate); below that threshold it stays with its owner in this family. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S2-S5 | Focus marker interpretation and disposition on the material risk or commitment. | Delay can compound relationship cost. | Senior Coverage MD may engage directly or orchestrate another senior owner. | Timely movement replaces routine cadence. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Credibility protected; commitment resolves; trust or access stabilizes; client experiences coherent JPM action. |
| **Failure risks** | Late response, duplicated outreach, purposeless escalation, or unresolved ownership. |
| **Evidence** | Coverage evidence revision 2.0, Q96-Q100 and Q106; Q10, Q102 and Q122 for the commitment half. |
| **Open questions** | Validate intervention thresholds and commitment ownership through real cases. Where the drift threshold sits between this scenario and `BUC-GIB-ACT-01` (candidate). |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a material relationship-risk or commitment episode is observed. |
| **Review triggers** | Changed attention threshold, authority, commitment boundary, or right-to-engage rule; admission decision on `JTBD-GIB-ACT-01`. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: cross-link the commitment half of this scenario to the candidate actions job `JTBD-GIB-ACT-01` and state the threshold at which a commitment leaves this family for `BUC-GIB-ACT-01` (candidate). Candidates are not admitted. No change to the variation or its maturity. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-REL-01` |
| `1.1` | 2026-10-07 | No new evidence; model revision of 2026-10-07 | Revised in place: commitment half cross-linked to `JTBD-GIB-ACT-01` (candidate); exits name `BUC-GIB-REL-02` (candidate) and `BUC-GIB-ACT-01` (candidate). | Coverage intent model owner | `BUC-GIB-REL-01` |

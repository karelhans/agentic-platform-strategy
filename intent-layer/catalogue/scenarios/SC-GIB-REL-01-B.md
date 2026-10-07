# SC-GIB-REL-01-B - Time-Sensitive Relationship Risk Or Commitment

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md); `JTBD-GIB-ACT-01` (candidate, not admitted) for the commitment half. |
| **Value delivered** | An accepted relationship-quality judgment, an objective, a Decision on how to engage, and an owned next step for a priority client institution. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; relevant commitment or relationship owners `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Trust, access, responsiveness, credibility, or a material reciprocal commitment changes while the window for a useful response is narrowing. |
| **Trigger** | Relationship risk, or the significance of a commitment, crosses the threshold for senior attention. |
| **Starting conditions** | Delay may damage credibility or access. Another JPM owner or client stakeholder may hold necessary context. |
| **Stakes and urgency** | Senior involvement may materially protect trust, move a commitment, or repair the relationship's direction. |
| **What varies** | The review is compressed, personal involvement is more likely, and coordination or moving the commitment becomes central. |
| **What remains invariant** | Institution-level judgment, purposeful objective, Decision on how to engage, and owned next step remain explicit. |
| **Additional business rules or controls** | Seniority alone does not justify contact; JPM must have a credible right and purpose to engage. |
| **Exit or transition** | The risk is repaired, the commitment moves, ownership is clarified, or a deliberate wait is accepted. Repair contact runs through `BUC-GIB-REL-02` (candidate) or `BUC-GIB-MEET-01`. A commitment that is drifting or waiting on the MD enters `BUC-GIB-ACT-01` (candidate) once it crosses the drift threshold. Below that threshold it stays with its owner in this family. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S2-S5 | Focus the reading of the signs, and the Decision, on the material risk or commitment. | Delay can compound the relationship cost. | The Senior Coverage MD may engage directly or coordinate another senior owner. | Timely movement replaces routine timing. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Credibility protected; the commitment resolves; trust or access stabilises; the client experiences coherent JPM action. |
| **Failure risks** | Late response, duplicated outreach, purposeless escalation, or unresolved ownership. |
| **Evidence** | Coverage evidence revision 2.0, Q96-Q100 and Q106; Q10, Q102 and Q122 for the commitment half. |
| **Open questions** | Validate intervention thresholds and commitment ownership through real cases. Where the drift threshold sits between this scenario and `BUC-GIB-ACT-01` (candidate). |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a material relationship-risk or commitment episode is observed. |
| **Review triggers** | Changed attention threshold, authority, commitment boundary, or right-to-engage rule; admission decision on `JTBD-GIB-ACT-01`. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: cross-link the commitment half of this scenario to the candidate actions job `JTBD-GIB-ACT-01` and state the threshold at which a commitment leaves this family for `BUC-GIB-ACT-01` (candidate). Candidates are not admitted. No change to the variation or its maturity. Revision 1.2 is a banker-language pass on wording only. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-REL-01` |
| `1.1` | 2026-10-07 | No new evidence; model revision of 2026-10-07 | Revised in place: commitment half cross-linked to `JTBD-GIB-ACT-01` (candidate); exits name `BUC-GIB-REL-02` (candidate) and `BUC-GIB-ACT-01` (candidate). | Coverage intent model owner | `BUC-GIB-REL-01` |
| `1.2` | 2026-10-07 | No new evidence; wording only | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None |

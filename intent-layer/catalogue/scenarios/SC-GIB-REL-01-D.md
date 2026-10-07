# SC-GIB-REL-01-D - Cross-JPM Overlap On One Institution

> Candidate record raised by the model revision of 2026-10-07. Not admitted. Until the intent model owner accepts it, consumers treat the cross-JPM overlap as the exception row it was in `BUC-GIB-REL-01` revision 1.0.

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md) |
| **Value delivered** | An accepted relationship-quality judgment, an objective, a Decision on how to engage, and an owned next step for a priority client institution. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; product and regional contact owners `[validate actor]`; business heads as arbiters `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` for the authority and the failure it answers (Q94, Q104, Q142); no run has been observed. |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Several parts of JPM touch one priority client institution. Another JPM team plans or has made contact. Overlap, conflicting positioning, duplicate outreach, or activity hidden from the Coverage MD comes to light. The client risks experiencing several banks rather than one. |
| **Trigger** | Cross-bank context reveals that another JPM team plans or has made contact with the institution. Or it reveals that two parts of JPM are positioning differently with it. |
| **Starting conditions** | The Coverage MD may learn of the other contact late or partially. The other team may not know the institution-level priorities. Some of the activity may be restricted and known only as existing and owned (Q145). |
| **Stakes and urgency** | Failure to coordinate JPM is one of the root failures the participant named (Q94), and it reinforces the others. Conflicting contact can cost access and credibility faster than silence does. |
| **What varies** | S3 to S5 centre on JPM's posture, sequence and lead owner across teams rather than on a single stakeholder choice. Participants widen to the other contact owners. Unresolved ownership escalates beyond the family. |
| **What remains invariant** | One institution-level judgment, objective and Decision. The Coverage MD owns the coherent institution-level agenda (Q104) and coordinates the response. |
| **Additional business rules or controls** | Coverage coordinates. The relevant business heads arbitrate conflicts over ownership, client contact, or product and regional priorities (Q142). Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. |
| **Exit or transition** | Posture, sequence and lead owner for each contact are agreed and communicated. Or the conflict sits with business heads while Coverage holds the client position. Agreed contact runs through `BUC-GIB-REL-02` (candidate) or `BUC-GIB-MEET-01`. An opportunity in dispute goes to its owner in `JF-GIB-PIPE-01` (Q136). |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1 | Surface all planned and recent JPM contact with the institution, including restricted activity as existing and owned. | The judgment cannot rest on Coverage's own contact alone. | Other contact owners contribute. | Complete picture of JPM's footprint and intent. |
| S3-S5 | Set JPM posture and sequence, assign who leads each contact, and escalate unresolved ownership. | Coherence across JPM, not the stakeholder choice, is the open question. | The Coverage MD sets posture and sequence (Q104); business heads arbitrate what the MD cannot resolve (Q142). | One JPM position toward the client; contact sequenced. |
| S6 | Confirm and communicate the agreed ownership to every contributing team. | Coherence lasts only if every owner knows it. | None. | Owned next step in each team. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | The client experiences one JPM voice; no duplicate or contradictory outreach; ownership disputes resolved before the client notices them. |
| **Failure risks** | The client discovers hidden activity first; escalation used in place of coordination; Coverage overriding a product team's legitimate contact without the client's priorities in view. |
| **Evidence** | Coverage evidence revision 2.0, Q94 (failure to coordinate JPM), Q104 (Coverage MD accountable for the institution-level agenda), Q141 (a cross-bank situation plan selected as a coexisting scope), Q142 (Coverage-led coordination; business heads resolve conflicts), Q145 (safe coordination under restriction). No observed run. |
| **Open questions** | Round 2 CREL08 probes may show this is a use case of its own, "coordinate JPM around one institution", with agreed JPM ownership as a value distinct from the relationship judgment. The model revision held it as a scenario because the evidence is about authority, not an observed run. How duplicate outreach and hidden activity are detected in practice. Business heads have no actor record and have not been interviewed. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | On the intent model owner's admission decision, or after Round 2 CREL08 returns. |
| **Review triggers** | An observed cross-JPM overlap episode; evidence that agreed JPM ownership is a value distinct from the relationship judgment, which would make this a use case; changed coordination authority or arbitration model. |
| **Supersession links** | None. Replaces the exception row "another JPM team plans engagement" in `BUC-GIB-REL-01` revision 1.0. |
| **Change rationale** | Raised by the model revision of 2026-10-07 and not admitted. The cross-JPM overlap changes the path of the parent's steps 3 to 5 and its participants, so it is a scenario rather than an exception row. It does not change the value delivered, so it is not yet a use case. Revision 1.1 is a banker-language pass on wording only. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-07 | Q94, Q104, Q141, Q142, Q145 re-read under the model revision of 2026-10-07; no new evidence | Raised as a candidate scenario at `Evidence-backed`; not admitted. Promotion to a use case deferred to Round 2 CREL08. | Pending: Coverage intent model owner | `BUC-GIB-REL-01`, `JF-GIB-REL-01`, `JTBD-GIB-REL-01` |
| `1.1` | 2026-10-07 | No new evidence; wording only | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Pending: Coverage intent model owner | None |

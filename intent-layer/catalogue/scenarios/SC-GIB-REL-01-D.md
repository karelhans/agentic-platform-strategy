# SC-GIB-REL-01-D - Cross-JPM Overlap On One Institution

> Candidate record raised by the model revision of 2026-10-07. Not admitted. Until the intent model owner accepts it, consumers treat the cross-JPM overlap as the exception row it was in `BUC-GIB-REL-01` revision 1.0.

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md) |
| **Value delivered** | An accepted relationship-quality judgment, objective, engagement disposition, and owned next movement for a priority client institution. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; product and regional contact owners `[validate actor]`; business heads as arbiters `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` for the authority and the failure it answers (Q94, Q104, Q142); no run has been observed. |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Several parts of JPM touch one priority client institution. Another JPM team plans or has made contact, and overlap, conflicting positioning, duplicate outreach or activity hidden from the Coverage MD comes to light. The client risks experiencing several banks rather than one. |
| **Trigger** | Cross-bank context reveals that another JPM team plans or has made contact with the institution, or that two parts of JPM are positioning differently with it. |
| **Starting conditions** | The Coverage MD may learn of the other contact late or partially; the other team may not know the institution-level agenda; some of the activity may be restricted and known only as existing and owned (Q145). |
| **Stakes and urgency** | Failure to coordinate JPM is one of the root failures the participant named (Q94), and it reinforces the others. Conflicting contact can cost access and credibility faster than silence does. |
| **What varies** | S3 to S5 centre on JPM posture, sequence and lead owner across teams rather than on a single stakeholder choice; participants widen to the other contact owners; unresolved ownership escalates beyond the family. |
| **What remains invariant** | One institution-level judgment, objective and disposition; the Coverage MD is accountable for the coherent institution-level agenda (Q104) and orchestrates the response. |
| **Additional business rules or controls** | Coverage orchestrates; relevant business heads arbitrate conflicts over ownership, client contact, or product and regional priorities (Q142). Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the entitled group, others may know that a restricted situation exists and who owns it; further visibility depends on the restriction. |
| **Exit or transition** | Posture, sequence and lead owner for each contact are agreed and communicated, or the conflict is with business heads with Coverage holding the client position meanwhile. Agreed contact runs through `BUC-GIB-REL-02` (candidate) or `BUC-GIB-MEET-01`; an opportunity in dispute routes to its accountable owner in `JF-GIB-PIPE-01` (Q136). |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1 | Surface all planned and recent JPM contact with the institution, including restricted activity as existing and owned. | The judgment cannot be made on Coverage's own contact alone. | Other contact owners contribute. | Complete picture of JPM's footprint and intent. |
| S3-S5 | Set JPM posture and sequence, assign who leads each contact, and escalate unresolved ownership. | Coherence across JPM, not the stakeholder choice, is the open question. | Coverage MD sets posture and sequence (Q104); business heads arbitrate what the MD cannot resolve (Q142). | One JPM position toward the client; contact sequenced. |
| S6 | Confirm and communicate the agreed ownership to every contributing team. | Coherence lasts only if every owner knows it. | None. | Owned next movement in each team. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Client experiences one JPM voice; no duplicate or contradictory outreach; ownership disputes resolved before the client notices them. |
| **Failure risks** | Hidden activity discovered by the client first; escalation used in place of orchestration; Coverage overriding a product team's legitimate contact without the client agenda in view. |
| **Evidence** | Coverage evidence revision 2.0, Q94 (failure to coordinate JPM), Q104 (Coverage MD accountable for the institution-level agenda), Q141 (a cross-bank situation plan selected as a coexisting scope), Q142 (Coverage-led orchestration; business heads resolve conflicts), Q145 (safe coordination under restriction). No observed run. |
| **Open questions** | Round 2 CREL08 probes may show this is a use case of its own, "orchestrate JPM around one institution", with agreed JPM ownership as a value distinct from the relationship judgment; the model revision held it as a scenario because the evidence is about authority, not an observed run. How duplicate outreach and hidden activity are detected in practice. Business heads have no actor record and have not been interviewed. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | On the intent model owner's admission decision, or after Round 2 CREL08 returns. |
| **Review triggers** | An observed cross-JPM overlap episode; evidence that agreed JPM ownership is a value distinct from the relationship judgment, which would make this a use case; changed orchestration authority or arbitration model. |
| **Supersession links** | None. Replaces the exception row "another JPM team plans engagement" in `BUC-GIB-REL-01` revision 1.0. |
| **Change rationale** | Raised by the model revision of 2026-10-07 and not admitted. The cross-JPM overlap changes the path of the parent's steps 3 to 5 and its participants, so it is a scenario rather than an exception row; it does not change the value delivered, so it is not yet a use case. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-07 | Q94, Q104, Q141, Q142, Q145 re-read under the model revision of 2026-10-07; no new evidence | Raised as a candidate scenario at `Evidence-backed`; not admitted. Promotion to a use case deferred to Round 2 CREL08. | Pending: Coverage intent model owner | `BUC-GIB-REL-01`, `JF-GIB-REL-01`, `JTBD-GIB-REL-01` |

# JF-GIB-REL-01 - Client Relationship Management

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that judges and strengthens institution-level relationship quality through meaningful markers, purposeful engagement, orchestration, and follow-through. |
| **Business purpose** | Preserve JPM relevance, trust, permission to influence, and the right to compete across priority client institutions. |
| **Lifecycle position** | Cross-lifecycle and enduring across business-as-usual, origination, execution, and post-close work. |
| **Scope boundary** | Begins with institution-level relationship review or material change and ends when an accepted objective and engagement disposition are owned, the purposeful contact that disposition calls for has been sent or deliberately withheld, or deliberate waiting is established. |
| **Included work** | Assess relationship markers and trajectory; judge senior attention; set objective and stakeholder; choose engagement, delegation, orchestration, commitment movement, repair, or wait; revisit marker changes; execute a purposeful client contact by message or call in the banker's voice, including the decision not to send; orchestrate JPM's posture, sequence and lead ownership when several parts of JPM touch one institution. |
| **Excluded work** | Preparing, conducting and converting one consequential client meeting (`JF-GIB-MEET-01`); stewarding an opportunity (`JF-GIB-PIPE-01`); triaging a signal before it is routed (`JF-GIB-INTEL-01`); resolving a commitment that has drifted past its threshold or is waiting on the senior (`JF-GIB-ACT-01`, candidate); fulfilling the commitment a contact creates, which stays with its accountable owner. Purposeful contact and cross-JPM orchestration are not excluded: they are this family's execution work. |
| **Primary business outcomes** | [`BO-GIB-REL-01`](../business-outcomes/BO-GIB-REL-01.md) |
| **Business use cases** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md); [`BUC-GIB-REL-02`](../business-use-cases/BUC-GIB-REL-02.md) (candidate, not admitted) |
| **JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md) |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate, not admitted) as preparing and delegated contributor; product and regional partners and business heads remain `[validate]`. |
| **Adjacent job families** | [`JF-GIB-INTEL-01`](JF-GIB-INTEL-01.md) intelligence triage, which hands a contact disposition to this family at its step 6; [`JF-GIB-PIPE-01`](JF-GIB-PIPE-01.md) opportunity pipeline stewardship, which receives a disputed or recognised opportunity by accountable owner; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) consequential client meetings, which receives a consequential interaction and returns a follow-up contact; `JF-GIB-ACT-01` (candidate, not admitted) actions and commitments, which receives only commitments that cross the drift threshold. |
| **Common business rules and controls** | Coverage MD orchestrates the institution-level relationship (Q104); cadence varies by tier and triggers review, not contact (Q33, Q99); listening is legitimate (Q100); sensitivity and client benefit govern engagement; the six Q12 judgments stay with the banker. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the entitled group, others may know that a restricted situation exists and who owns it; further visibility depends on the restriction; Coverage orchestrates and business heads arbitrate. |
| **Known variations** | Priority tier, trajectory, stakeholder role, relationship risk, commitment significance, geography, and sponsor versus corporate context `[validate]`; contextual change, time-sensitive risk, cadence and cross-JPM overlap are the four scenarios of `BUC-GIB-REL-01`. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q92-Q111; Q11, Q12, Q98, Q100 for purposeful contact; Q94, Q104, Q142 for cross-JPM orchestration. |
| **Evidence maturity** | `Evidence-backed` |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-REL-01` | Review and direct a priority client relationship | Produces an accepted institution-level judgment and disposition. | Ends at the disposition; a contact hands to `BUC-GIB-REL-02`, a consequential meeting to `JF-GIB-MEET-01`, and each other movement to its accountable owner's family. |
| `BUC-GIB-REL-02` (candidate, not admitted) | Execute a purposeful client contact | Produces one approved, coherent client contact or an explicit decision not to send, which is relationship execution in the banker's own voice. | Distinct from `BUC-GIB-REL-01` by unit of value (a contact, not a judgment); distinct from `JF-GIB-MEET-01` because no consequential fixed window exists. |
| `JTBD-GIB-REL-01` | Strengthen priority client relationships | Expresses the enduring relationship progress sought. | Confirmed for Senior Coverage MDs by one participant. |
| `SC-GIB-REL-01-A` to `-C` | Contextual change; time-sensitive risk or commitment; tier-based cadence | Variations of `BUC-GIB-REL-01` with the same value delivered. | A re-scoped at 1.1 so A, B and C are mutually exclusive. |
| `SC-GIB-REL-01-D` (candidate, not admitted) | Cross-JPM overlap on one institution | Variation of `BUC-GIB-REL-01` in which posture, sequence and lead owner across JPM are the open question. | Round 2 CREL08 may promote it to a use case. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader relationship-owner and product-partner validation, or on the admission decision for `BUC-GIB-REL-02` and `SC-GIB-REL-01-D`. |
| **Review triggers** | Changed orchestration authority, institution boundary, marker model, engagement boundary, cross-LOB evidence, or admission of the candidate use case, scenario or adjacent actions family. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: included work now names purposeful contact and cross-JPM orchestration; excluded work corrected so it no longer implies all execution leaves the family; candidate use case and scenario listed without admission; adjacent families reference `JF-GIB-ACT-01` (candidate) instead of an uncatalogued actions area; cross-family control rule added. Definition, purpose and maturity unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q92-Q111 | Promoted as `Evidence-backed`. | Coverage intent model owner | Relationship outcome, use case, JTBD, and scenarios A-C |
| `1.1` | 2026-10-07 | No new evidence; Q11, Q12, Q94, Q98, Q100, Q104, Q142, Q145 re-read under the model revision of 2026-10-07 | Revised in place. Scope and included work widened to the family's own execution work; excluded work corrected; `BUC-GIB-REL-02`, `SC-GIB-REL-01-D` and `ACTOR-COV-SUPPORT-TEAM` listed as candidates raised by the model revision and not admitted; control rule added. Maturity unchanged. | Coverage intent model owner | `BUC-GIB-REL-01`, `BUC-GIB-REL-02` (candidate), `SC-GIB-REL-01-A`, `SC-GIB-REL-01-D` (candidate), `JTBD-GIB-REL-01` |

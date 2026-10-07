# JF-GIB-REL-01 - Client Relationship Management

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that judges and strengthens institution-level relationship quality. It reads meaningful signs, makes purposeful contact, coordinates JPM, and follows through. |
| **Business purpose** | Preserve JPM's relevance, trust, permission to influence, and right to compete across priority client institutions. |
| **Lifecycle position** | Enduring work that runs across every stage: business-as-usual, origination, execution, and post-close. |
| **Scope boundary** | Begins with an institution-level relationship review or a material change. Ends when an owner holds an accepted objective and a Decision on how to engage. The purposeful contact that Decision calls for has then been sent or deliberately withheld, or a deliberate wait is in place. |
| **Included work** | Assess relationship signs and direction; judge senior attention; set the objective and the stakeholder; choose to engage, delegate, coordinate, move a commitment, repair, or wait; revisit changed signs; make a purposeful client contact by message or call in the banker's voice, including the Decision not to send; coordinate JPM's posture, sequence and lead owner when several parts of JPM touch one institution. |
| **Excluded work** | Preparing, conducting and converting one high-stakes client meeting (`JF-GIB-MEET-01`); managing an opportunity (`JF-GIB-PIPE-01`); triaging a Signal before it is sent on (`JF-GIB-INTEL-01`); resolving a commitment that has drifted past its threshold or is waiting on the senior (`JF-GIB-ACT-01`, candidate); fulfilling the commitment a contact creates, which stays with its owner. Purposeful contact and cross-JPM coordination are not excluded: they are this family's execution work. |
| **Primary business outcomes** | [`BO-GIB-REL-01`](../business-outcomes/BO-GIB-REL-01.md) |
| **Business use cases** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md); [`BUC-GIB-REL-02`](../business-use-cases/BUC-GIB-REL-02.md) (candidate, not admitted) |
| **JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md) |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate, not admitted) as preparing and delegated contributor; product and regional partners and business heads remain `[validate]`. |
| **Adjacent job families** | [`JF-GIB-INTEL-01`](JF-GIB-INTEL-01.md) intelligence triage, which hands a contact Decision to this family at its step 6; [`JF-GIB-PIPE-01`](JF-GIB-PIPE-01.md) opportunity pipeline management, which receives a disputed or recognised opportunity by owner; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) high-stakes client meetings, which receives a high-stakes meeting and returns a follow-up contact; `JF-GIB-ACT-01` (candidate, not admitted) actions and commitments, which receives only commitments that cross the drift threshold. |
| **Common business rules and controls** | The Coverage MD coordinates the institution-level relationship (Q104). Contact frequency varies by tier and triggers a review, not a contact (Q33, Q99). Listening is legitimate (Q100). Sensitivity and client benefit govern any contact. The six Q12 judgments stay with the banker. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Known variations** | Priority tier, direction, stakeholder role, relationship risk, commitment significance, geography, and sponsor versus corporate context `[validate]`. Contextual change, time-sensitive risk, contact frequency and cross-JPM overlap are the four scenarios of `BUC-GIB-REL-01`. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q92-Q111; Q11, Q12, Q98, Q100 for purposeful contact; Q94, Q104, Q142 for cross-JPM coordination. |
| **Evidence maturity** | `Evidence-backed` |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-REL-01` | Review and direct a priority client relationship | Produces an accepted institution-level judgment and Decision. | Ends at the Decision. A contact hands to `BUC-GIB-REL-02`, a high-stakes meeting to `JF-GIB-MEET-01`, and each other next step to its owner's family. |
| `BUC-GIB-REL-02` (candidate, not admitted) | Execute a purposeful client contact | Produces one approved, coherent client contact or an explicit Decision not to send. That is relationship execution in the banker's own voice. | Distinct from `BUC-GIB-REL-01` by unit of value: a contact, not a judgment. Distinct from `JF-GIB-MEET-01` because no high-stakes fixed window exists. |
| `JTBD-GIB-REL-01` | Strengthen priority client relationships | Expresses the enduring relationship progress sought. | Confirmed for Senior Coverage MDs by one participant. |
| `SC-GIB-REL-01-A` to `-C` | Contextual change; time-sensitive risk or commitment; tier-based contact frequency | Variations of `BUC-GIB-REL-01` with the same value delivered. | A re-scoped at 1.1 so A, B and C are mutually exclusive. |
| `SC-GIB-REL-01-D` (candidate, not admitted) | Cross-JPM overlap on one institution | Variation of `BUC-GIB-REL-01` in which posture, sequence and lead owner across JPM are the open question. | Round 2 CREL08 may promote it to a use case. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader relationship-owner and product-partner validation, or on the admission decision for `BUC-GIB-REL-02` and `SC-GIB-REL-01-D`. |
| **Review triggers** | Changed coordination authority, institution boundary, model of relationship signs, contact boundary, cross-LOB evidence, or admission of the candidate use case, scenario or adjacent actions family. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: included work now names purposeful contact and cross-JPM coordination; excluded work corrected so it no longer implies all execution leaves the family; candidate use case and scenario listed without admission; adjacent families reference `JF-GIB-ACT-01` (candidate) instead of an uncatalogued actions area; cross-family control rule added. Definition, purpose and maturity unchanged. Revision 1.2 is a banker-language pass on wording only. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q92-Q111 | Promoted as `Evidence-backed`. | Coverage intent model owner | Relationship outcome, use case, JTBD, and scenarios A-C |
| `1.1` | 2026-10-07 | No new evidence; Q11, Q12, Q94, Q98, Q100, Q104, Q142, Q145 re-read under the model revision of 2026-10-07 | Revised in place. Scope and included work widened to the family's own execution work; excluded work corrected; `BUC-GIB-REL-02`, `SC-GIB-REL-01-D` and `ACTOR-COV-SUPPORT-TEAM` listed as candidates raised by the model revision and not admitted; control rule added. Maturity unchanged. | Coverage intent model owner | `BUC-GIB-REL-01`, `BUC-GIB-REL-02` (candidate), `SC-GIB-REL-01-A`, `SC-GIB-REL-01-D` (candidate), `JTBD-GIB-REL-01` |
| `1.2` | 2026-10-07 | No new evidence; wording only | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | `SC-GIB-REL-01-C` (title reference updated) |

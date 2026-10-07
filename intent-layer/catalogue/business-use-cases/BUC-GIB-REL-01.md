# BUC-GIB-REL-01 - Review And Direct A Priority Client Relationship

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-REL-01`](../business-outcomes/BO-GIB-REL-01.md) |
| **Job family** | [`JF-GIB-REL-01`](../job-families/JF-GIB-REL-01.md) |
| **Value delivered** | An accepted relationship-quality judgment, objective, engagement disposition, and owned next movement for a priority client institution. |
| **Collective JTBD(s)** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md); `JTBD-GIB-ACT-01` (candidate, not admitted) is served at step 6, where the next movement gains an owner. |
| **Accountable team or role** | Senior Coverage MD as institution-level relationship orchestrator. |
| **Participating roles** | Coverage support team, client stakeholder owners, product and regional partners, and relevant commitment owners `[validate]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate, not admitted). |
| **Evidence maturity** | `Evidence-backed` |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | A scheduled institution review, changed client or relationship context, forming client decision, material commitment, cadence condition, or relationship risk. |
| **Starting state** | Relationship quality, trajectory, stakeholder implications, and client agenda may be partially understood or distributed across JPM. |
| **Completion condition** | The institution has an accepted relationship judgment, objective, engagement or wait disposition, and owned next movement. |
| **Resulting state** | Personal engagement, delegated maintenance, cross-JPM coordination, commitment movement, relationship repair, expansion, or deliberate wait can proceed coherently. A disposition to contact the client by message or call hands to `BUC-GIB-REL-02` (candidate). |
| **Out of scope** | Conduct of one client meeting, composing and sending the client contact itself, opportunity stewardship, intelligence triage before routing, and detailed commitment execution. |
| **Frequency and criticality** | Recurring and event-driven; failure can weaken trust, access, relevance, credibility, or the right to compete. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Judge institution-level relationship quality and direct the appropriate JPM response. | Decides senior attention, objective, stakeholder, engagement posture, orchestration, and deliberate wait. | Requires meaningful markers and context without pretending the client agenda is fully knowable. | `ACTOR-COV-SENIOR-MD` |
| Coverage support team (candidate) | Maintain stakeholder, interaction, commitment, and footprint context; prepare the institution case; execute delegated maintenance within agreed authority. | Contribute evidence and own delegated engagement; the institution judgment stays with the MD. | Distributed context, confidentiality, client fatigue, and cross-JPM coordination. | `ACTOR-COV-SUPPORT-TEAM` (candidate, Q04, Q22, Q35, Q107) |
| Product and regional partners | Declare their own planned and recent contact and contribute product and regional context. | Hold their own client contact; conflicts over ownership or positioning go to business heads (Q142). | May know of a restricted situation only as existing and owned (Q145). | `[validate actor]` |
| Business heads | Arbitrate ownership, client contact, or product and regional priority conflicts the Coverage MD cannot resolve (Q142). | Final say on contested ownership. | A different cohort, not interviewed. | `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-REL-01-S1` | Establish institution change and trajectory. | Coverage support team, Senior Coverage MD | Client agenda markers, stakeholder map, JPM footprint, interactions, commitments, competition, trajectory. | Decide why attention may be needed now. | Gather only context material to the institution judgment. | Prepared institution-level case. |
| `BUC-GIB-REL-01-S2` | Interpret relationship-quality markers. | Senior Coverage MD, contributors | Trust, candor, access, reciprocity, engagement, initiation, contact pattern. | Judge current quality and direction without false precision. | Resolve contradictory context where material. | Accepted relationship-quality judgment. |
| `BUC-GIB-REL-01-S3` | Judge whether senior attention is warranted. | Senior Coverage MD | Leverage, risk, commitment significance, timing, tier, trajectory. | Personal attention, delegated maintenance, coordination, or wait. | Bring in relevant partners only where needed. | Senior-attention disposition. |
| `BUC-GIB-REL-01-S4` | Set the relationship objective and stakeholder. | Senior Coverage MD | Desired learning, trust, access, influence, repair, expansion, or commitment. | Choose purposeful outcome and appropriate stakeholder. | Stakeholder and JPM-participant detail remains available on demand. | Relationship objective. |
| `BUC-GIB-REL-01-S5` | Choose the engagement disposition. | Senior Coverage MD | Objective, timing, right to engage, sensitivities, team capability. | Engage, delegate, coordinate, move commitment, repair, expand, or wait. | A contact by message or call hands to `BUC-GIB-REL-02` (candidate); a consequential interaction hands to `BUC-GIB-MEET-01`; other movement goes to its accountable owner. | Owned engagement disposition. |
| `BUC-GIB-REL-01-S6` | Review movement and update judgment. | Senior Coverage MD, Coverage support team | Changed markers, interaction outcome, commitments, relationship trajectory. | Continue, adjust, escalate, delegate, or wait; confirm the next movement has an accepted owner. | Route each next movement to the accountable owner's job family (Q136), with cross-links kept to the others; update linked opportunity, meeting, or intelligence contexts. Only commitments that cross the drift threshold enter `BUC-GIB-ACT-01` (candidate). | Current relationship judgment with owned next movement. Serves `JTBD-GIB-ACT-01` (candidate). |

## Scenarios

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| [`SC-GIB-REL-01-A`](../scenarios/SC-GIB-REL-01-A.md) | Contextual change in the client institution: agenda, leadership, ownership or strategic change (Q97). Re-scoped at revision 1.1 from a general institution review so it no longer duplicates C. | Which markers and stakeholders are re-read; how far the prior judgment still holds. | Institution-level judgment, objective, and disposition. |
| [`SC-GIB-REL-01-B`](../scenarios/SC-GIB-REL-01-B.md) | Time-sensitive risk or commitment | Urgency and direct senior involvement. | Purposeful response protects or advances relationship quality. |
| [`SC-GIB-REL-01-C`](../scenarios/SC-GIB-REL-01-C.md) | Tier-based cadence review | Required response varies by tier and trajectory. | Cadence triggers judgment, not automatic purposeless contact. |
| [`SC-GIB-REL-01-D`](../scenarios/SC-GIB-REL-01-D.md) (candidate, not admitted) | Cross-JPM overlap on one institution: another JPM team plans or has made contact; overlap, conflicting positioning or hidden activity surfaces (Q94, Q104, Q142). | S3 to S5 centre on posture, sequence and lead owner across JPM; business heads arbitrate unresolved ownership. | One institution-level judgment and disposition; Coverage MD orchestrates. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| Relationship markers conflict. | Interaction, stakeholder, or JPM evidence points in different directions. | Preserve uncertainty and seek targeted context rather than force a score. | Qualified relationship judgment. |
| No engagement is warranted. | Tier, trajectory, purpose, or right-to-engage test fails. | Deliberate wait or delegated maintenance with reassessment condition. | Relationship remains governed without unnecessary contact. |
| The reason for attention rests on restricted evidence. | S1 or S2 draws on evidence outside the entitled group. | Apply the control rule below; the judgment is made by those entitled, others know it exists and who owns it. | Governed judgment without disclosure. |

The former exception "another JPM team plans engagement" is now scenario D, because it changes the path of S3 to S5 rather than interrupting it.

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Increased candor and access; clients seek JPM's view; reciprocal commitments resolve; contact remains meaningful; relevance and right to compete persist. |
| **Failure consequences** | Weakened trust, narrow access, duplicate or purposeless outreach, missed commitments, lost relevance, or relationship concentration. |
| **Current process and pain** | Client and stakeholder context is incomplete and distributed; cross-JPM coordination and follow-through can reinforce information gaps `[validate observed process]`. |
| **Business rules and controls** | Coverage orchestrates the institution relationship (Q104); listening is valid (Q100); cadence varies by tier and triggers review, not contact (Q33, Q99); client benefit and sensitivity govern engagement. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the entitled group, others may know that a restricted situation exists and who owns it; further visibility depends on the restriction; Coverage orchestrates and business heads arbitrate. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q92-Q111; Q136 for routing by accountable owner; Q142 and Q145 for the control rule. |
| **Open questions** | Validate contributing actors, observed review episodes, relationship marker measurement, and cross-LOB applicability. Boundary with `BUC-GIB-REL-02` (candidate): the review ends at a disposition and the contact begins there; confirm with an observed episode (CREL07, CREL12). Whether scenario D becomes a use case of its own (CREL08). |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed relationship reviews and contributor validation, or on the admission decision for `BUC-GIB-REL-02` and `SC-GIB-REL-01-D`. |
| **Review triggers** | Changed trigger, completion, value delivered, orchestration authority, marker model, or boundary with meetings, client contact and commitments. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: steps and value unchanged. Scenario A re-scoped and scenario D added as a candidate; the cross-JPM exception row moved to D; routing at S6 restated by accountable owner (Q136) with the candidate actions job cited; cross-family control rule added; candidate support-team actor named where the contributor row previously read `[validate actor]`. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q92-Q111 confirmed-intent synthesis | Promoted as `Evidence-backed`; contributor roles and observed process remain open. | Coverage intent model owner | Relationship outcome, family, JTBD, and scenarios A-C |
| `1.1` | 2026-10-07 | No new evidence; Q94, Q104, Q136, Q142, Q145 re-read under the model revision of 2026-10-07 | Revised in place. Scenario A re-scoped to contextual change; scenario D (candidate) added and the matching exception row retired; S6 routes by accountable owner and serves `JTBD-GIB-ACT-01` (candidate); control rule added; `BUC-GIB-REL-02` (candidate) named as the destination of a contact disposition. Candidates raised by the model revision are not admitted. Maturity unchanged. | Coverage intent model owner | `SC-GIB-REL-01-A`, `SC-GIB-REL-01-D` (candidate), `BUC-GIB-REL-02` (candidate), `JF-GIB-REL-01`, `JTBD-GIB-REL-01` |

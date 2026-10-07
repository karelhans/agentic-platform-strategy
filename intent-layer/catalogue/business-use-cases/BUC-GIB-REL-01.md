# BUC-GIB-REL-01 - Review And Direct A Priority Client Relationship

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-REL-01`](../business-outcomes/BO-GIB-REL-01.md) |
| **Job family** | [`JF-GIB-REL-01`](../job-families/JF-GIB-REL-01.md) |
| **Value delivered** | An accepted relationship-quality judgment, an objective, a Decision on how to engage, and an owned next step for a priority client institution. |
| **Collective JTBD(s)** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md); `JTBD-GIB-ACT-01` (candidate, not admitted) is served at step 6, where the next step gains an owner. |
| **Accountable team or role** | Senior Coverage MD, who coordinates the institution-level relationship. |
| **Participating roles** | Coverage support team, client stakeholder owners, product and regional partners, and relevant commitment owners `[validate]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate, not admitted). |
| **Evidence maturity** | `Evidence-backed` |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | A scheduled institution review, a change in client or relationship context, a forming client decision, a material commitment, an Engagement-frequency condition, or a relationship risk. |
| **Starting state** | Relationship quality, direction, stakeholder implications, and client priorities may be partly understood or spread across JPM. |
| **Completion condition** | The institution has an accepted relationship judgment, an objective, a Decision to engage or wait, and an owned next step. |
| **Resulting state** | Personal Engagement, delegated maintenance, cross-JPM coordination, commitment movement, relationship repair, expansion, or a deliberate wait can proceed coherently. A Decision to engage the client by message or call hands to `BUC-GIB-REL-02` (candidate). |
| **Out of scope** | Conducting one client Interaction, composing and sending the client Engagement itself, opportunity management, Signal triage before the Signal is sent on, and detailed commitment execution. |
| **Frequency and criticality** | Recurring and event-driven. Failure can weaken trust, access, relevance, credibility, or the right to compete. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Judge institution-level relationship quality and direct the appropriate JPM response. | Decides senior attention, objective, stakeholder, posture toward the client, coordination, and deliberate wait. | Needs meaningful signs and context without pretending the client's priorities are fully knowable. | `ACTOR-COV-SENIOR-MD` |
| Coverage support team (candidate) | Maintain stakeholder, Interaction, commitment, and footprint context; prepare the institution case; carry out delegated maintenance within agreed authority. | Contribute evidence and own delegated Engagement; the institution judgment stays with the MD. | Distributed context, confidentiality, client fatigue, and cross-JPM coordination. | `ACTOR-COV-SUPPORT-TEAM` (candidate, Q04, Q22, Q35, Q107) |
| Product and regional partners | Declare their own planned and recent Engagement and contribute product and regional context. | Hold their own client Engagements; conflicts over ownership or positioning go to business heads (Q142). | May know of a restricted situation only as existing and owned (Q145). | `[validate actor]` |
| Business heads | Arbitrate conflicts over ownership, client Engagement, or product and regional priority that the Coverage MD cannot resolve (Q142). | Final say on contested ownership. | A different cohort, not interviewed. | `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-REL-01-S1` | Establish what changed at the institution and its direction. | Coverage support team, Senior Coverage MD | Signs of client priorities, stakeholder map, JPM footprint, Interactions, commitments, competition, direction. | Decide why attention may be needed now. | Gather only context material to the institution judgment. | Prepared institution-level case. |
| `BUC-GIB-REL-01-S2` | Interpret the signs of relationship quality. | Senior Coverage MD, contributors | Trust, candor, access, reciprocity, engagement, initiation, and the Engagement pattern. | Judge current quality and direction without false precision. | Resolve contradictory context where material. | Accepted relationship-quality judgment. |
| `BUC-GIB-REL-01-S3` | Judge whether senior attention is warranted. | Senior Coverage MD | Leverage, risk, commitment significance, timing, tier, direction. | Personal attention, delegated maintenance, coordination, or wait. | Bring in relevant partners only where needed. | Decision on senior attention. |
| `BUC-GIB-REL-01-S4` | Set the relationship objective and stakeholder. | Senior Coverage MD | Desired learning, trust, access, influence, repair, expansion, or commitment. | Choose the purposeful outcome and the appropriate stakeholder. | Stakeholder and JPM-participant detail stays available on demand. | Relationship objective. |
| `BUC-GIB-REL-01-S5` | Decide how to engage. | Senior Coverage MD | Objective, timing, right to engage, sensitivities, team capability. | Engage, delegate, coordinate, move a commitment, repair, expand, or wait. | An Engagement by message or call hands to `BUC-GIB-REL-02` (candidate). A high-stakes Interaction hands to `BUC-GIB-MEET-01`. Any other next step goes to its owner. | Owned Decision on how to engage. |
| `BUC-GIB-REL-01-S6` | Review the next step and update the judgment. | Senior Coverage MD, Coverage support team | Changed signs, Interaction outcome, commitments, relationship direction. | Continue, adjust, escalate, delegate, or wait; confirm the next step has an accepted owner. | Send each next step to the owner's job family (Q136) and keep cross-links to the others. Update linked opportunity, Interaction, or Signal contexts. Only commitments that cross the drift threshold enter `BUC-GIB-ACT-01` (candidate). | Current relationship judgment with an owned next step. Serves `JTBD-GIB-ACT-01` (candidate). |

## Scenarios

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| [`SC-GIB-REL-01-A`](../scenarios/SC-GIB-REL-01-A.md) | Contextual change in the client institution: a change in priorities, leadership, ownership or strategy (Q97). Re-scoped at revision 1.1 from a general institution review so it no longer duplicates C. | Which signs and stakeholders are re-read; how far the prior judgment still holds. | Institution-level judgment, objective, and Decision. |
| [`SC-GIB-REL-01-B`](../scenarios/SC-GIB-REL-01-B.md) | Time-sensitive risk or commitment | Urgency and direct senior involvement. | A purposeful response protects or advances relationship quality. |
| [`SC-GIB-REL-01-C`](../scenarios/SC-GIB-REL-01-C.md) | Tier-based Engagement frequency review | The required response varies by tier and direction. | Engagement frequency triggers judgment, not automatic purposeless Engagement. |
| [`SC-GIB-REL-01-D`](../scenarios/SC-GIB-REL-01-D.md) (candidate, not admitted) | Cross-JPM overlap on one institution: another JPM team plans or has made an Engagement; overlap, conflicting positioning or hidden activity surfaces (Q94, Q104, Q142). | S3 to S5 centre on posture, sequence and lead owner across JPM; business heads arbitrate unresolved ownership. | One institution-level judgment and Decision; the Coverage MD coordinates. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| Relationship signs conflict. | Interaction, stakeholder, or JPM evidence points in different directions. | Keep the uncertainty and seek targeted context rather than force a score. | Qualified relationship judgment. |
| No Engagement is warranted. | The tier, direction, purpose, or right-to-engage test fails. | Deliberate wait or delegated maintenance, with a condition for reassessment. | The relationship stays governed without unnecessary Engagement. |
| The reason for attention rests on restricted evidence. | S1 or S2 draws on evidence outside the group with access. | Apply the control rule below. Those with access make the judgment; others know it exists and who owns it. | Governed judgment without disclosure. |

The former exception "another JPM team plans engagement" is now scenario D, because it changes the path of S3 to S5 rather than interrupting it.

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Candor and access increase; clients seek JPM's view; reciprocal commitments resolve; Engagement stays meaningful; relevance and the right to compete persist. |
| **Failure consequences** | Weakened trust, narrow access, duplicate or purposeless outreach, missed commitments, lost relevance, or relationship concentration. |
| **Current process and pain** | Client and stakeholder context is incomplete and spread across JPM. Cross-JPM coordination and follow-through can widen information gaps `[validate observed process]`. |
| **Business rules and controls** | Coverage coordinates the institution relationship (Q104). Listening is valid (Q100). Engagement frequency varies by tier and triggers a review, not an Engagement (Q33, Q99). Client benefit and sensitivity govern any Engagement. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q92-Q111; Q136 for sending each next step to its owner; Q142 and Q145 for the control rule. |
| **Open questions** | Validate contributing actors, observed review episodes, measurement of relationship signs, and cross-LOB applicability. Boundary with `BUC-GIB-REL-02` (candidate): the review ends at a Decision and the Engagement begins there; confirm with an observed episode (CREL07, CREL12). Whether scenario D becomes a use case of its own (CREL08). |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.3` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed relationship reviews and contributor validation, or on the admission decision for `BUC-GIB-REL-02` and `SC-GIB-REL-01-D`. |
| **Review triggers** | Changed trigger, completion, value delivered, coordination authority, model of relationship signs, or boundary with Interactions, client Engagement and commitments. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: steps and value unchanged. Scenario A re-scoped and scenario D added as a candidate; the cross-JPM exception row moved to D; sending at S6 restated by owner (Q136) with the candidate actions job cited; cross-family control rule added; candidate support-team actor named where the contributor row previously read `[validate actor]`. Revision 1.2 is a banker-language pass on wording only. Revision 1.3 is a terminology pass on wording only: Interaction and Engagement adopted as governed terms. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q92-Q111 confirmed-intent synthesis | Promoted as `Evidence-backed`; contributor roles and observed process remain open. | Coverage intent model owner | Relationship outcome, family, JTBD, and scenarios A-C |
| `1.1` | 2026-10-07 | No new evidence; Q94, Q104, Q136, Q142, Q145 re-read under the model revision of 2026-10-07 | Revised in place. Scenario A re-scoped to contextual change; scenario D (candidate) added and the matching exception row retired; S6 routes by accountable owner and serves `JTBD-GIB-ACT-01` (candidate); control rule added; `BUC-GIB-REL-02` (candidate) named as the destination of a contact disposition. Candidates raised by the model revision are not admitted. Maturity unchanged. | Coverage intent model owner | `SC-GIB-REL-01-A`, `SC-GIB-REL-01-D` (candidate), `BUC-GIB-REL-02` (candidate), `JF-GIB-REL-01`, `JTBD-GIB-REL-01` |
| `1.2` | 2026-10-07 | No new evidence; wording only | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | `SC-GIB-REL-01-C` (title reference updated) |
| `1.3` | 2026-10-07 | No new evidence; wording only | Terminology: Interaction (a live exchange with a client: call, virtual or in person) and Engagement (any client contact, including email) adopted as governed terms. Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | `SC-GIB-REL-01-C`, `BUC-GIB-REL-02` (title references updated) |

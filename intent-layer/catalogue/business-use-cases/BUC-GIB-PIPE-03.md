# BUC-GIB-PIPE-03 - Review The Portfolio And Redirect Effort

> **Candidate record.** Raised by the model revision of 2026-10-07 and not admitted. The admission rule in charter section 6 has not been met: no forum has been observed and no concrete episode exists (Q139). Consumers must not build on this record until the Coverage intent model owner admits it.

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-PIPE-01`](../business-outcomes/BO-GIB-PIPE-01.md) - Improve opportunity portfolio accuracy; this use case is where effort allocation across opportunities is decided. |
| **Job family** | [`JF-GIB-PIPE-01`](../job-families/JF-GIB-PIPE-01.md) - Opportunity pipeline management. |
| **Value delivered** | An accepted shared picture of the portfolio with any warranted effort, ownership, pursuit, or capacity redirections made explicit. |
| **Collective JTBD(s)** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) - Maintain disciplined opportunity management. Step S5 also serves `JTBD-GIB-ACT-01` (candidate): an accepted owner and explicit next commitment for each redirection. |
| **Accountable team or role** | The forum's chair, normally the Senior Coverage MD or business head who owns the portfolio under review `[validate actor]`. Opportunity owners accept redirections that concern them. |
| **Participating roles** | Senior Coverage MD, accountable opportunity owners, Coverage and product bankers, business heads as conflict resolvers `[validate actor]`, and the supporting cohort that prepares the current picture (`ACTOR-COV-SUPPORT-TEAM`, candidate). |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-PIPELINE-TEAM`](../actors/ACTOR-COV-PIPELINE-TEAM.md); `ACTOR-COV-SUPPORT-TEAM` (candidate); business heads `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` - Q146 describes the forum and its two purposes. Q114 and Q24 give the effort judgment, and Q113 the outlook purpose. No forum has been observed and no concrete episode exists (Q139). |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | A scheduled management or planning forum. |
| **Starting state** | Participants may hold inconsistent or stale views of several opportunities at different maturities. Not every opportunity warrants a changed decision. Time may be spent reconstructing facts rather than exercising judgment (Q146). |
| **Completion condition** | Participants share one accepted current picture of the reviewed portfolio. Every warranted redirection of effort, ownership, pursuit, or capacity is explicit with an owner. |
| **Resulting state** | Owners carry redirections into the opportunities they manage. Opportunities whose judgment changed enter [`BUC-GIB-PIPE-01`](BUC-GIB-PIPE-01.md) as a review trigger. The next forum can review progress against this picture. |
| **Out of scope** | Reviewing one opportunity in depth (`BUC-GIB-PIPE-01`), recognising new ideas (`BUC-GIB-PIPE-02`), execution milestones, individual task follow-through, and the format of any status report. |
| **Frequency and criticality** | Recurs with each forum. Failure produces status theatre, unchallenged optimism, or effort left where senior judgment can no longer change the outcome (Q114). |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Align the picture, challenge changed opportunities, and decide where the firm's effort should move. | Decides effort and ownership moves within their authority. Coordinates Coverage across products and regions. | Portfolio context is shared across the forum. Senior time is scarce. | `ACTOR-COV-SENIOR-MD` |
| Coverage opportunity team | Bring the current state of owned opportunities; accept redirections. | Accountable owners accept or contest redirections that concern them. | Views may be stale or inconsistent at the outset. | `ACTOR-COV-PIPELINE-TEAM` |
| Business heads | Resolve conflicts over ownership, client contact, or product and regional priorities that the forum surfaces (Q142). | Arbitrate; do not own opportunities. | A different cohort, not interviewed. | `[validate actor]` |
| Supporting cohort | Prepare the current picture so the forum spends time on judgment rather than reconstruction. | Prepares; does not decide. | Senior-ready bar (Q04, Q35). | `ACTOR-COV-SUPPORT-TEAM` (candidate) `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-PIPE-03-S1` | Select opportunities for review. | Forum chair, supporting cohort | Material change since the last forum, approaching decision windows, disputed states, and the forum's purpose. | Decide which opportunities enter the discussion and why (Q146). | Owners flag opportunities they want challenged. | A bounded review set. |
| `BUC-GIB-PIPE-03-S2` | Align the current picture. | All participants | Each opportunity's accepted state, owner, next client outcome, and what changed. | Decide where views differ and which view stands for now. | Inconsistent or stale views are reconciled or recorded as plural. | One shared current picture. |
| `BUC-GIB-PIPE-03-S3` | Challenge the changed ones. | Senior Coverage MD, owners, contributors | Evidence changes, direction, client intent, and consequences of delay for opportunities that moved. | Judge whether each changed opportunity's state and direction remain credible. | Deep review of one opportunity goes to `BUC-GIB-PIPE-01` where the forum cannot resolve it. | Challenge-tested picture. |
| `BUC-GIB-PIPE-03-S4` | Trade off across opportunities. | Senior Coverage MD, forum chair | Client decision windows, expected economics, relationship consequence, probability that team effort changes the outcome, and commitments already made (Q24). | Judge where effort should move (Q114). | Business heads resolve conflicts between owners, products, or regions (Q142). | Explicit trade-offs. |
| `BUC-GIB-PIPE-03-S5` | Decide effort and ownership moves. | Forum chair, accountable owners | The trade-offs and the owners' acceptance. | Decide which redirections are warranted and who owns each. | Serves `JTBD-GIB-ACT-01` (candidate): each redirection has an accepted owner and explicit next commitment. | Redirections with owners. |
| `BUC-GIB-PIPE-03-S6` | Record and send to owners. | Forum chair, supporting cohort | The accepted picture and the redirections. | Decide what becomes the shared picture for the next forum. | Redirections go to the owner's job family (Q136). Opportunities with changed judgment become `BUC-GIB-PIPE-01` triggers. Only above-threshold items enter `BUC-GIB-ACT-01` (candidate). Restricted detail follows the control rule below. | Accepted portfolio picture with explicit redirections. |

## Scenarios

The scenario axis is the forum's purpose (Q146).

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| [`SC-GIB-PIPE-03-A`](../scenarios/SC-GIB-PIPE-03-A.md) | Alignment-only forum | The forum establishes a common picture. S4 and S5 produce no redirection unless evidence has changed. | One accepted shared picture. Where there are no redirections, that is stated explicitly. |
| [`SC-GIB-PIPE-03-B`](../scenarios/SC-GIB-PIPE-03-B.md) | Decision forum | The forum is convened to make portfolio, intervention, ownership, or capacity decisions. Business heads may attend. | One accepted shared picture with explicit, owned redirections. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| A decision is forced where evidence has not changed. | The forum debates an opportunity whose state is unchanged since the last review. | The chair distinguishes status alignment from decision-making. No redirection without changed evidence. | No decision theatre. |
| The forum cannot resolve one opportunity. | Challenge exposes disputed evidence or ownership that needs more than forum time. | Send the opportunity to `BUC-GIB-PIPE-01` with its owner. | The forum keeps its portfolio scope. |
| Ownership or priority conflict across products or regions. | Two owners, conflicting outreach, or competing priorities surface. | Business heads arbitrate. Coverage continues to coordinate across the institution (Q142). | One accountable owner per opportunity. |
| Material detail is restricted. | Some participants are outside the group with access. | Discuss only that a restricted situation exists and who owns it, subject to the restriction (Q145). | Safe coordination without unauthorized disclosure. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Participants use one accepted current picture. Redirections occur when warranted and are owned. Reconstruction time and repeated status debate decline (Q146). Senior intervention is placed earlier and more selectively (Q149). |
| **Failure consequences** | Status theatre, unchallenged optimism, excessive review, effort left where it no longer changes the outcome, or no ownership after a changed judgment. |
| **Current process and pain** | The essential output today is a shared current status report. Much forum time goes to reconstructing facts rather than exercising judgment (Q146) `[validate with observed forum]`. |
| **Business rules and controls** | Do not force a decision where evidence has not changed. Distinguish status alignment from decision-making (Q146). Preserve plural early views in the shared picture. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q146 (forum purposes), Q114 (where effort should move), Q24 (capacity priority factors), Q113 (outlook and effort as the purpose of discipline); model revision proposal of 2026-10-07, section 4.2 and the pipeline family inventory. No forum observed; Q139: no concrete episode. |
| **Open questions** | Which forums exist by LOB, who chairs and attends, and which decisions each is authorized to make `[validate]`; the business-head role `[validate actor]`; an observed forum (Round 2 CPIPE09, CPIPE12). |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a real management or planning forum is observed, or when the owner decides on admission. |
| **Review triggers** | An observed forum; evidence that the forum's value is the same as one-opportunity review after all; changed forum purpose, decision authority, or participants; admission of a business-head actor record. |
| **Supersession links** | Promoted from scenario [`SC-GIB-PIPE-01-A`](../scenarios/SC-GIB-PIPE-01-A.md) revision `1.0`, now `Superseded`; its two Q146 modes become `SC-GIB-PIPE-03-A` and `SC-GIB-PIPE-03-B`. Takes the recurring-forum half of the `BUC-GIB-PIPE-01` revision `2.0` trigger. |
| **Change rationale** | Revision `0.2`: banker-language pass; wording only, meaning unchanged. Revision `0.1`: raised by the model revision of 2026-10-07 and not admitted. The use case test showed that the unit of value of the forum is the portfolio, not one opportunity. So the recurring session fails the scenario test and passes the use case test. Held at `Candidate` pending an observed forum. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested the pipeline family against Q01-Q151 | Raised as a candidate, promoted from `SC-GIB-PIPE-01-A`; `Evidence-backed`, no forum observed; not admitted. | Coverage intent model owner (as candidate, not admitted) | `BUC-GIB-PIPE-01`, `SC-GIB-PIPE-01-A`, `SC-GIB-PIPE-03-A`, `SC-GIB-PIPE-03-B`, `JTBD-GIB-PIPE-01`, `JF-GIB-PIPE-01`, `BO-GIB-PIPE-01` |
| `0.2` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner (as candidate, not admitted) | None; wording only |

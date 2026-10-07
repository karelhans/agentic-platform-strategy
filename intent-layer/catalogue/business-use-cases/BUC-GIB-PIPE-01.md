# BUC-GIB-PIPE-01 - Review One Opportunity And Decide Its Next Move

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-PIPE-01`](../business-outcomes/BO-GIB-PIPE-01.md) - Improve opportunity portfolio accuracy. |
| **Job family** | [`JF-GIB-PIPE-01`](../job-families/JF-GIB-PIPE-01.md) - Opportunity pipeline management. |
| **Value delivered** | A challenge-tested judgment on one opportunity. It has an accountable owner and a purposeful next step, or a deliberate park or exit. It has an explicit condition for future review. |
| **Collective JTBD(s)** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) - Maintain disciplined opportunity management. Step S5 also serves `JTBD-GIB-ACT-01` (candidate): translate intent into an accepted owner and an explicit next commitment. |
| **Accountable team or role** | Coverage-led opportunity management group; the accountable opportunity owner accepts the shared state and the next step. |
| **Participating roles** | Senior Coverage MD, accountable opportunity owner, Coverage and product bankers, relevant regional and specialist contributors, and the supporting cohort that prepares and translates evidence (`ACTOR-COV-SUPPORT-TEAM`, candidate). Business heads resolve ownership conflicts `[validate actor]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-PIPELINE-TEAM`](../actors/ACTOR-COV-PIPELINE-TEAM.md); `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | `Evidence-backed` - the process is drawn from accepted intent and operating-model answers. It lacks a concrete observed opportunity episode (Q139). |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | For one existing opportunity: material evidence changes, a review condition is reached, or the opportunity needs challenge before more effort is spent. Recognising a new idea is [`BUC-GIB-PIPE-02`](BUC-GIB-PIPE-02.md) (candidate). The recurring management or planning forum is [`BUC-GIB-PIPE-03`](BUC-GIB-PIPE-03.md) (candidate). |
| **Starting state** | The opportunity already has an owner and a shared state. Evidence, client intent, economics, ownership, and maturity may be incomplete or disputed. Interpretations may legitimately differ. |
| **Completion condition** | The reviewed opportunity has an accepted current state and an accountable owner. It has a purposeful next step or a deliberate park or exit decision. It has an explicit condition for future review. |
| **Resulting state** | The shared picture reflects the accepted stage-appropriate judgment without hiding uncertainty. The accountable owner can continue managing the opportunity or carry commitments into their own job family. |
| **Out of scope** | Recognising an idea as an opportunity (`BUC-GIB-PIPE-02`), portfolio-level trade-offs across opportunities (`BUC-GIB-PIPE-03`), detailed task management, execution milestones, enduring relationship management, the process for one client Interaction, and technical system-of-record behavior. |
| **Frequency and criticality** | Event-driven per opportunity. Failure can lose a viable opportunity, distort the outlook, duplicate effort, or consume senior time. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Judge pursuit, the next client outcome, a changed opportunity judgment, and reshape or stop decisions where senior context is required. | Applies institution, relationship, and firm-level judgment. Coordinates Coverage across products and regions. | Needs stage-appropriate evidence without false precision. Works under time, confidentiality, and relationship constraints. | `ACTOR-COV-SENIOR-MD` |
| Coverage opportunity team | Maintain evidence, own the opportunity, carry out the next step, and surface a changed direction or disagreement. | The accountable opportunity owner resolves the shared state, subject to appropriate review and business-head conflict resolution (Q151, Q142). | Evidence is sparse early. Ownership and visibility may cross products, regions, and controls. | `ACTOR-COV-PIPELINE-TEAM` |
| Supporting cohort | Assemble and translate evidence so the review starts from a senior-ready picture. | Prepares; does not accept the state of the opportunity. | Works to the senior-ready bar under time pressure (Q04, Q29, Q35). | `ACTOR-COV-SUPPORT-TEAM` (candidate) `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-PIPE-01-S1` | Receive the review trigger. | Accountable owner, opportunity team | Changed evidence, a reached review condition, a watch condition firing, or a request to challenge before more effort. The opportunity's current shared state. | Decide whether the trigger warrants a review now, and which condition of the opportunity it reflects. | Triggers arrive from Signal triage, relationship work, client Interactions, product teams, or a prior review condition. A recognised idea arrives from `BUC-GIB-PIPE-02`. | One existing opportunity enters review. |
| `BUC-GIB-PIPE-01-S2` | Assemble current evidence and legitimate views. | Accountable owner, opportunity team, supporting cohort | Qualitative or quantitative strategic value, next client outcome, source trail, confidence, freshness, sensitivity, and differing interpretations. | Decide what is known, inferred, disputed, restricted, or missing for the current maturity. | Relevant contributors add evidence without forcing one premature view. | Stage-appropriate evidence set with uncertainty preserved. |
| `BUC-GIB-PIPE-01-S3` | Challenge maturity and direction. | Senior Coverage MD, accountable owner, relevant contributors | Evidence changes, prior assumptions, client intent, relevance to the firm, competitive position, and consequences of delay. | Judge whether the current state and direction remain credible. | Relevant business heads resolve material ownership conflicts. | Challenge-tested opportunity judgment. |
| `BUC-GIB-PIPE-01-S4` | Choose the response. | Senior Coverage MD or accountable owner according to authority | Challenge-tested judgment and the remaining window to intervene. | Advance, reshape, continue learning, monitor, park, reactivate, or exit. | Work that belongs to another family goes to the accountable owner in the relationship, Interaction, or execution job family. | An explicit response on the opportunity. |
| `BUC-GIB-PIPE-01-S5` | Confirm the accountable owner and the next step. | Accountable opportunity owner | Intended client outcome, next meaningful commitment, restrictions, and review need. | Accept ownership and the purposeful next step or re-entry condition. | Serves `JTBD-GIB-ACT-01` (candidate): an accepted owner and an explicit next commitment. Team members and product or regional contributors align to the accepted direction. | Accountable ownership is explicit. |
| `BUC-GIB-PIPE-01-S6` | Update the shared picture and review conditions. | Accountable owner, opportunity team | Accepted judgment, rationale, source trail, sensitivity, next step, and review condition. | Decide what becomes canonical now and what remains a plural or personal view. | Commitments are sent to the owner's job family (Q136). Only commitments above the drift or senior-dependency threshold enter `BUC-GIB-ACT-01` (candidate). Restricted detail follows the control rule below. | Current shared state is available for the next review or progression event. |

## Scenarios

The scenario axis is the condition of the opportunity when the review fires.

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| [`SC-GIB-PIPE-01-B`](../scenarios/SC-GIB-PIPE-01-B.md) | Material change or closing decision window | Urgency and senior involvement increase. | Evidence is challenged and an explicit response is accepted. |
| [`SC-GIB-PIPE-01-C`](../scenarios/SC-GIB-PIPE-01-C.md) | Parked opportunity reactivation | Prior rationale and re-entry evidence become central. | The current opportunity judgment and ownership are renewed. |
| [`SC-GIB-PIPE-01-D`](../scenarios/SC-GIB-PIPE-01-D.md) | Ambiguous early idea after recognition | Evidence is sparse and multiple views may coexist. | Accountable ownership and purposeful learning remain required. |
| [`SC-GIB-PIPE-01-F`](../scenarios/SC-GIB-PIPE-01-F.md) | Deliberate exit | Timing, economics, relationship cost, or dependencies argue for stopping. Closure is minimal. | The exit is a challenge-tested judgment with an owner for the re-entry watch. |
| [`SC-GIB-PIPE-01-G`](../scenarios/SC-GIB-PIPE-01-G.md) | Review condition reached without progress | Ownership, active status, or direction are re-challenged. | An explicit response and owner replace silent persistence. |

Former scenario `SC-GIB-PIPE-01-A` (recurring pipeline management session) is superseded by `BUC-GIB-PIPE-03` (candidate). Former scenario `SC-GIB-PIPE-01-E` (restricted cross-GIB opportunity) is superseded by the cross-family control rule below. Both files are retained for traceability.

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| Evidence is too weak to support active management. | Challenge reveals no credible thesis or next learning. | Park or exit; record re-entry conditions where useful. | A deliberate non-active state rather than silent persistence. |
| Ownership is disputed across products or regions. | Conflicting owners, outreach, or assessments appear. | Relevant business heads resolve the conflict. Coverage continues to coordinate across the institution (Q142). | One accountable opportunity owner and coherent client posture. |
| Material detail is restricted. | An access or control boundary prevents full sharing. | Expose only that a restricted situation exists and who owns it, subject to the restriction (Q145). | Safe coordination without unauthorized disclosure. |
| The accepted next step does not happen. | The review condition is reached without meaningful progress. | Re-challenge the owner, active status, or direction. See `SC-GIB-PIPE-01-G`. | Revised direction, escalation, parking, or exit. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Portfolio accuracy; accountable ownership; deliberate parking or exit; reduced reconstruction effort; fewer viable opportunities lost without review. Earlier idea recognition is measured at `BUC-GIB-PIPE-02`. |
| **Failure consequences** | Lost opportunity or revenue, distorted outlook, duplicated outreach, wasted effort, damaged client trust, or late intervention. |
| **Current process and pain** | Bankers reconstruct pipeline context across fragmented records and personal knowledge. Early client intent is ambiguous. Ownership and follow-through may be inconsistent `[validate with concrete episode]`. |
| **Business rules and controls** | Preserve the source trail and uncertainty. Avoid forced probability. Allow stage-dependent convergence. Keep detailed tasks outside the pipeline's minimum requirements. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. The rule has no value of its own and is never a scenario or a use case. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q13-Q16, Q113-Q117, Q143, Q144, Q151; model revision proposal of 2026-10-07. Q139: no concrete opportunity episode has been supplied. |
| **Open questions** | Validate the process against a concrete opportunity episode (Q139; Round 2 CPIPE03, CPIPE08, CPIPE09, CPIPE12). Test boundaries and role contributions across product bankers and LOBs. Validate data and control rules with accountable stakeholders. Validate the business-head conflict-resolution role with that cohort. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `3.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After a concrete opportunity walkthrough and broader role validation, or when `BUC-GIB-PIPE-02` or `BUC-GIB-PIPE-03` is admitted or rejected. |
| **Review triggers** | Changed trigger, completion condition, value delivered, accountable group, lifecycle boundary, or commitment handoff; evidence that recognition or portfolio review belong back inside this process; admission or rejection of the two candidate use cases. |
| **Supersession links** | Revision `3.0` narrows the trigger of revision `2.0`: recognising a plausible idea moves to `BUC-GIB-PIPE-02` (candidate) and the recurring forum moves to `BUC-GIB-PIPE-03` (candidate). Scenario `SC-GIB-PIPE-01-A` is superseded by `BUC-GIB-PIPE-03`; scenario `SC-GIB-PIPE-01-E` is superseded by the cross-family control rule. Revision `2.0` revised the pre-governance pipeline pilot in place; stable `BUC-GIB-PIPE-01` retained. |
| **Change rationale** | Revision `3.2`: terminology pass (Interaction, Engagement); wording only, meaning unchanged. Revision `3.1`: banker-language pass; wording only, meaning unchanged. Revision `3.0`: the revision `2.0` trigger bundled three differently triggered processes with different units of value: one opportunity, one idea, and the portfolio. The model revision of 2026-10-07 narrows this use case to one existing opportunity. The value delivered is recognisably the same, so the stable ID is kept and the major revision is incremented. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-01 | Pre-confirmation pipeline research and interview through Q112 | Initial evidence-backed runtime interpretation focused on portfolio review and senior intervention. | Pipeline pilot evidence owner | Existing runtime pipeline slice |
| `2.0` | 2026-10-02 | Added Q113-Q151 validation | Revised in place; disciplined stewardship becomes the center and the Idea-to-Closed boundary is accepted for Coverage. | Coverage intent model owner | `JF-GIB-PIPE-01`, `JTBD-GIB-PIPE-01`, actors, and scenarios A-E |
| `3.0` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested every job and use case against Q01-Q151 | Revised in place with a narrowed trigger and title; S1 becomes "receive the review trigger"; scenarios A and E superseded, F and G added; commitment routing changed to the accountable owner's job family (Q136) with `JTBD-GIB-ACT-01` cited at S5; cross-family control rule added. Maturity unchanged at `Evidence-backed`; Q139 gap stands. | Coverage intent model owner | `BUC-GIB-PIPE-02`, `BUC-GIB-PIPE-03`, `JTBD-GIB-PIPE-01`, `JF-GIB-PIPE-01`, `BO-GIB-PIPE-01`, scenarios A-G |
| `3.1` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None; wording only |
| `3.2` | 2026-10-07 | No new source evidence; terminology pass | Terminology: Interaction (a live exchange with a client: call, virtual or in person) and Engagement (any client contact, including email) adopted as governed terms. Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None; wording only |

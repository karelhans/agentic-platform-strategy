# BUC-GIB-INTEL-01 - Triage And Send A Material Signal

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-INTEL-01`](../business-outcomes/BO-GIB-INTEL-01.md) |
| **Job family** | [`JF-GIB-INTEL-01`](../job-families/JF-GIB-INTEL-01.md) |
| **Value delivered** | An accepted Decision, Rationale, intended outcome, and View for a potentially material Signal. |
| **Collective JTBD(s)** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md); [`JTBD-GIB-INTEL-02`](../jtbd/JTBD-GIB-INTEL-02.md) (candidate; the holder's expected follow-through closes at S1); [`JTBD-GIB-ACT-01`](../jtbd/JTBD-GIB-ACT-01.md) (candidate; served by the commitment step at S6). |
| **Accountable team or role** | The Senior Coverage MD decides materiality, sufficient credibility, response, and intended client outcome. The Coverage support team, [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate), carries preparatory triage. |
| **Participating roles** | Coverage support team (VPs, associates, analysts), client and product bankers, research or intelligence contributors, relationship owners, and the owners in the receiving job families `[validate]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate). |
| **Evidence maturity** | `Evidence-backed` |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | New information may materially affect a client, relationship, opportunity, meeting, commitment, or firm outcome. A monitor condition set at S5 that fires is a new trigger. |
| **Starting state** | Information may be noisy, duplicated, weakly connected, or uncertain. Information held by a banker who does not own the affected client reaches this use case through [`BUC-GIB-INTEL-02`](BUC-GIB-INTEL-02.md) (candidate). |
| **Completion condition** | The Signal has an accepted Decision and Rationale, an intended outcome where applicable, and an owner's View or a monitoring condition. |
| **Resulting state** | Material evidence can be acted upon, investigated, monitored, retained, or dismissed without consuming further unowned attention. |
| **Out of scope** | Carrying out outreach, pipeline management, meeting preparation, or downstream commitments; getting held information to its owner in the first place (`BUC-GIB-INTEL-02`, candidate). |
| **Frequency and criticality** | Continuous and event-driven. Consequence ranges from harmless noise to lost credibility, opportunity, or time to act. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Judge materiality, sufficient credibility, response, and intended client outcome. | Can dismiss, retain, monitor, validate, prepare, act, or send to the owner's job family. | Needs concise context, evidence, uncertainty, consequence, and timing without noise. | `ACTOR-COV-SENIOR-MD` |
| Coverage support team (candidate) | Reduce duplication, connect client context, show evidence and confidence, and prepare response options. Carry batch reduction and the composition of connected items. | Can validate and prepare summaries. Material client and firm judgment stays senior. Items meeting a Q74 threshold go direct to the MD. | Source access, confidentiality, context completeness, and time sensitivity. | `ACTOR-COV-SUPPORT-TEAM` (candidate) |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-INTEL-01-S1` | Reduce noise and duplication. | Support team | Repetition, novelty, relevance, existing knowledge; Signals acknowledged in from `BUC-GIB-INTEL-02`. | Decide what warrants context assessment. May run over a batch (scenario D). | Consolidate equivalent evidence. | Reduced candidate set. |
| `BUC-GIB-INTEL-01-S2` | Identify affected clients and context. | Support team | Client priorities, relationships, opportunities, meetings, commitments, and knowledge. | Decide which contexts could materially change the implication. Where several changes converge, compose the connection (scenario E). | Consult relevant owners where permitted. | Client-specific context. |
| `BUC-GIB-INTEL-01-S3` | Explain consequence and evidential strength. | Support team | Potential impact, time window, source, corroboration, uncertainty, missing facts; any targeted validation returned from S5. | Judge what confidence supports which possible use. | Escalate items meeting a Q74 threshold directly to the Senior Coverage MD. | An interpretable case for the Signal. |
| `BUC-GIB-INTEL-01-S4` | Judge the appropriate response. | Senior Coverage MD | The Signal case and client or firm context. | Decide whether it matters, is credible enough, warrants response, and changes the intended outcome. | Seek targeted validation where needed. | Accepted response direction. |
| `BUC-GIB-INTEL-01-S5` | Record the Decision and Rationale. | Senior Coverage MD or delegate | Accepted judgment. | Dismiss, retain, monitor, validate, prepare, or act. A `validate` Decision returns the item to S3 with the question to be answered. A `monitor` Decision sets the condition whose firing is a new trigger. | Set a reassessment condition where relevant. | Explicit Decision. |
| `BUC-GIB-INTEL-01-S6` | Send to the owner's job family. | Decision owner | Intended outcome and accepted Rationale. | Identify the owner for the intended outcome (Q136): relationship, pipeline, meeting, or continued intelligence ownership. Keep cross-references to other affected owners. | The owner receives the context and accepts the next commitment. This commitment step serves [`JTBD-GIB-ACT-01`](../jtbd/JTBD-GIB-ACT-01.md) (candidate). Only items that later cross the drift or dependency threshold enter [`BUC-GIB-ACT-01`](BUC-GIB-ACT-01.md) (candidate). | Owned next step, or a Decision to monitor or dismiss. |

## Scenarios

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| [`SC-GIB-INTEL-01-A`](../scenarios/SC-GIB-INTEL-01-A.md) | Short-window material signal | Urgency and senior attention increase. | Explicit evidence-based Decision and View. |
| [`SC-GIB-INTEL-01-B`](../scenarios/SC-GIB-INTEL-01-B.md) | Uncertain high-impact signal | Validation depth and escalation depend on consequence and time; a `validate` Decision loops back to S3. | Uncertainty stays explicit and the response proportionate. |
| [`SC-GIB-INTEL-01-C`](../scenarios/SC-GIB-INTEL-01-C.md) | Monitor or dismiss | Completion is a reasoned wait, dismissal, or monitor condition; a fired condition is a new trigger. | Decision and Rationale are explicit. |
| [`SC-GIB-INTEL-01-D`](../scenarios/SC-GIB-INTEL-01-D.md) (candidate, `Hypothesis`) | Accumulated signals with no single trigger after an unattended window | S1 runs over the batch; items are ordered for judgment by consequence and window. | Each item ends in its own Decision, including release. |
| [`SC-GIB-INTEL-01-E`](../scenarios/SC-GIB-INTEL-01-E.md) (candidate, `Evidence-backed`) | Converging changes or cross-client implication | S2 and S3 compose the connection; the Decision may dismiss the connection, own it, or pin it. | Exits are this use case's Decisions; each item keeps its source trail. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| Relevant evidence cannot be shared fully. | Access or sensitivity boundary. | Apply the control rule: others may know a restricted situation exists and who owns it. Send only permitted context to the owner. | Restricted evidence remains protected. |
| Confidence is low but consequence is high. | Evidence and impact diverge. | Increase scrutiny according to consequence and remaining time; a `validate` Decision returns to S3. | Validate, escalate as a starting view, or monitor explicitly. |
| No action is justified. | Materiality, credibility, or timing test fails. | Dismiss or monitor, with Rationale and a reassessment condition. | Senior attention is released; a fired monitor condition re-enters as a new trigger. |
| Ownership of the View is contested. | More than one plausible owner across products or regions. | Coverage coordinates at institution level; relevant business heads arbitrate (Q142). | One owner receives the context. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Fewer material surprises; less noise and manual verification; earlier client relevance; better conversations; appropriate Decisions to monitor or dismiss; faster downstream progress. |
| **Failure consequences** | Missed Signal, late response, wasted action, damaged credibility, or senior attention consumed by noise. |
| **Current process and pain** | Relevant evidence may stay fragmented across the bank, disconnected from client context, and hard to trust or send on `[validate operational detail]`. |
| **Business rules and controls** | Preserve the source trail and uncertainty; match scrutiny to impact and time; respect confidentiality; do not imply client action from relevance alone. Direct senior attention thresholds (Q74): high consequence with a short window, relationship-sensitive meaning, strategic ambiguity, a change to a major opportunity, or cross-client or firm-wide implication. These go to the Senior Coverage MD without prior support-team triage. Senior judgment may be asked for at more than one boundary (Q42): after changed evidence is identified, and again after responses are proposed. A `validate` Decision at S5 returns the item to S3. A fired monitor condition is a new trigger of this use case. Sending at S6 follows the owner (Q136). Cross-family control rule (Q70, Q145, Q142): when evidence, outreach, or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q71-Q91; Round 1 record Q39 to Q42, Q57 to Q62, Q70, Q74, Q136, Q142, Q145 as applied by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md). |
| **Open questions** | Validate the support-team cohort as an actor record, source coverage, and observed Decision episodes. Observe a batch resumption and a convergence episode for scenarios D and E. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed intelligence episodes and support-team actor validation; when `BUC-GIB-INTEL-02` or the ACT-01 candidates are admitted or rejected. |
| **Review triggers** | Changed trigger, completion, Decision set, View boundary, owner, value delivered, or evidence that distinct use cases are required. |
| **Supersession links** | None. |
| **Change rationale** | Apply the model revision of 2026-10-07: add candidate scenarios D and E, the Q74 thresholds, the Q42 note, the validate loop, the monitor re-trigger, owner-based sending at S6, the control rule, and the support-team cohort. Steps and value delivered unchanged. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q71-Q91 confirmed-intent synthesis | Promoted as `Evidence-backed`; preparatory role and observed process remain open. | Coverage intent model owner | Intelligence outcome, family, JTBD, and scenarios A-C |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q39 to Q42, Q57 to Q62, Q70, Q74, Q136, Q142, Q145 re-read | Revised in place; no semantic change to steps or value. Candidate scenarios D and E, candidate sibling `BUC-GIB-INTEL-02`, and candidate actor `ACTOR-COV-SUPPORT-TEAM` referenced but not admitted. | `[validate: intent model owner]` | `SC-GIB-INTEL-01-A` to `-E`, `BUC-GIB-INTEL-02`, `JTBD-GIB-INTEL-01`, `JTBD-GIB-INTEL-02`, `JF-GIB-INTEL-01` |
| `1.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Title changed from "Triage And Route Consequential Intelligence". Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

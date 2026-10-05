# BUC-GIB-INTEL-01 - Triage And Route Consequential Intelligence

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-INTEL-01`](../business-outcomes/BO-GIB-INTEL-01.md) |
| **Job family** | [`JF-GIB-INTEL-01`](../job-families/JF-GIB-INTEL-01.md) |
| **Value delivered** | An accepted disposition, rationale, intended outcome, and destination for potentially consequential intelligence. |
| **Collective JTBD(s)** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Accountable team or role** | Senior Coverage MD for materiality, sufficient credibility, response, and intended client outcome; preparatory triage roles remain `[validate]`. |
| **Participating roles** | VPs, associates, client and product bankers, research or intelligence contributors, relationship owners, and destination-lens owners `[validate]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md) |
| **Evidence maturity** | `Evidence-backed` |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | New information may materially affect a client, relationship, opportunity, meeting, commitment, or franchise outcome. |
| **Starting state** | Information may be noisy, duplicated, weakly connected, uncertain, or unevenly shared. |
| **Completion condition** | The intelligence has an accepted disposition and rationale, intended outcome where applicable, and destination lens or monitoring condition. |
| **Resulting state** | Consequential evidence can be acted upon, investigated, monitored, retained, or dismissed without consuming further unowned attention. |
| **Out of scope** | Executing outreach, pipeline stewardship, meeting preparation, or downstream commitments. |
| **Frequency and criticality** | Continuous and event-driven; consequence ranges from harmless noise to lost credibility, opportunity, or intervention time. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Judge materiality, sufficient credibility, response, and intended client outcome. | Can dismiss, monitor, validate, prepare, act, or route to another lens. | Requires concise context, evidence, uncertainty, consequence, and timing without noise. | `ACTOR-COV-SENIOR-MD` |
| Preparatory triage contributors `[validate]` | Reduce duplication, connect client context, expose evidence and confidence, and prepare response options. | Can validate and synthesize; material client and franchise judgment remains senior. | Source access, confidentiality, context completeness, and time sensitivity. | `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-INTEL-01-S1` | Reduce noise and duplication. | Preparatory contributors | Repetition, novelty, relevance, existing knowledge. | Decide what warrants contextual assessment. | Consolidate equivalent evidence. | Reduced candidate set. |
| `BUC-GIB-INTEL-01-S2` | Identify affected clients and context. | Preparatory contributors | Client priorities, relationships, opportunities, meetings, commitments, and knowledge. | Decide which contexts could materially change the implication. | Consult relevant owners where permitted. | Client-specific context. |
| `BUC-GIB-INTEL-01-S3` | Explain consequence and evidential strength. | Preparatory contributors | Potential impact, time window, source, corroboration, uncertainty, missing facts. | Judge what confidence supports which possible use. | Escalate sensitive or short-window evidence. | Interpretable intelligence case. |
| `BUC-GIB-INTEL-01-S4` | Judge the appropriate response. | Senior Coverage MD | Intelligence case and client or franchise context. | Decide whether it matters, is credible enough, warrants response, and changes intended outcome. | Seek targeted validation where needed. | Accepted response direction. |
| `BUC-GIB-INTEL-01-S5` | Record the disposition and rationale. | Senior Coverage MD or delegate | Accepted judgment. | Dismiss, retain, monitor, validate, prepare, or act. | Establish reassessment condition where relevant. | Explicit disposition. |
| `BUC-GIB-INTEL-01-S6` | Route to the destination lens. | Disposition owner | Intended outcome and accepted rationale. | Select relationship, pipeline, meeting, action, or continued intelligence ownership. | Accountable destination owner receives the context. | Owned next progress or deliberate non-action. |

## Scenarios

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| [`SC-GIB-INTEL-01-A`](../scenarios/SC-GIB-INTEL-01-A.md) | Short-window consequential signal | Urgency and senior attention increase. | Explicit evidence-based disposition and destination. |
| [`SC-GIB-INTEL-01-B`](../scenarios/SC-GIB-INTEL-01-B.md) | Uncertain high-impact signal | Validation depth and escalation depend on consequence and time. | Uncertainty remains explicit and response proportionate. |
| [`SC-GIB-INTEL-01-C`](../scenarios/SC-GIB-INTEL-01-C.md) | Deliberate non-action or monitoring | Completion is a reasoned wait, dismissal, or monitor condition. | Disposition and rationale are explicit. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| Relevant evidence cannot be shared fully. | Entitlement or sensitivity boundary. | Route safe context to the accountable owner. | Restricted evidence remains protected. |
| Confidence is low but consequence is high. | Evidence and impact diverge. | Increase scrutiny according to consequence and remaining time. | Validate, escalate as hypothesis, or monitor explicitly. |
| No action is justified. | Materiality, credibility, or timing test fails. | Dismiss or monitor with rationale and reassessment condition. | Senior attention is released. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Fewer consequential surprises; less noise and manual verification; earlier client relevance; better conversations; appropriate non-action; faster downstream movement. |
| **Failure consequences** | Missed signal, late response, wasted action, damaged credibility, or senior attention consumed by noise. |
| **Current process and pain** | Relevant evidence may remain fragmented across the bank, disconnected from client context, and difficult to trust or route `[validate operational detail]`. |
| **Business rules and controls** | Preserve provenance and uncertainty; calibrate scrutiny to impact and time; respect confidentiality; do not imply client action from relevance alone. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q71-Q91. |
| **Open questions** | Validate preparatory actor ownership, source coverage, and observed disposition episodes. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-02 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed intelligence episodes and preparatory-role validation. |
| **Review triggers** | Changed trigger, completion, disposition set, destination boundary, owner, value delivered, or evidence that distinct use cases are required. |
| **Supersession links** | None. |
| **Change rationale** | Promote the existing evidence-backed bounded process without changing its stable steps. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q71-Q91 confirmed-intent synthesis | Promoted as `Evidence-backed`; preparatory role and observed process remain open. | Coverage intent model owner | Intelligence outcome, family, JTBD, and scenarios A-C |

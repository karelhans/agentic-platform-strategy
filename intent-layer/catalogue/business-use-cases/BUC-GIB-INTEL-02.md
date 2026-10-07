# BUC-GIB-INTEL-02 - Bring A Held Signal To Its Accountable Owner

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-INTEL-01`](../business-outcomes/BO-GIB-INTEL-01.md) |
| **Job family** | [`JF-GIB-INTEL-01`](../job-families/JF-GIB-INTEL-01.md) |
| **Value delivered** | The Signal, its relevance, and its permitted context are with the owner who has access, in time to be triaged. |
| **Collective JTBD(s)** | [`JTBD-GIB-INTEL-02`](../jtbd/JTBD-GIB-INTEL-02.md) (candidate); [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Accountable team or role** | The banker holding the information is accountable for recognising and sharing it. The owner of the affected client or outcome is accountable for acknowledging it into `BUC-GIB-INTEL-01`. Coverage leads identification of the owner (Q142). |
| **Participating roles** | Any Coverage, product, or regional banker who holds the information; the Coverage support team for identification and permitted-form preparation; the client or outcome owner; controls partners where a restriction applies `[validate]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md) as the typical owner; [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate). The holder cohort has no actor record `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` for the trigger, value, and judgments from the MD's account (Q02, Q06); no observed episode and no holder interviewed. |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | A banker recognises that information they hold may affect a client or outcome they do not own. |
| **Starting state** | The information sits with someone who has no declared demand for it from the owner (Q07). They may not know who the owner is or how to reach them. Client, legal, clean-team, regional, or relationship sensitivity may constrain them. |
| **Completion condition** | The owner has acknowledged the Signal, its relevance, and its permitted context into `BUC-GIB-INTEL-01-S1`. Where substance is restricted, the existence of a restricted situation and its owner are recorded and nothing further is disclosed. |
| **Resulting state** | The Signal is inside the owner's triage while the response window is open; restricted substance remains protected. |
| **Out of scope** | Judging the Signal's materiality or response (that is `BUC-GIB-INTEL-01`), resolving ownership conflicts (business heads arbitrate under the control rule), and any client Engagement. |
| **Frequency and criticality** | Event-driven and infrequent per holder. The participant's own costly miss (Q02) was exactly this failure: the information existed in the bank and never arrived. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Holding banker (any Coverage, product, or regional banker) | Recognise that the information may matter beyond their own remit. Share relevance, context, and expected follow-through. | Judges whether it plausibly matters to someone else and what sensitivity permits. | Does not know the owner's priorities or open questions. Bound by confidentiality, information barriers, and client discretion. | `[validate actor]` |
| Coverage support team (candidate) | Help identify the affected client and the owner; prepare the Signal in permitted form. | Can identify and prepare; cannot widen what the restriction permits. | Access and sensitivity rules; Coverage holds institution-level ownership. | `ACTOR-COV-SUPPORT-TEAM` (candidate) |
| Owner (typically Senior Coverage MD) | Acknowledge the Signal into intelligence triage; own the follow-through. | Decides whether to accept the Signal into `BUC-GIB-INTEL-01` and what to tell the holder. | Receives relevance and permitted context, not raw volume. | `ACTOR-COV-SENIOR-MD` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-INTEL-02-S1` | Recognise the information may matter beyond own remit. | Holding banker | What was learned, which institutions or outcomes it could touch, and how time-bound it is. | Does it plausibly matter to someone else? | None yet; recognition is the holder's own. | A candidate Signal for sharing. |
| `BUC-GIB-INTEL-02-S2` | Identify the affected client and the owner. | Holding banker; Coverage support team | Client coverage, institution-level ownership, open opportunities or commitments that could be affected. | Who owns the affected client or outcome? Coverage coordinates and names the institution-level owner (Q142). | Coverage coordinates; business heads arbitrate where ownership is contested. | A named owner. |
| `BUC-GIB-INTEL-02-S3` | Judge what may be shared. | Holding banker; controls partners where relevant | Client confidentiality, information barriers, clean-team, regional, relationship, and personnel sensitivity (Q145). | What does sensitivity permit, in what form, and to whom? | Access questions go to controls partners `[validate]`. | A permitted form for the Signal, or a finding that only existence and ownership may be shared. |
| `BUC-GIB-INTEL-02-S4` | Share relevance, context, and expected follow-through. | Holding banker | The six contexts absent at Q06: the owner's priorities, open questions, the Signal's relevance, who the owner is, a permitted way to share, and the expected follow-through. | What does the owner need in order to judge it, and what does the holder expect back? | The owner receives the Signal in permitted form. | The Signal, its relevance, and permitted context are with the owner. |
| `BUC-GIB-INTEL-02-S5` | Owner acknowledges the Signal into intelligence triage. | Owner | The Signal as shared, with its relevance and uncertainty. | Accept into `BUC-GIB-INTEL-01-S1`, or decline with a reason. | Enters `BUC-GIB-INTEL-01`; the holder learns the follow-through. | The Signal is in triage; the loop is closed for the holder. |
| `BUC-GIB-INTEL-02-S6` | Where substance is restricted, record that a restricted situation exists and who owns it. | Holding banker; owner | The restriction and the group with access. | What may be known outside the group with access: at minimum existence and ownership (Q145). | Others can send further relevant evidence to the owner without seeing the substance. | Safe coordination without disclosure. |

## Scenarios

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| None yet | No scenario has been raised. Restricted substance is not a scenario; it is handled by the cross-family control rule below and by step S6. | - | - |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| The owner cannot be identified or is contested. | Several plausible owners, or none, across products or regions. | Coverage coordinates at institution level; relevant business heads arbitrate ownership (Q142). | One owner receives the Signal. |
| Sensitivity prevents sharing the substance. | Client, legal, clean-team, regional, or relationship restriction applies. | Share only that a restricted situation exists and who owns it (S6); further visibility depends on the restriction. | Restricted substance remains protected; the owner knows where to look. |
| The holder does not recognise relevance. | Discovered only after the fact, as at Q02. | Not detectable within the run; recorded as a material surprise under `BO-GIB-INTEL-01`. | The Signal never enters triage; the failure is the outcome measure, not a step. |
| The owner declines or does not acknowledge. | No acknowledgement within the useful window. | The holder re-sends with the consequence stated, or escalates to the Coverage lead for the institution. | The Signal is either acknowledged or declined with a reason. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Signals held elsewhere in the bank reach the owner before the useful window closes; the holder learns the follow-through; no owner has to publish demand; no unauthorised disclosure. |
| **Failure consequences** | A material surprise for the owner (Q02), duplicated or conflicting client action, or a breach of a restriction. |
| **Current process and pain** | Sharing depends on who knows whom. The holder lacks the owner's priorities, open questions, the Signal's relevance, the owner's identity, a way to share, and the expected follow-through (Q06: all six absent) `[validate with the holder cohort]`. |
| **Business rules and controls** | Cross-family control rule (Q70, Q145, Q142): when evidence, outreach, or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. Do not require owners to declare needs in advance (Q07). Share relevance and context, not raw volume. Preserve the source trail and uncertainty into `BUC-GIB-INTEL-01`. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md) and the Round 1 record: Q02, Q06, Q07, Q142, Q145. Raised by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md). |
| **Open questions** | Interview a banker who has held such information; observe one sharing episode; validate permitted forms with controls partners; decide whether the holder cohort needs an actor record. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.3` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | When a sharing episode is observed or Round 2 question CINT12 returns. |
| **Review triggers** | Changed trigger, value delivered, accountable role, permitted-form rule, ownership model, or evidence that sharing is a step of `BUC-GIB-INTEL-01` rather than a use case. |
| **Supersession links** | None. The ID was earlier used informally in the IBIQ mapping for a daily re-orientation candidate; that candidate was withdrawn from this ID and is now `SC-GIB-INTEL-01-D`. |
| **Change rationale** | Raised as a candidate by the model revision of 2026-10-07; not admitted. `BUC-GIB-INTEL-01` had hidden this work as a starting state and an exception row; it has its own trigger, accountable role, and value. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | Q02, Q06, Q07, Q142, Q145 re-read in the model revision | Raised as `Candidate` at `Evidence-backed`; not admitted. | `[validate: intent model owner]` | `JTBD-GIB-INTEL-02`, `JTBD-GIB-INTEL-01`, `BUC-GIB-INTEL-01`, `JF-GIB-INTEL-01`, `BO-GIB-INTEL-01` |
| `0.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |
| `0.3` | 2026-10-07 | None; wording only. | Terminology: Interaction (a live exchange with a client: call, virtual or in person) and Engagement (any client contact, including email) adopted as governed terms. Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

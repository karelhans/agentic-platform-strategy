# BUC-GIB-REL-02 - Execute A Purposeful Client Contact

> Candidate record raised by the model revision of 2026-10-07. Not admitted. The catalogue's admitted position for this family is `BUC-GIB-REL-01` alone. That holds until the intent model owner accepts this record under the charter's admission rule.

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-REL-01`](../business-outcomes/BO-GIB-REL-01.md); its guardrails on contact volume and client fatigue are the measures this use case must watch. |
| **Job family** | [`JF-GIB-REL-01`](../job-families/JF-GIB-REL-01.md) |
| **Value delivered** | One approved, substantive client contact in the banker's voice. It is coherent with other JPM contact with the institution. Its ask and expected next step are owned and recorded. Or: an explicit, recorded Decision not to send. |
| **Collective JTBD(s)** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md); [`JTBD-GIB-MEET-01`](../jtbd/JTBD-GIB-MEET-01.md) for the post-meeting follow-up variant only; `JTBD-GIB-ACT-01` (candidate, not admitted) at step 6, where the next step gains an owner. |
| **Accountable team or role** | Senior Coverage MD, or the relationship owner the MD has delegated to. The contact goes in that person's voice. |
| **Participating roles** | Coverage support team preparing context and drafts; other JPM owners with planned or recent contact with the institution; the owner who receives the next step `[validate]`. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate, not admitted). |
| **Evidence maturity** | `Hypothesis` overall: no banker episode has been observed, and the process was raised from a reading of a product use case. Steps 1, 2 and 5 are evidence-backed (Q11, Q12, Q98, Q100). The coherence check at step 3 rests on Q94. |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | An accepted Decision from `BUC-GIB-REL-01` step 5, `BUC-GIB-INTEL-01` step 6 or `BUC-GIB-MEET-01` step 6 names a client, an objective and contact by message or call. |
| **Starting state** | The reason to engage has been judged elsewhere. What to say, to whom precisely, in what sequence with other JPM contact, and whether to send at all are still open. |
| **Completion condition** | The banker who owns the contact has sent it or deliberately withheld it. The Decision is recorded. The ask and expected next step have an owner. |
| **Resulting state** | The client has heard one coherent JPM voice with a purpose, or has deliberately not been contacted. The next step is owned and visible in the relationship record. |
| **Out of scope** | Judging whether the relationship warrants attention (`BUC-GIB-REL-01`); triaging the Signal that prompted contact (`BUC-GIB-INTEL-01`); preparing and conducting a high-stakes meeting (`BUC-GIB-MEET-01`); fulfilling the commitment the contact creates. |
| **Frequency and criticality** | Frequent. Each run is small, but repeated purposeless or duplicated contact erodes trust and access. A wrong message in the banker's name damages credibility directly. |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Owns the contact that goes in their name and the Decision to send or withhold. | All six Q12 judgments: whether to engage, who owns the relationship contact, the client objective and ask, tone and message, JPM participants, and whether to send. | Needs the Q98 thesis without reconstructing it personally: what changed, what matters to this person, the outcome sought, what to say or ask, what to avoid, and what happens next. | `ACTOR-COV-SENIOR-MD` |
| Coverage support team (candidate) | Prepare the thesis, check prior and planned JPM contact, draft the message, and record the outcome. | Recommend. May own delegated routine contact where `BUC-GIB-REL-01` has delegated it (Q33, Q99). Never sends in the MD's name without the MD's Decision. | Distributed context, confidentiality, and other owners' contact plans. | `ACTOR-COV-SUPPORT-TEAM` (candidate) |
| Other JPM contact owners | Declare planned or recent contact and agree the sequence. | Hold their own contact; conflicts go to the Coverage MD and, unresolved, to business heads (Q142). | Restricted situations may be known only as existing and owned (Q145). | `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-REL-02-S1` | Confirm what changed, what matters to this person, and the outcome sought. | Coverage support team, Senior Coverage MD | The accepted Decision and its Rationale; signs of client priorities; relationship history with this person. | Is the purpose still real and specific to this person now? | Draws on the originating use case's record. | Contact thesis (Q98). Evidence-backed. |
| `BUC-GIB-REL-02-S2` | Confirm the right to engage and what to avoid. | Senior Coverage MD, support team | Relationship owner, sensitivities, restrictions, commitments outstanding, what must not be said or asked. | Whether JPM, and this banker, should be the one to engage; what is off limits. | Restricted matters follow the control rule below. | Cleared or withdrawn right to engage. Evidence-backed (Q12, Q98). |
| `BUC-GIB-REL-02-S3` | Check what the client has already heard from JPM and agree the sequence with other owners. | Support team, other JPM contact owners, Senior Coverage MD | Recent and planned JPM contact with the institution; positioning taken by others. | Does this contact duplicate, contradict or need to follow another? Who leads? | Overlap or conflict surfaces to the Coverage MD. See `SC-GIB-REL-01-D` where it concerns the institution posture. | Agreed sequence and coherent position (Q94). |
| `BUC-GIB-REL-02-S4` | Compose the message and the ask. | Support team or Senior Coverage MD | The thesis, the chosen stakeholder, tone appropriate to the relationship, the specific ask or, for listening-only contact, the invitation. | What to say or ask; what next step the contact proposes. | Draft in the banker's voice for the banker's review. | Draft contact and proposed next step. |
| `BUC-GIB-REL-02-S5` | The banker judges tone, ask, participants and whether to send. | Senior Coverage MD | The draft, the thesis, sequence with other JPM contact, client fatigue and contact pattern. | Send, revise, delegate to another owner, or do not send. Listening-only contact without an ask is a valid outcome (Q100). | Revision returns to S4; delegation names the owner. | Approved contact, or an explicit Decision not to send. Evidence-backed (Q12, Q100). |
| `BUC-GIB-REL-02-S6` | Send or withhold, record, and hand the next step to its owner. | Senior Coverage MD or delegated owner, support team | The sent contact, or the withhold Decision and its Rationale; the expected client response and next step. | Who owns the next step and by when it should be reviewed. | Send the next step to the owner's job family (Q136). Update the relationship record in `BUC-GIB-REL-01`. Only items that later cross the drift threshold enter `BUC-GIB-ACT-01` (candidate). | Contact delivered or deliberately withheld and recorded, with an owned next step. Serves `JTBD-GIB-ACT-01` (candidate). |

## Scenarios

Candidate scenarios named by the model revision of 2026-10-07. No scenario record has been created for them; each needs an episode before it is written.

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| `SC-GIB-REL-02-A` (candidate, no record) | Listening-only contact: the purpose is to hear the client, not to bring an offering (Q100). | No ask is composed at S4; S5 judges the invitation and the right to the client's time. | A purposeful, approved contact with an owned next step, or a Decision not to send. |
| `SC-GIB-REL-02-B` (candidate, no record) | Post-Signal contact: the trigger is a Decision from `BUC-GIB-INTEL-01` step 6. | S1 leans on the Signal's Rationale and evidential strength; the Signal's window sets the timing. | Same value; the Signal's intended client outcome becomes the contact's purpose. |
| `SC-GIB-REL-02-C` (candidate, no record) | Delegated contact in the MD's name: routine maintenance delegated under `BUC-GIB-REL-01` (Q33, Q99). | The support team or a relationship owner composes and may send. The MD's S5 judgment is exercised as a standing delegation with limits. | The MD remains accountable for what goes in their voice. The "do not send" exit remains available to the delegate. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| The banker decides not to send. | S5 judgment: the purpose has lapsed, the timing is wrong, the client has had enough contact, or the right to engage fails. | Mandatory exit. The Decision and its Rationale are recorded. The originating use case is told, so it can revisit its own Decision. | Explicit, recorded Decision not to send. The use case completes. |
| Another JPM owner has made or plans overlapping contact. | S3 check of recent and planned JPM contact. | The Coverage MD sets posture and sequence; unresolved ownership goes to business heads (Q142). Where the overlap concerns the institution posture rather than one message, it is handled as `SC-GIB-REL-01-D`. | Sequenced, coherent contact or deferral. |
| The purpose turns out to be a gap in contact alone. | S1 cannot name what changed or what matters to this person now. | Return to `BUC-GIB-REL-01`. A dry spell is a reason to review, not a reason to send (Q33, Q99). | No contact; relationship judgment reassessed. |
| The right to engage depends on restricted information. | S2 finds the reason to engage rests on evidence outside the group with access. | Apply the control rule below. The contact is withheld or reshaped so it does not disclose. | Withheld or permitted contact; restriction recorded as existing and owned. |
| Sent contact without a recorded next step or owner. | S6 record is missing an owner or review condition. | Owner named before the run is closed. | Owned next step. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Contacts the client responds to or acts on; client-initiated requests following contact; no rise in contact volume without a rise in meaningful response; "do not send" Decisions recorded and respected; no duplicated or contradictory JPM contact with one institution. |
| **Failure consequences** | Client fatigue, a message in the MD's name that misreads the client, duplicated or conflicting JPM outreach, contact without a purpose, or an ask whose follow-up nobody owns. |
| **Current process and pain** | Juniors prepare outreach against the Q11 brief and the MD judges it. What the client has already heard from other parts of JPM is often not known at the point of sending `[validate observed process]`. |
| **Business rules and controls** | The six Q12 judgments stay with the banker, however the contact is prepared. Listening is a legitimate purpose (Q100). A gap in contact alone never produces a contact (Q33, Q99). The "do not send" exit is mandatory and is a completed run, not a failure. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Evidence** | Q11 (minimum brief before outreach), Q12 (MD judgment boundary, all six), Q94 (failure to coordinate JPM and to follow through), Q98 (conversation thesis), Q100 (listening-only). Raised from the business reading of the IBIQ draft-outreach product use case, which is not itself a record. No observed episode (Q139). |
| **Open questions** | One observed contact episode, including a "do not send" Decision, via Round 2 CREL07 and CREL12. Whether the delegated variant needs a standing delegation rule. Boundary with `BUC-GIB-MEET-01` step 6 when a follow-up message is itself high-stakes. Whether product partners ever hold the accountable role for contact with a Coverage-owned institution. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | On the intent model owner's admission decision, or after Round 2 CREL07 and CREL12 return an episode. |
| **Review triggers** | An observed contact episode; a participant's acceptance or rejection of the six judgments as the boundary; evidence that the contact and the relationship judgment share one unit of value; changed coordination authority. |
| **Supersession links** | None. Distinct from `BUC-GIB-REL-01` by unit of value: a delivered contact rather than a relationship judgment. |
| **Change rationale** | Raised by the model revision of 2026-10-07 and not admitted. Under the template's own test, the relationship judgment and the contact have different units of value. The contact's judgments have direct banker evidence (Q11, Q12, Q98, Q100) but no observed episode. The record is therefore held at `Hypothesis` with the evidence-backed steps marked. Revision 0.2 is a banker-language pass on wording only. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | Q11, Q12, Q94, Q98, Q100 re-read under the model revision of 2026-10-07; no new evidence | Raised as a candidate at `Hypothesis`; not admitted. Awaits an episode and the owner's acceptance. | Pending: Coverage intent model owner | `JTBD-GIB-REL-01`, `JF-GIB-REL-01`, `BO-GIB-REL-01`, `BUC-GIB-REL-01`, `SC-GIB-REL-01-C` |
| `0.2` | 2026-10-07 | No new evidence; wording only | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Pending: Coverage intent model owner | None |

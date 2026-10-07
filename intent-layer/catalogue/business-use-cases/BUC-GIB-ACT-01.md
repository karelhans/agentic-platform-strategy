# BUC-GIB-ACT-01 - Resolve A Commitment That Is Drifting Or Waiting On The Senior

> **Candidate record.** Raised by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md), section 4.2 and the cross-cutting appendix. Not admitted. A thin use case with an entry threshold, not a parallel family of equal weight.

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | None yet. No `BO-*` record exists for this job family. A business outcome would need a measure of commitments resolving explicitly rather than drifting (Q120). |
| **Job family** | [`JF-GIB-ACT-01`](../job-families/JF-GIB-ACT-01.md) - Actions and commitments (candidate). |
| **Value delivered** | A drifting material commitment or MD blockage explicitly resolved: fulfilled, renegotiated, re-owned, stopped or deliberately parked, before the window closes. |
| **Collective JTBD(s)** | [`JTBD-GIB-ACT-01`](../jtbd/JTBD-GIB-ACT-01.md) - Translate intent into accepted ownership and explicit commitment (candidate). |
| **Accountable team or role** | Senior Coverage MD, for the items in the senior attention set. The commitment owner accepts the resolution. |
| **Participating roles** | Senior Coverage MD; the commitment owner in whichever job family holds the commitment; the supporting cohort that prepares the consequence and ownership picture; business heads where ownership conflict arises outside the group with access. |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate). |
| **Evidence maturity** | `Hypothesis`. The proposal's use case test backs the record with evidence. Charter section 6 rule 2 holds it at `Hypothesis` until a concrete episode is recorded. |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | A material commitment or MD-dependent item crosses a threshold: a committed checkpoint is missed, a decision window is shrinking, an assumption has changed, relationship risk has increased (Q23), or work is waiting on the MD (Q18). |
| **Starting state** | The commitment exists in another job family's record or in personal memory. Its owner may be nominal. Nobody has stated the consequence of delay in comparable terms. The senior may not see that work is waiting on them. |
| **Completion condition** | The commitment or blockage has an explicit resolution: fulfilled, renegotiated, re-owned, stopped or deliberately parked. It has a credible owner and checkpoint. The senior has released attention or deliberately kept it (Q36). |
| **Resulting state** | The owner's job family carries the resolution. The owner can move without returning to the senior. The senior attention set is smaller or deliberately unchanged. |
| **Out of scope** | The consequence judgments the parent families own; the embedded commitment steps that create commitments in the first place; task inventories and routine task tracking; execution milestones; capacity allocation (Q130); relationship maintenance (Q17). |
| **Frequency and criticality** | Event-driven and, as a standing senior view, recurring. Failure lets commitments drift without a decision, leaves the senior a hidden bottleneck, and narrows the window to intervene (Q19, Q119). |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Judge what matters now, test whether ownership is real, choose the mode of intervention, release attention. | Decides act, direct, chase, escalate, monitor or stop; escalates ownership conflicts to business heads. | Needs the consequence of delay in comparable terms (Q19), the current owner and commitment, and the remaining window. Works under time, confidentiality and relationship constraints. | `ACTOR-COV-SENIOR-MD` |
| Coverage supporting cohort | Identify items above threshold, state the consequence of delay, surface where ownership is nominal, carry the resolution back into the owner's family. | Prepares and translates; holds the standing senior-ready quality bar (Q34); does not decide the mode of intervention. | Needs the senior's outcome, starting view, inputs and checkpoint rule (Q22). Constrained by access rules and need-to-know boundaries. | `ACTOR-COV-SUPPORT-TEAM` (candidate) |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-ACT-01-S1` | Identify commitments and blockers above threshold across job families. | Supporting cohort, Senior Coverage MD | Client promises made and received, decisions only the MD can make, work awaiting MD feedback, team commitments at risk, cross-bank dependencies, compliance and approvals (Q17); the threshold conditions (Q18, Q23). | Which items have crossed the threshold and so enter the senior attention set. | Read from the intelligence, relationship, pipeline and Interaction records; no new object is created (Q141). | Bounded set of items above threshold. |
| `BUC-GIB-ACT-01-S2` | State the consequence of delay. | Supporting cohort | Relationship or credibility cost, opportunity economics at risk, decision window remaining, downstream work held (Q19). | How this item compares with others if left unresolved. | Owner and contributors supply the facts; the cohort states them in comparable terms. | Comparable consequence attached to each item. |
| `BUC-GIB-ACT-01-S3` | Check that the owner has accepted the work, not just the name. | Senior Coverage MD, commitment owner | Whether the named owner has accepted the outcome, the starting view, the inputs, and the checkpoint and escalation rule (Q22, Q119). | Is ownership real? | The owner confirms or the gap is surfaced to the MD. | Ownership confirmed as real, or exposed as nominal. |
| `BUC-GIB-ACT-01-S4` | The MD chooses the mode: act, direct, chase, escalate, monitor or stop. | Senior Coverage MD | Clarity of outcome and quality bar, current owner and commitment, impact and time sensitivity (Q20); the available Decisions (Q65). | Which intervention, if any, and by whom. | Direction or delegation goes to the owner. Escalation goes to business heads where ownership conflicts cross the group with access. | Explicit senior Decision. |
| `BUC-GIB-ACT-01-S5` | Release senior attention when owner and checkpoint are credible. | Senior Coverage MD | Client progress evidenced; owner and checkpoint secured; blocker or risk resolved; deliberate wait state; stop decision made; deliverable completed (Q36). | Is it safe to exit, or must the item stay in the attention set? | The owner takes the next checkpoint. | Item leaves the senior attention set or is deliberately kept. |
| `BUC-GIB-ACT-01-S6` | Record the resolution in the owner's job family. | Commitment owner, supporting cohort | The resolution, its Rationale, the owner and the next checkpoint. | What the owner's family record now says about the commitment. | Written into the intelligence, relationship, pipeline or Interaction record that holds the commitment (Q136). | The owner's family carries the resolution; the review is closed for this item. |

## Scenarios

None yet. No scenario record is created until a concrete episode exists. Candidate variations, listed here and not as files:

| Candidate variation | Context or trigger | What would vary | What would remain invariant |
| --- | --- | --- | --- |
| Commitment to a client versus internal commitment | A promise made to or by a client, versus a commitment between JPM teams | Consequence terms: relationship or credibility cost weighs more for client commitments. Who must be told of a renegotiation. | Explicit resolution and real ownership |
| The MD is the blocker versus the owner is | Work is waiting on the senior's direction, feedback or alignment (Q18), versus the owner's checkpoint has slipped (Q23) | Who acts in S4: the MD clears their own item, or chooses a mode toward the owner | Consequence stated, attention released when credible |
| Cross-family dependency | The commitment depends on work owned in another job family | The record in S6 goes to the owner's family (Q136), with cross-links to the dependent family. Business heads may arbitrate. | One resolution recorded in the owner's family |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| Ownership is nominal and nobody accepts the outcome. | S3 finds no accepted outcome, starting view or checkpoint. | MD re-owns, directs a new owner, or stops the work. | Real owner or explicit stop. |
| Ownership conflict arises outside the group with access. | Conflicting owners or outreach appear across products or regions. | Business heads arbitrate; Coverage coordinates; others learn only that a restricted situation exists and who owns it. | One owner, safe minimum visibility. |
| The item is below threshold. | S1 finds no threshold condition met. | Leave it in its family's record; do not enter the senior attention set. | Review not entered. |
| The window has already closed. | Consequence in S2 shows no remaining window to intervene. | Record the outcome and any stop or renegotiation; return the lesson to the owner's family. | Explicit closure rather than silent lapse. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Commitments resolve explicitly. Outcomes advance. Owners move independently without repeated reinterpretation (Q120). Elapsed time from blocker to resolution and from owner to client progress shortens (Q21). Senior attention is released at the right point. |
| **Failure consequences** | Relationship or credibility cost, opportunity economics at risk, decision windows lost, downstream work held (Q19); the senior as hidden bottleneck. |
| **Current process and pain** | Commitments are held across family records, messages and memory. The senior is most often the constraint where direction, feedback, alignment, capacity or information is waiting (Q18). Ownership is often nominal (Q119) `[validate with concrete episode]`. |
| **Business rules and controls** | Entry threshold (Q17, Q23) rather than a task inventory. No separate senior-attention plan object (Q141): this review reads the other families' records. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), actions and commitments section; Round 1 appendix Q17 to Q23, Q36, Q118 to Q121, Q141. One participant; no observed episode. |
| **Open questions** | Validate against a concrete drifting-commitment or MD-blocker episode. Test the threshold conditions with a second participant. Confirm that the supporting cohort performs S1, S2 and S6 as described. Test whether product bankers and Line MDs see the same thresholds (Q148). |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.3` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | On acceptance or rejection of the model revision of 2026-10-07, or after a concrete commitment episode is recorded. |
| **Review triggers** | A concrete episode; a second participant changing the threshold conditions, the Decisions, or the "both" ownership model (Q121); evidence that a separate senior-attention object is wanted (Q141); changes to the commitment steps of the parent families; changed accountable collective. |
| **Supersession links** | None. |
| **Change rationale** | Raised by the model revision of 2026-10-07 as a candidate; not admitted. Gives the standing senior view at Q121 its one thin use case, with threshold entry and no new object. The four families' commitment steps can then say where above-threshold items go. Revisions `0.2` and `0.3` change wording only. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | Round 1 Q17 to Q23, Q36, Q118 to Q121, Q141, tested in the model revision of 2026-10-07 | Raised as a candidate at `Hypothesis` under charter rule 2; not admitted. | Pending: Coverage intent model owner | `JF-GIB-ACT-01`, `JTBD-GIB-ACT-01`, `ACTOR-COV-SENIOR-MD`, `ACTOR-COV-SUPPORT-TEAM` |
| `0.2` | 2026-10-07 | None | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Pending: Coverage intent model owner | None; wording only. |
| `0.3` | 2026-10-07 | None | Terminology: Interaction (a live exchange with a client: call, virtual or in person) and Engagement (any client contact, including email) adopted as governed terms. Meaning, evidence, maturity and review state unchanged. | Pending: Coverage intent model owner | None; wording only. |

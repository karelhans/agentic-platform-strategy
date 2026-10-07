# BUC-GIB-PIPE-02 - Recognise An Idea As An Opportunity

> **Candidate record.** Raised by the model revision of 2026-10-07 and not admitted. The admission rule in charter section 6 has not been met: no concrete episode exists (Q139). Consumers must not build on this record until the Coverage intent model owner admits it.

## Classification

| Field | Value |
| --- | --- |
| **Business outcome target(s)** | [`BO-GIB-PIPE-01`](../business-outcomes/BO-GIB-PIPE-01.md) - Improve opportunity portfolio accuracy; this use case is where the leading indicator "earlier idea recognition" is produced. |
| **Job family** | [`JF-GIB-PIPE-01`](../job-families/JF-GIB-PIPE-01.md) - Opportunity pipeline management. |
| **Value delivered** | One idea taken into shared management with a named owner and explicit uncertainty, or a recorded decision not to recognise it. |
| **Collective JTBD(s)** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) - Maintain disciplined opportunity management. Also serves [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) cross-family: "choose the appropriate response" for a Signal whose response is a possible transaction path. |
| **Accountable team or role** | Coverage-led opportunity management group; the banker who recognises the idea proposes, and the named owner accepts or declines ownership. |
| **Participating roles** | Senior Coverage MD, the recognising banker, the proposed owner, Coverage and product bankers who hold relevant context, and the supporting cohort (`ACTOR-COV-SUPPORT-TEAM`, candidate). |
| **Representative personas** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-PIPELINE-TEAM`](../actors/ACTOR-COV-PIPELINE-TEAM.md); `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | Trigger and value delivered `Evidence-backed` (Q115, Q140, Q149); the six steps `Hypothesis`. No concrete episode (Q139). |

## Process Boundary

| Field | Value |
| --- | --- |
| **Trigger** | A credible Signal, a veiled client comment, or relationship context suggests a plausible transaction path. The institution has no opportunity for it yet. |
| **Starting state** | No opportunity exists. Evidence is sparse and client intent is often veiled (Q115). Several readings of the same Signal may be legitimate. |
| **Completion condition** | The idea is taken into shared management with a named owner and its uncertainty stated. Or the decision not to recognise it is recorded with its reason. |
| **Resulting state** | An admitted idea enters [`BUC-GIB-PIPE-01`](BUC-GIB-PIPE-01.md) under scenario `SC-GIB-PIPE-01-D`. A declined idea leaves no administrative residue beyond its reason. A watched idea has a stated condition for return. |
| **Out of scope** | Judging the Signal itself (that is `BUC-GIB-INTEL-01`), managing an existing opportunity (`BUC-GIB-PIPE-01`), portfolio trade-offs (`BUC-GIB-PIPE-03`), precedent recall, and fee or revenue estimation per transaction path. |
| **Frequency and criticality** | Frequent and brief. The idea-to-recognised-opportunity transition is the primary leakage point in the lifecycle (Q140). Fewer viable opportunities lost silently is the leading measure of pipeline improvement (Q149). |

## Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Senior Coverage MD | Recognise ideas from client interaction and relationship context. Challenge whether a credible JPM role and client need exist. Decide to own the idea where senior context is required. | Admits, declines, or watches. Names the owner where the idea is theirs to place. | Veiled intent and sparse evidence. Must not fill the portfolio with speculation. | `ACTOR-COV-SENIOR-MD` |
| Coverage opportunity team | Recognise ideas from Signals and product context. Propose an owner. Accept or decline as the named owner. | The proposed owner accepts or declines ownership. | Evidence is partial. Interpretations may differ across products and regions. | `ACTOR-COV-PIPELINE-TEAM` |
| Supporting cohort | State the implication for the institution and the plural readings so the decision is senior-ready. | Prepares; does not admit or decline. | Senior-ready bar under time pressure (Q04, Q35). | `ACTOR-COV-SUPPORT-TEAM` (candidate) `[validate actor]` |

## Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| `BUC-GIB-PIPE-02-S1` | State the implication for the institution. | Recognising banker, supporting cohort | The Signal, comment, or context. What the institution is doing or facing. What the client has said or avoided saying. | Decide what this could mean for the institution, in business terms. | Signal-originated ideas arrive from `BUC-GIB-INTEL-01` S6. Conversation-originated ideas arrive from `BUC-GIB-MEET-01` S6 or relationship work. | A stated implication, not yet an opportunity. |
| `BUC-GIB-PIPE-02-S2` | Judge whether a credible JPM role and client need exist. | Recognising banker, Senior Coverage MD | Client need or strategic thesis, JPM's relevance and position, access path. | Decide whether JPM could plausibly contribute and the client could plausibly need it. | Product bankers add product-specific plausibility where relevant. | A plausibility judgment with its grounds. |
| `BUC-GIB-PIPE-02-S3` | Note plural interpretations. | Recognising banker, contributors | Alternative readings of the same evidence; what each would imply. | Decide which readings to carry forward and which to drop. | Differing views are recorded, not reconciled by force. | Explicit uncertainty. |
| `BUC-GIB-PIPE-02-S4` | State value qualitatively. | Recognising banker | Strategic relevance to the firm; indicative scale in words. | Decide whether the idea is worth an owner's effort without estimating economics (Q143). | None required. | Qualitative value statement. |
| `BUC-GIB-PIPE-02-S5` | Owner decides admit, decline, or watch. | Named owner, Senior Coverage MD where senior | The implication, plausibility judgment, plural readings, qualitative value, and why now. | Plausible enough to own; who owns it; why now. | The owner accepts or declines. Where declined, the recognising banker may propose another owner or record non-recognition. | Admit, decline, or watch with a stated condition. |
| `BUC-GIB-PIPE-02-S6` | Hand to opportunity review or record non-recognition. | Named owner | The accepted decision and its uncertainty. | Decide what the shared picture shows now. | An admitted idea enters `BUC-GIB-PIPE-01` (scenario D). A watched idea carries a return condition. A declined idea is recorded with its reason and nothing more. Restricted detail follows the control rule below. | One idea taken into shared management, watched, or deliberately not recognised. |

## Scenarios

Candidate scenarios named by the model revision of 2026-10-07; no scenario files exist yet.

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| `SC-GIB-PIPE-02-A` (candidate, `Hypothesis`) | Signal-originated: a triaged Signal arrives from `BUC-GIB-INTEL-01` S6 with a transaction path as its response. | Evidence is external and already judged for credibility. Client intent is inferred, not heard. | One idea admitted, watched, or deliberately not recognised. |
| `SC-GIB-PIPE-02-B` (candidate, `Hypothesis`) | Conversation-originated: a veiled client comment (Q115) arrives from `BUC-GIB-MEET-01` S6 or relationship contact. | Evidence is the banker's own reading of the client. Interpretation and relationship sensitivity dominate. | One idea admitted, watched, or deliberately not recognised. |

## Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| No owner will accept the idea. | The proposed owner declines and no alternative is named. | The Senior Coverage MD decides to own it, name an owner, or record non-recognition. | No unowned idea persists. |
| The idea duplicates an existing opportunity. | The institution already has an opportunity on the same path. | Hand the evidence to that opportunity's owner as a review trigger for `BUC-GIB-PIPE-01`. | One opportunity, not two. |
| Material detail is restricted. | An access or control boundary prevents full sharing. | Expose only that a restricted situation exists and who owns it, subject to the restriction (Q145). | Safe coordination without unauthorized disclosure. |
| Pressure to size the idea. | Economics are requested before the client has disclosed intent. | Decline to estimate; state value qualitatively (Q143). | No fabricated economics in the shared picture. |

## Outcomes And Evidence

| Field | Value |
| --- | --- |
| **Success signals** | Earlier idea recognition (time from relevant evidence to a named owner); proportion of ideas with an accountable owner; fewer viable opportunities lost silently (Q149); non-recognition recorded deliberately rather than dropped silently. |
| **Failure consequences** | A relevant Signal never becomes a credible pursuit (Q140). Or the portfolio fills with speculation that distorts the outlook. |
| **Current process and pain** | Ideas live in bankers' heads, conversations, and notes until someone decides to call them an opportunity. The transition is unmeasured and is the primary leakage point `[validate with concrete episode]`. |
| **Business rules and controls** | No forced probability; speculative economics stay qualitative at idea stage (Q143; rule carried from `SC-GIB-PIPE-01-D`). Plural interpretations are preserved. Non-recognition is a valid result. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q115 (idea-to-opportunity is the most uncertain phase; "distinct but linked jobs" rejected), Q140 (primary leakage point), Q143 (economics qualitative for immature ideas), Q149 (leading measure); model revision proposal of 2026-10-07, section 4.2 and the pipeline family inventory. Q139: no concrete episode. |
| **Open questions** | A concrete recognition episode (Q139; Round 2 CPIPE03, CPIPE08); the recognition threshold across Coverage, M&A, ECM, and DCM (Q148); whether "watch" needs an owner distinct from the opportunity owner; who may record non-recognition. |

## Relationship To Earlier Candidates

This record absorbs the IBIQ use-case mapping's earlier `BUC-GIB-PIPE-02` candidate ("from a credible signal, set out the plausible transaction paths and judge whether any merits recognition"). It drops that candidate's precedent-recall step and its per-path firm-revenue step. Both come from a product specification rather than banker evidence. The revenue step contradicts Q143 and the no-forced-economics rule of `SC-GIB-PIPE-01-D`. The trigger is widened from a triaged Signal to any Signal, veiled comment, or relationship context. Q115 places recognition at the front of the funnel regardless of source.

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | When a concrete recognition episode is collected (Round 2 CPIPE03, CPIPE08) or the owner decides on admission. |
| **Review triggers** | A concrete episode; evidence that recognition and review share one unit of value after all; evidence that recognition belongs to the Signal family; a changed Q143 economics rule; admission of `ACTOR-COV-SUPPORT-TEAM`. |
| **Supersession links** | Supersedes the IBIQ mapping's provisional `BUC-GIB-PIPE-02` candidate (consumers/ibiq-use-case-mapping.md, section 2). Takes the recognition half of the `BUC-GIB-PIPE-01` revision `2.0` trigger. |
| **Change rationale** | Revision `0.2`: banker-language pass; wording only, meaning unchanged. Revision `0.1`: raised by the model revision of 2026-10-07 and not admitted. The use case test showed that taking an idea under ownership produces a unit of value no existing use case produces. Q140 and Q149 make the transition the business's own leading measure. Held at `Candidate` pending an episode. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested the pipeline family against Q01-Q151 | Raised as a candidate; trigger and value `Evidence-backed`, steps `Hypothesis`; not admitted. | Coverage intent model owner (as candidate, not admitted) | `BUC-GIB-PIPE-01`, `JTBD-GIB-PIPE-01`, `JF-GIB-PIPE-01`, `BO-GIB-PIPE-01`, `SC-GIB-PIPE-01-D` |
| `0.2` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner (as candidate, not admitted) | None; wording only |

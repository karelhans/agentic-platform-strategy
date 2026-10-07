# SC-GIB-INTEL-01-E - Converging Changes Or Cross-Client Implication

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted Decision, Rationale, intended outcome, and View for a potentially material Signal. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Several changes converge on one client or stakeholder, one opportunity, one decision window, or one owner's capacity (Q57). Or a single Signal carries an implication for more than one client or for the firm (Q74). |
| **Trigger** | Several changes converge, consequence crosses a threshold, or the connection itself needs senior judgment (Q60). |
| **Starting conditions** | Each item may be unremarkable alone; the consequence lies in the connection, which nobody owns yet. |
| **Stakes and urgency** | Judged separately, the items can be released and the connection missed. Judged as one situation, the response can be out of proportion to the evidence for any one item. Cross-client or firm-wide implication is a Q74 direct-attention threshold. |
| **What varies** | `S2` and `S3` compose the connection: why the items are linked, what changed in each, evidence and confidence, why it may matter now, existing ownership and commitments, open questions, and the ways to send it on (Q61). The Decision at `S4` to `S5` may be to dismiss the connection, to own it as normal work, or to pin it for continued oversight. The connection also lapses when the triggering window closes or evidence invalidates it (Q62). |
| **What remains invariant** | The exits are `BUC-GIB-INTEL-01` Decisions. Each contributing item keeps its own source trail and uncertainty. Sending follows the owner, with cross-references kept to the other affected owners (Q136). |
| **Additional business rules or controls** | Composition does not raise the evidential strength of any contributing item. A pinned connection carries a reassessment condition like any monitor Decision. |
| **Exit or transition** | The connection is dismissed, becomes owned work in the owner's job family, or is pinned with a return condition; or it lapses with the window or the evidence. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S2-S3 | Connect the items and explain why they belong together, with evidence, consequence, ownership, and the ways to send the connection on as a whole. | The consequence is in the convergence, not in any one item. | Support team composes; Senior Coverage MD judges the connection directly (Q74 threshold). | One interpretable case for a connected situation. |
| S4-S6 | The Decision addresses the connection: dismiss it, own it, or pin it. | Q62 exits are the parent's Decisions. | Sending goes to the owner for the connected outcome, with other affected owners informed (Q136). | No separate situation record; the connection lives as a Decision. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Connections across items are seen before the window closes; dismissed connections are explicit; pinned connections return when material; no over-reaction to weak items because they arrived together. |
| **Failure risks** | A missed connection, a composed case treated as stronger than its parts, or a connection with no owner. |
| **Evidence** | Round 1 record Q57, Q59 to Q62, Q74; [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md). Raised by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md), which demoted the "compose converging changes" use case candidate to this scenario because its exits are INTEL-01 Decisions. |
| **Open questions** | Observe one convergence episode; validate how cross-references to other affected owners are kept without duplicating ownership. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After an observed convergence episode. |
| **Review triggers** | Evidence that a composed connection delivers a value distinct from the parent's Decisions, or a changed sending rule. |
| **Supersession links** | None. |
| **Change rationale** | Raised as a candidate scenario by the model revision of 2026-10-07; not admitted. Fills the family's "cross-client implications" known variation with direct Round 1 evidence. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-07 | Q57, Q59 to Q62, Q74 re-read in the model revision | Raised as `Candidate` at `Evidence-backed`; not admitted. | `[validate: intent model owner]` | `BUC-GIB-INTEL-01`, `JTBD-GIB-INTEL-01`, `JF-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

# SC-GIB-PIPE-03-A - Alignment-Only Forum

> **Candidate record.** Scenario of candidate use case `BUC-GIB-PIPE-03`. Raised by the model revision of 2026-10-07 and not admitted; it is admitted or rejected with its parent.

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-PIPE-03`](../business-use-cases/BUC-GIB-PIPE-03.md) (candidate) |
| **Related JTBDs** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) |
| **Value delivered** | An accepted shared picture of the portfolio with any warranted effort, ownership, pursuit, or capacity redirections made explicit. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`, `ACTOR-COV-PIPELINE-TEAM`; `ACTOR-COV-SUPPORT-TEAM` (candidate) |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | A scheduled management or planning session. Its purpose is to establish a common picture of the portfolio, not to make decisions (Q146). |
| **Trigger** | A scheduled forum whose purpose is set as alignment. |
| **Starting conditions** | Participants hold inconsistent or stale views. Most opportunities have not materially changed since the last session. |
| **Stakes and urgency** | Shared reality is the value. The risk is that reconstruction crowds out judgment, or that a decision is forced where evidence has not changed. |
| **What varies** | Steps S4 and S5 are light or empty. Trade-offs and redirections occur only where evidence has changed. Business heads are not normally present. |
| **What remains invariant** | The forum ends with one accepted shared picture. Where there are no redirections, that is stated explicitly rather than left implicit. |
| **Additional business rules or controls** | Do not force a decision where evidence has not changed. Distinguish status alignment from decision-making (Q146). Control rule of the parent applies. |
| **Exit or transition** | The accepted picture informs the normal management of each opportunity. An opportunity whose state is found to have changed becomes a `BUC-GIB-PIPE-01` review trigger, or is carried to a decision forum (`SC-GIB-PIPE-03-B`). |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1-S2 | The review set is broad and the time goes to aligning the picture. | The forum's purpose is a common picture. | None. | Reconstruction is visible and can be reduced over time. |
| S4-S5 | Trade-offs and redirections are made only where evidence has changed. Otherwise "no redirection" is recorded. | Decisions without changed evidence are status theatre. | None. | The picture is accepted. Effort stays where it is unless a change warrants moving it. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Participants leave with one accepted picture. Repeated status debate declines. No redirections are forced. |
| **Failure risks** | Status theatre, reconstruction consuming the forum, or a changed opportunity passing unchallenged because the forum "only aligns". |
| **Evidence** | Coverage evidence revision 2.0, Q146 (some sessions establish a common picture); inherited from `SC-GIB-PIPE-01-A` revision `1.0`. No forum observed. |
| **Open questions** | Which forums are alignment-only by LOB; whether alignment-only forums exist at all once a shared picture is maintained continuously `[validate]`. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | With the parent: after a real forum is observed or on the owner's admission decision. |
| **Review triggers** | Changed forum purpose or participants; evidence that alignment and decision forums do not vary on one axis; admission or rejection of `BUC-GIB-PIPE-03`. |
| **Supersession links** | Carries the alignment mode of [`SC-GIB-PIPE-01-A`](SC-GIB-PIPE-01-A.md) revision `1.0` (`Superseded`). |
| **Change rationale** | Revision `1.1`: banker-language pass; wording only, meaning unchanged. Revision `1.0`: raised by the model revision of 2026-10-07 and not admitted. The two Q146 modes of the former recurring-session scenario are placed on one axis, forum purpose, under the promoted use case. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 | Raised as a candidate scenario of `BUC-GIB-PIPE-03`; `Evidence-backed`, no forum observed; not admitted. | Coverage intent model owner (as candidate, not admitted) | `BUC-GIB-PIPE-03`, `SC-GIB-PIPE-01-A` |
| `1.1` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner (as candidate, not admitted) | None; wording only |

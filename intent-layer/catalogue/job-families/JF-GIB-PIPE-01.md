# JF-GIB-PIPE-01 - Opportunity Pipeline Management

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work through which GIB teams manage potential and active opportunities from Idea through Closed. Teams challenge each opportunity's direction and deliberately progress, park, reactivate, or exit it. |
| **Business purpose** | Maintain enough shared discipline to direct the firm's effort and protect the outlook. Do not force false certainty or heavy reporting onto ambiguous early opportunities. |
| **Lifecycle position** | Cross-lifecycle: Idea, Opportunity, Pitch, Mandate, Closed, and Parked or reactivated states. |
| **Scope boundary** | Begins when a Signal, a veiled client comment or relationship context suggests a plausible transaction path. It also begins when an existing opportunity needs review, or when a scheduled forum reviews the portfolio. Ends when the opportunity is closed, deliberately exited, or parked with explicit re-entry conditions and an owner. |
| **Included work** | Recognise ideas and take them under ownership, or deliberately decline them. Assemble evidence and views. Challenge maturity and direction. Choose advance, reshape, monitor, park, reactivate, or exit. Confirm the owner and the next step. Review the portfolio and redirect effort, ownership, pursuit, or capacity. |
| **Excluded work** | Institution-level relationship quality. Detailed deal execution. Preparing and conducting one client Interaction. Judging a Signal before it suggests a transaction path. Resolving individual commitments that are drifting or waiting on the senior; that is `JF-GIB-ACT-01` (candidate). |
| **Primary business outcomes** | [`BO-GIB-PIPE-01`](../business-outcomes/BO-GIB-PIPE-01.md) - Improve opportunity portfolio accuracy. |
| **Business use cases** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) - Review one opportunity and decide its next move; [`BUC-GIB-PIPE-02`](../business-use-cases/BUC-GIB-PIPE-02.md) (candidate) - Recognise an idea as an opportunity; [`BUC-GIB-PIPE-03`](../business-use-cases/BUC-GIB-PIPE-03.md) (candidate) - Review the portfolio and redirect effort. |
| **JTBDs** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) - Maintain disciplined opportunity management. |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-PIPELINE-TEAM`](../actors/ACTOR-COV-PIPELINE-TEAM.md); `ACTOR-COV-SUPPORT-TEAM` (candidate); business heads as conflict resolvers `[validate actor]` (Q142). |
| **Adjacent job families** | [`JF-GIB-INTEL-01`](JF-GIB-INTEL-01.md) Signal triage; [`JF-GIB-REL-01`](JF-GIB-REL-01.md) client relationship management; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) high-stakes client Interactions; `JF-GIB-ACT-01` (candidate) actions and commitments. The commitment step S5 of `BUC-GIB-PIPE-01` and `BUC-GIB-PIPE-03` serves `JF-GIB-ACT-01`; only above-threshold items enter it. |
| **Common business rules and controls** | Preserve uncertainty and the source trail. Allow plural early views. Converge on one canonical view as evidence matures. No forced probability; economics stay qualitative at idea stage (Q143). Keep an accountable owner. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. The rule has no value of its own and is written into every use case. It is never a scenario or a use case. |
| **Known variations** | Coverage versus product banking; M&A versus ECM/DCM; priority versus developing clients; domestic versus multi-region work `[validate]` (Q148). Within `BUC-GIB-PIPE-01`, the condition of the opportunity when the review fires: closing window, parked, early after recognition, exit-worthy, stalled (scenarios B, C, D, F, G). Within `BUC-GIB-PIPE-03`, forum purpose: alignment-only or decision (Q146). Within `BUC-GIB-PIPE-02`, origin of the idea: Signal or Interaction (candidate scenarios, no files). Restricted cross-GIB situations are no longer a variation. They are the control rule. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), especially Q113-Q117 and Q140-Q151; model revision proposal of 2026-10-07. Q139: no concrete opportunity episode. |
| **Evidence maturity** | `Evidence-backed` - the standing job family and its boundaries are supported. The catalogue grouping was not independently confirmed across GIB. |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-PIPE-01` | Review one opportunity and decide its next move | Produces a challenge-tested judgment on one existing opportunity. The judgment has an owner, a next step or a park or exit, and a review condition. | Trigger narrowed at revision `3.0` to one existing opportunity. Commitments are sent to the owner's job family (Q136); only above-threshold items enter `BUC-GIB-ACT-01` (candidate). |
| `BUC-GIB-PIPE-02` (candidate) | Recognise an idea as an opportunity | Produces one idea taken into shared management with a named owner and explicit uncertainty, or a recorded decision not to recognise it. | Not admitted. Also serves `JTBD-GIB-INTEL-01` cross-family. Begins where `BUC-GIB-INTEL-01` S6 or `BUC-GIB-MEET-01` S6 ends. |
| `BUC-GIB-PIPE-03` (candidate) | Review the portfolio and redirect effort | Produces an accepted shared picture of the portfolio with explicit, owned redirections. | Not admitted. Promoted from `SC-GIB-PIPE-01-A`; unit of value is the portfolio. |
| `JTBD-GIB-PIPE-01` | Maintain disciplined opportunity management | Expresses the enduring progress sought across the family; served by all three use cases. | Confirmed for Senior Coverage MDs, not yet across all GIB cohorts. |
| `SC-GIB-PIPE-01-B`, `-C`, `-D`, `-F`, `-G` | Scenarios of `BUC-GIB-PIPE-01` | Conditions of one opportunity when the review fires. | F and G added 2026-10-07; D re-scoped to after recognition. |
| `SC-GIB-PIPE-03-A`, `-B` (candidates) | Scenarios of `BUC-GIB-PIPE-03` | Forum purpose: alignment-only or decision (Q146). | Admitted or rejected with their parent. |
| `SC-GIB-PIPE-01-A`, `-E` | Superseded scenarios | Retained for traceability. | A promoted to `BUC-GIB-PIPE-03`; E retired to the control rule. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.3` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader Line MD and product-banker validation, or when `BUC-GIB-PIPE-02` or `BUC-GIB-PIPE-03` is admitted or rejected. |
| **Review triggers** | Changed lifecycle boundary, evidence that origination and active-deal management require separate families, changed membership, or cross-LOB findings that invalidate one shared family. |
| **Supersession links** | None. This is the first governed canonical revision of the existing stable ID. |
| **Change rationale** | Revision `1.3`: terminology pass (Interaction, Engagement); wording only, meaning unchanged. Revision `1.2`: banker-language pass; wording only, meaning unchanged. Title changed from "Opportunity Pipeline Stewardship". Revision `1.1`: the model revision of 2026-10-07 found the family holds three use cases, not one. It also found that restricted-information handling is a control rule rather than a variation. Membership, boundaries, rules and variations updated; definition, purpose and maturity unchanged. Revision `1.0` established disciplined opportunity management as the stable business-process family rather than a product or reporting module. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Coverage interview through Q151 and cross-LOB pipeline synthesis | Promoted as `Evidence-backed`; preserve cross-LOB and boundary questions for validation. | Coverage intent model owner | `BO-GIB-PIPE-01`, `BUC-GIB-PIPE-01`, `JTBD-GIB-PIPE-01` |
| `1.1` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested every job and use case against Q01-Q151 | Revised in place: three use cases listed (two candidates, not admitted); scenario changes recorded; `JF-GIB-ACT-01` (candidate) named as adjacent; control rule added; known variations updated. Maturity unchanged. | Coverage intent model owner | `BUC-GIB-PIPE-01`, `BUC-GIB-PIPE-02`, `BUC-GIB-PIPE-03`, `JTBD-GIB-PIPE-01`, scenarios A-G and 03-A/B |
| `1.2` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Title changed from "Opportunity Pipeline Stewardship". Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None; wording only |
| `1.3` | 2026-10-07 | No new source evidence; terminology pass | Terminology: Interaction (a live exchange with a client: call, virtual or in person) and Engagement (any client contact, including email) adopted as governed terms. Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None; wording only |

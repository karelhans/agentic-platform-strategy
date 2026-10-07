# JF-GIB-PIPE-01 - Opportunity Pipeline Stewardship

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work through which GIB teams steward potential and active opportunities from Idea through Closed, challenge their trajectory, and deliberately progress, park, reactivate, or exit them. |
| **Business purpose** | Maintain enough shared discipline to direct franchise effort and protect the outlook without forcing false certainty or burdensome reporting onto ambiguous early opportunities. |
| **Lifecycle position** | Cross-lifecycle: Idea, Opportunity, Pitch, Mandate, Closed, and Parked or reactivated states. |
| **Scope boundary** | Begins when a signal, veiled client comment or relationship context suggests a plausible transaction path, when an existing opportunity needs review, or when a scheduled forum reviews the portfolio; ends when the opportunity is closed, deliberately exited, or parked with explicit re-entry conditions and ownership. |
| **Included work** | Recognize ideas and admit them to stewardship or deliberately decline them; assemble evidence and views; challenge maturity and trajectory; choose advance, reshape, monitor, park, reactivate, or exit; confirm stewardship and next movement; review the portfolio and redirect effort, ownership, pursuit, or capacity. |
| **Excluded work** | Institution-level relationship quality, detailed deal execution, preparation and conduct of one client meeting, judging a signal before it suggests a transaction path, and resolution of individual commitments that are drifting or waiting on the senior (`JF-GIB-ACT-01`, candidate). |
| **Primary business outcomes** | [`BO-GIB-PIPE-01`](../business-outcomes/BO-GIB-PIPE-01.md) - Improve opportunity portfolio accuracy. |
| **Business use cases** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) - Review one opportunity and decide its next move; [`BUC-GIB-PIPE-02`](../business-use-cases/BUC-GIB-PIPE-02.md) (candidate) - Recognise an idea as an opportunity; [`BUC-GIB-PIPE-03`](../business-use-cases/BUC-GIB-PIPE-03.md) (candidate) - Review the portfolio and redirect effort. |
| **JTBDs** | [`JTBD-GIB-PIPE-01`](../jtbd/JTBD-GIB-PIPE-01.md) - Maintain disciplined opportunity stewardship. |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-PIPELINE-TEAM`](../actors/ACTOR-COV-PIPELINE-TEAM.md); `ACTOR-COV-SUPPORT-TEAM` (candidate); business heads as conflict resolvers `[validate actor]` (Q142). |
| **Adjacent job families** | [`JF-GIB-INTEL-01`](JF-GIB-INTEL-01.md) intelligence triage; [`JF-GIB-REL-01`](JF-GIB-REL-01.md) client relationship management; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) consequential client meetings; `JF-GIB-ACT-01` (candidate) actions and commitments, served by the commitment step S5 of `BUC-GIB-PIPE-01` and `BUC-GIB-PIPE-03` and entered only by above-threshold items. |
| **Common business rules and controls** | Preserve uncertainty and provenance; allow plural early views; increase canonical convergence as evidence matures; no forced probability and qualitative economics at idea stage (Q143); retain accountable stewardship. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the entitled group, others may know that a restricted situation exists and who owns it; further visibility depends on the restriction; Coverage orchestrates and business heads arbitrate. The rule has no value of its own and is written into every use case; it is never a scenario or a use case. |
| **Known variations** | Coverage versus product banking; M&A versus ECM/DCM; priority versus developing clients; domestic versus multi-region work `[validate]` (Q148). Within `BUC-GIB-PIPE-01`, the condition of the opportunity when the review fires: closing window, parked, early after recognition, exit-worthy, stalled (scenarios B, C, D, F, G). Within `BUC-GIB-PIPE-03`, forum purpose: alignment-only or decision (Q146). Within `BUC-GIB-PIPE-02`, origin of the idea: signal or conversation (candidate scenarios, no files). Restricted cross-GIB situations are no longer a variation; they are the control rule. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), especially Q113-Q117 and Q140-Q151; model revision proposal of 2026-10-07. Q139: no concrete opportunity episode. |
| **Evidence maturity** | `Evidence-backed` - the standing job family and boundaries are supported, but the catalogue grouping was not independently confirmed across GIB. |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-PIPE-01` | Review one opportunity and decide its next move | Produces a challenge-tested judgment on one existing opportunity with an owner, next move or park or exit, and a review condition. | Trigger narrowed at revision `3.0` to one existing opportunity. Commitments route to the accountable owner's job family (Q136); only above-threshold items enter `BUC-GIB-ACT-01` (candidate). |
| `BUC-GIB-PIPE-02` (candidate) | Recognise an idea as an opportunity | Produces one idea admitted to shared stewardship with a steward and explicit uncertainty, or deliberate non-recognition. | Not admitted. Also serves `JTBD-GIB-INTEL-01` cross-family. Begins where `BUC-GIB-INTEL-01` S6 or `BUC-GIB-MEET-01` S6 ends. |
| `BUC-GIB-PIPE-03` (candidate) | Review the portfolio and redirect effort | Produces an accepted shared picture of the portfolio with explicit, owned redirections. | Not admitted. Promoted from `SC-GIB-PIPE-01-A`; unit of value is the portfolio. |
| `JTBD-GIB-PIPE-01` | Maintain disciplined opportunity stewardship | Expresses the enduring progress sought across the family; served by all three use cases. | Confirmed for Senior Coverage MDs, not yet across all GIB cohorts. |
| `SC-GIB-PIPE-01-B`, `-C`, `-D`, `-F`, `-G` | Scenarios of `BUC-GIB-PIPE-01` | Conditions of one opportunity when the review fires. | F and G added 2026-10-07; D re-scoped to after recognition. |
| `SC-GIB-PIPE-03-A`, `-B` (candidates) | Scenarios of `BUC-GIB-PIPE-03` | Forum purpose: alignment-only or decision (Q146). | Admitted or rejected with their parent. |
| `SC-GIB-PIPE-01-A`, `-E` | Superseded scenarios | Retained for traceability. | A promoted to `BUC-GIB-PIPE-03`; E retired to the control rule. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader Line MD and product-banker validation, or when `BUC-GIB-PIPE-02` or `BUC-GIB-PIPE-03` is admitted or rejected. |
| **Review triggers** | Changed lifecycle boundary, evidence that origination and active-deal stewardship require separate families, changed membership, or cross-LOB findings that invalidate one shared family. |
| **Supersession links** | None. This is the first governed canonical revision of the existing stable ID. |
| **Change rationale** | Revision `1.1`: the model revision of 2026-10-07 found the family holds three use cases, not one, and that restricted-information handling is a control rule rather than a variation. Membership, boundaries, rules and variations updated; definition, purpose and maturity unchanged. Revision `1.0` established disciplined opportunity stewardship as the stable business-process family rather than a product or reporting module. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Coverage interview through Q151 and cross-LOB pipeline synthesis | Promoted as `Evidence-backed`; preserve cross-LOB and boundary questions for validation. | Coverage intent model owner | `BO-GIB-PIPE-01`, `BUC-GIB-PIPE-01`, `JTBD-GIB-PIPE-01` |
| `1.1` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 re-tested every job and use case against Q01-Q151 | Revised in place: three use cases listed (two candidates, not admitted); scenario changes recorded; `JF-GIB-ACT-01` (candidate) named as adjacent; control rule added; known variations updated. Maturity unchanged. | Coverage intent model owner | `BUC-GIB-PIPE-01`, `BUC-GIB-PIPE-02`, `BUC-GIB-PIPE-03`, `JTBD-GIB-PIPE-01`, scenarios A-G and 03-A/B |

# JF-GIB-INTEL-01 - Intelligence Triage

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that recognises information may matter to a client or outcome, brings it to the accountable owner where it is held elsewhere, reduces noise, connects it to client context, exposes consequence and confidence, and routes an explicit response. |
| **Business purpose** | Preserve senior judgment for consequential change and enable timely action or confident non-action without reconstructing evidence manually or losing signals that exist elsewhere in the bank. |
| **Lifecycle position** | Cross-lifecycle and event-driven. |
| **Scope boundary** | Begins when a banker recognises information may affect a client or franchise outcome, including one they do not own, and ends when an accepted disposition and intended outcome are routed to the accountable owner's job family. |
| **Included work** | Recognise relevance beyond own remit and share in permitted form; reduce noise; identify affected context; explain consequence, timing, evidence, and confidence; support senior judgment; record disposition; route the result to the accountable owner. |
| **Excluded work** | Executing relationship outreach, changing opportunity stewardship, conducting a client meeting, or completing downstream commitments. |
| **Primary business outcomes** | [`BO-GIB-INTEL-01`](../business-outcomes/BO-GIB-INTEL-01.md) |
| **Business use cases** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md); [`BUC-GIB-INTEL-02`](../business-use-cases/BUC-GIB-INTEL-02.md) (candidate). |
| **JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md); [`JTBD-GIB-INTEL-02`](../jtbd/JTBD-GIB-INTEL-02.md) (candidate). |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate) for preparatory triage; the banker holding information for `BUC-GIB-INTEL-02` has no actor record `[validate]`. |
| **Adjacent job families** | [`JF-GIB-REL-01`](JF-GIB-REL-01.md) relationship management; [`JF-GIB-PIPE-01`](JF-GIB-PIPE-01.md) pipeline stewardship; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) consequential client meetings; [`JF-GIB-ACT-01`](JF-GIB-ACT-01.md) (candidate) actions and commitments, served by the commitment step at the end of every use case in this family. |
| **Common business rules and controls** | Preserve provenance and uncertainty; calibrate scrutiny to consequence and time; allow explicit non-action; respect entitlement and sensitivity. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach, or ownership conflict arises outside the entitled group, others may know that a restricted situation exists and who owns it; further visibility depends on the restriction; Coverage orchestrates and business heads arbitrate. |
| **Known variations** | Short-window signals; uncertain high-impact signals; deliberate monitoring; accumulated signals after an unattended window (candidate); converging changes or cross-client implication (candidate); information held by a banker who does not own the affected client (candidate use case). Client sensitivity is handled by the control rule rather than as a variation. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q71-Q91; Round 1 record Q02, Q06, Q07, Q39 to Q42, Q57 to Q62, Q70, Q74, Q136, Q142, Q145 as applied by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md). |
| **Evidence maturity** | `Evidence-backed` |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-INTEL-01` | Triage and route consequential intelligence | Produces one accepted intelligence disposition and destination. | Downstream action belongs to the accountable owner's job family. |
| `BUC-GIB-INTEL-02` (candidate) | Bring a held signal to its accountable owner | Gets a signal held elsewhere into the owner's triage in permitted form. | Ends at `BUC-GIB-INTEL-01-S1`; not admitted. |
| `JTBD-GIB-INTEL-01` | Isolate and judge consequential change | Expresses the enduring senior progress sought. | Confirmed for Senior Coverage MDs. |
| `JTBD-GIB-INTEL-02` (candidate) | Bring held information to its accountable owner | Expresses the holder's progress, without which the senior job fails. | Wording not yet put to a participant; not admitted. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader signal-provider and Line MD validation; when the candidate records are admitted or rejected. |
| **Review triggers** | Changed disposition boundary, destination ownership, evidence rules, actor authority, or evidence that separate families are required. |
| **Supersession links** | None. |
| **Change rationale** | Apply the model revision of 2026-10-07: widen the scope boundary to information a banker does not own, list the candidate use case and job, add the control rule, update variations and adjacent families. Family identity unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent evidence through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BO-GIB-INTEL-01`, `BUC-GIB-INTEL-01`, `JTBD-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q02, Q06, Q07, Q142, Q145 and the scenario evidence re-read | Revised in place; candidates listed and marked, none admitted. | `[validate: intent model owner]` | `BUC-GIB-INTEL-02`, `JTBD-GIB-INTEL-02`, `SC-GIB-INTEL-01-D`, `SC-GIB-INTEL-01-E` |

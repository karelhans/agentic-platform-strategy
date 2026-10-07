# JF-GIB-INTEL-01 - Intelligence Triage

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that recognises a Signal may matter to a client or outcome. It brings the Signal to its owner when it is held elsewhere. It reduces noise, connects the Signal to client context, and shows consequence and confidence. It ends by sending an explicit Decision to the owner's View. |
| **Business purpose** | Preserve senior judgment for material change. Enable timely action, or a confident Decision to monitor or dismiss, without rebuilding evidence by hand or losing Signals held elsewhere in the bank. |
| **Lifecycle position** | Cross-lifecycle and event-driven. |
| **Scope boundary** | Begins when a banker recognises that information may affect a client or firm outcome, including one they do not own. Ends when the owner's job family receives an accepted Decision and intended outcome. |
| **Included work** | Recognise relevance beyond own remit and share in permitted form; reduce noise; identify affected context; explain consequence, timing, evidence, and confidence; support senior judgment; record the Decision and Rationale; send the result to the owner. |
| **Excluded work** | Carrying out relationship outreach, changing opportunity pipeline management, conducting a client meeting, or completing downstream commitments. |
| **Primary business outcomes** | [`BO-GIB-INTEL-01`](../business-outcomes/BO-GIB-INTEL-01.md) |
| **Business use cases** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md); [`BUC-GIB-INTEL-02`](../business-use-cases/BUC-GIB-INTEL-02.md) (candidate). |
| **JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md); [`JTBD-GIB-INTEL-02`](../jtbd/JTBD-GIB-INTEL-02.md) (candidate). |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate) for preparatory triage; the banker holding information for `BUC-GIB-INTEL-02` has no actor record `[validate]`. |
| **Adjacent job families** | [`JF-GIB-REL-01`](JF-GIB-REL-01.md) relationship management; [`JF-GIB-PIPE-01`](JF-GIB-PIPE-01.md) opportunity pipeline management; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) high-stakes client meetings; [`JF-GIB-ACT-01`](JF-GIB-ACT-01.md) (candidate) actions and commitments, served by the commitment step at the end of every use case in this family. |
| **Common business rules and controls** | Preserve the source trail and uncertainty; match scrutiny to consequence and time; allow an explicit Decision to monitor or dismiss; respect access and sensitivity. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach, or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Known variations** | Short-window Signals; uncertain high-impact Signals; monitor or dismiss; accumulated Signals after an unattended window (candidate); converging changes or cross-client implication (candidate); information held by a banker who does not own the affected client (candidate use case). The control rule handles client sensitivity; it is not a variation. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q71-Q91; Round 1 record Q02, Q06, Q07, Q39 to Q42, Q57 to Q62, Q70, Q74, Q136, Q142, Q145 as applied by the [model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md). |
| **Evidence maturity** | `Evidence-backed` |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-INTEL-01` | Triage and send a material signal | Produces one accepted Decision and View for a Signal. | Downstream action belongs to the owner's job family. |
| `BUC-GIB-INTEL-02` (candidate) | Bring a held signal to its accountable owner | Gets a Signal held elsewhere into the owner's triage in permitted form. | Ends at `BUC-GIB-INTEL-01-S1`; not admitted. |
| `JTBD-GIB-INTEL-01` | Isolate and judge material change | Expresses the enduring senior progress sought. | Confirmed for Senior Coverage MDs. |
| `JTBD-GIB-INTEL-02` (candidate) | Bring held information to its accountable owner | Expresses the holder's progress, without which the senior job fails. | Wording not yet put to a participant; not admitted. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader signal-provider and Line MD validation; when the candidate records are admitted or rejected. |
| **Review triggers** | Changed Decision boundary, View ownership, evidence rules, actor authority, or evidence that separate families are required. |
| **Supersession links** | None. |
| **Change rationale** | Apply the model revision of 2026-10-07: widen the scope boundary to information a banker does not own, list the candidate use case and job, add the control rule, update variations and adjacent families. Family identity unchanged. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent evidence through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BO-GIB-INTEL-01`, `BUC-GIB-INTEL-01`, `JTBD-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q02, Q06, Q07, Q142, Q145 and the scenario evidence re-read | Revised in place; candidates listed and marked, none admitted. | `[validate: intent model owner]` | `BUC-GIB-INTEL-02`, `JTBD-GIB-INTEL-02`, `SC-GIB-INTEL-01-D`, `SC-GIB-INTEL-01-E` |
| `1.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

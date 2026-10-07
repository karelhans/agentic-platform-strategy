# JF-GIB-MEET-01 - High-Stakes Client Meetings

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that prepares for, conducts, and interprets high-stakes client meetings. It converts each meeting into accepted learning, relationship progress, a decision state, and follow-through that has begun. |
| **Business purpose** | Use fixed client-meeting windows to learn or influence. Protect relationship quality. Make sure changed state becomes owned progress. |
| **Lifecycle position** | Across the client lifecycle: relationship development, origination, pitching, execution, and post-close relationship work. |
| **Scope boundary** | Begins when a high-stakes client meeting needs preparation. Ends when the outcome is interpreted, commitments are explicit, affected job families are updated, and the first follow-through step has begun. |
| **Included work** | Establish why now; form the starting view; align JPM posture; resolve critical uncertainty; hold the meeting; interpret the outcome; make commitments explicit; send changed state to its owner; begin the first step. |
| **Excluded work** | Enduring relationship management, full completion of downstream commitments, broad opportunity portfolio review, routine logistics, and internal management sessions without a client. |
| **Primary business outcomes** | [`BO-GIB-MEET-01`](../business-outcomes/BO-GIB-MEET-01.md) |
| **Business use cases** | [`BUC-GIB-MEET-01`](../business-use-cases/BUC-GIB-MEET-01.md). Its last step hands a follow-up client contact to `BUC-GIB-REL-02` (candidate, in `JF-GIB-REL-01`). It hands an above-threshold commitment to `BUC-GIB-ACT-01` (candidate, in `JF-GIB-ACT-01`). |
| **JTBDs** | [`JTBD-GIB-MEET-01`](../jtbd/JTBD-GIB-MEET-01.md) |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md), the VPs, associates and analysts who prepare, translate and quality-control (candidate raised by the model revision of 2026-10-07, not admitted). |
| **Adjacent job families** | `JF-GIB-REL-01` client relationship management, including `BUC-GIB-REL-02` (candidate) for a follow-up client contact after a meeting; `JF-GIB-INTEL-01` intelligence triage; `JF-GIB-PIPE-01` pipeline management; and `JF-GIB-ACT-01` actions and commitments (candidate raised by the model revision of 2026-10-07, not admitted). `JF-GIB-ACT-01` receives only a commitment that has crossed the drift or senior-dependency threshold. All other changed state is sent to the owner's job family (Q136). |
| **Common business rules and controls** | Meeting purpose and client benefit are explicit. Uncertainty stays visible. JPM posture is coherent. Confidentiality and conduct constraints apply. Follow-through has an accepted owner. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or an ownership conflict arises outside the group with access, others may know that a restricted situation exists and who owns it. Further visibility depends on the restriction. Coverage coordinates and business heads arbitrate. |
| **Known variations** | Decision-forming ([`SC-GIB-MEET-01-A`](../scenarios/SC-GIB-MEET-01-A.md)); relationship-sensitive and listening-led ([`SC-GIB-MEET-01-B`](../scenarios/SC-GIB-MEET-01-B.md)); major-commitment and cross-JPM ([`SC-GIB-MEET-01-C`](../scenarios/SC-GIB-MEET-01-C.md), may split); protocol-driven or first senior interaction ([`SC-GIB-MEET-01-D`](../scenarios/SC-GIB-MEET-01-D.md)); short-notice or unplanned ([`SC-GIB-MEET-01-E`](../scenarios/SC-GIB-MEET-01-E.md), candidate at `Hypothesis`). A Decision to monitor or dismiss is an exception path of the use case, not a scenario. Crisis or adverse-event meetings are untested and probably fold into B (Round 2 CMEET10). |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q123-Q127; Q136, Q142, Q70, Q145 for sending changed state and for the control rule. [Model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md). |
| **Evidence maturity** | `Evidence-backed`. Standing-job-family status and boundary are supported, but the family record was not separately validated across roles or LOBs. |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-MEET-01` | Prepare, conduct, and convert a high-stakes client meeting | Produces one interpreted meeting outcome, sent to its owners, with the first step begun. Kept whole in the model revision of 2026-10-07: readiness is consumed inside the same episode and is not a separate value. | Completion of downstream work belongs to the owner's job family (Q136). Only an above-threshold commitment enters `BUC-GIB-ACT-01` (candidate). |
| `JTBD-GIB-MEET-01` | Convert high-stakes client meetings into progress | Expresses the enduring progress sought across the family. | Confirmed for Senior Coverage MDs. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-07, through Q151 and the model revision of 2026-10-07. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed client-meeting episodes and supporting-team validation (Round 2 CMEET12). |
| **Review triggers** | Changed process boundary, meeting completion, actor responsibility, value delivered, or evidence that preparation and conversion are separate use cases. The last trigger was tested in the model revision of 2026-10-07 and did not fire (Q127; readiness is consumed inside the same episode). |
| **Supersession links** | None; first canonical record. |
| **Change rationale** | Model revision of 2026-10-07: review trigger wording aligned with the use case ("separate use cases"). Known variations mapped to scenarios A to E, with the protocol-driven variation now covered by scenario D. Adjacent families name `JF-GIB-ACT-01` and `BUC-GIB-REL-02` as candidates. Cross-family control rule added. Contributor cohort replaced by candidate `ACTOR-COV-SUPPORT-TEAM`. No candidate is admitted by this revision. Banker-language pass of 2026-10-07: wording only. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q123-Q127 confirmed-intent evidence | Promoted as `Evidence-backed`; observed process and broader roles remain open. | Coverage intent model owner | `BO-GIB-MEET-01`, `BUC-GIB-MEET-01`, `JTBD-GIB-MEET-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q136, Q142, Q70, Q145. | Revised in place: trigger wording aligned, scenarios D and E listed, adjacent candidates and control rule added. Maturity unchanged. | Coverage intent model owner | `BUC-GIB-MEET-01`, `SC-GIB-MEET-01-D`, `SC-GIB-MEET-01-E`; candidates `JF-GIB-ACT-01`, `BUC-GIB-REL-02`, `ACTOR-COV-SUPPORT-TEAM` |
| `1.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Title changed from "Consequential Client Meetings". Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None. |

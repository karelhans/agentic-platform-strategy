# JF-GIB-MEET-01 - Consequential Client Meetings

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that prepares for, conducts, interprets, and converts consequential client interactions into accepted learning, relationship movement, decision state, and initiated follow-through. |
| **Business purpose** | Use fixed client-interaction windows to learn or influence while protecting relationship quality and ensuring changed state becomes owned progress. |
| **Lifecycle position** | Cross-lifecycle; occurs during relationship development, origination, pitching, execution, and post-close engagement. |
| **Scope boundary** | Begins when a consequential client interaction requires preparation and ends when its outcome is interpreted, commitments are explicit, affected job families are updated, and first follow-through has begun. |
| **Included work** | Establish why now; form hypothesis; align JPM posture; resolve critical uncertainty; engage; interpret outcome; make commitments explicit; route changed state; initiate first movement. |
| **Excluded work** | Enduring institution relationship stewardship, full downstream commitment completion, broad opportunity portfolio review, routine logistics, and non-client internal management sessions. |
| **Primary business outcomes** | [`BO-GIB-MEET-01`](../business-outcomes/BO-GIB-MEET-01.md) |
| **Business use cases** | [`BUC-GIB-MEET-01`](../business-use-cases/BUC-GIB-MEET-01.md). Its last step hands a follow-up client contact to `BUC-GIB-REL-02` (candidate, in `JF-GIB-REL-01`) and an above-threshold commitment to `BUC-GIB-ACT-01` (candidate, in `JF-GIB-ACT-01`). |
| **JTBDs** | [`JTBD-GIB-MEET-01`](../jtbd/JTBD-GIB-MEET-01.md) |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md), the VPs, associates and analysts who prepare, translate and quality-control (candidate raised by the model revision of 2026-10-07, not admitted). |
| **Adjacent job families** | `JF-GIB-REL-01` client relationship management, including `BUC-GIB-REL-02` (candidate) for a follow-up client contact after a meeting; `JF-GIB-INTEL-01` intelligence triage; `JF-GIB-PIPE-01` pipeline stewardship; and `JF-GIB-ACT-01` actions and commitments (candidate raised by the model revision of 2026-10-07, not admitted), which receives only a commitment that has crossed the drift or senior-dependency threshold. Changed state otherwise routes to the accountable owner's job family (Q136). |
| **Common business rules and controls** | Meeting purpose and client benefit are explicit; uncertainty remains visible; JPM posture is coherent; confidentiality and conduct constraints apply; follow-through has an accepted owner. Cross-family control rule (Q70, Q145, Q142): when evidence, outreach or ownership conflict arises outside the entitled group, others may know that a restricted situation exists and who owns it; further visibility depends on the restriction; Coverage orchestrates and business heads arbitrate. |
| **Known variations** | Decision-forming ([`SC-GIB-MEET-01-A`](../scenarios/SC-GIB-MEET-01-A.md)); relationship-sensitive and listening-led ([`SC-GIB-MEET-01-B`](../scenarios/SC-GIB-MEET-01-B.md)); major-commitment and cross-JPM ([`SC-GIB-MEET-01-C`](../scenarios/SC-GIB-MEET-01-C.md), may split); protocol-driven or first senior interaction ([`SC-GIB-MEET-01-D`](../scenarios/SC-GIB-MEET-01-D.md)); short-notice or unplanned ([`SC-GIB-MEET-01-E`](../scenarios/SC-GIB-MEET-01-E.md), candidate at `Hypothesis`). Deliberate no-action is an exception path of the use case, not a scenario. Crisis or adverse-event meetings are untested and probably fold into B (Round 2 CMEET10). |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q123-Q127; Q136, Q142, Q70, Q145 for routing and the control rule. [Model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md). |
| **Evidence maturity** | `Evidence-backed` - standing-job-family status and boundary are supported, but the family record was not separately validated across roles or LOBs. |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-MEET-01` | Prepare, conduct, and convert a consequential client meeting | Produces one interpreted and routed interaction outcome with initiated movement. Kept whole in the model revision of 2026-10-07: readiness is consumed inside the same episode and is not a separate value. | Completion of downstream work belongs to the accountable owner's job family (Q136); only an above-threshold commitment enters `BUC-GIB-ACT-01` (candidate). |
| `JTBD-GIB-MEET-01` | Convert consequential client interactions into progress | Expresses the enduring progress sought across the family. | Confirmed for Senior Coverage MDs. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-07, through Q151 and the model revision of 2026-10-07. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After observed client-meeting episodes and supporting-team validation (Round 2 CMEET12). |
| **Review triggers** | Changed process boundary, meeting completion, actor responsibility, value delivered, or evidence that preparation and conversion are separate use cases. The last trigger was tested in the model revision of 2026-10-07 and did not fire (Q127; readiness consumed inside the same episode). |
| **Supersession links** | None; first canonical record. |
| **Change rationale** | Model revision of 2026-10-07: review trigger wording aligned with the use case ("separate use cases"); known variations mapped to scenarios A to E, with the protocol-driven variation now covered by scenario D; adjacent families name `JF-GIB-ACT-01` and `BUC-GIB-REL-02` as candidates; cross-family control rule added; contributor cohort replaced by candidate `ACTOR-COV-SUPPORT-TEAM`. No candidate is admitted by this revision. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q123-Q127 confirmed-intent evidence | Promoted as `Evidence-backed`; observed process and broader roles remain open. | Coverage intent model owner | `BO-GIB-MEET-01`, `BUC-GIB-MEET-01`, `JTBD-GIB-MEET-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q136, Q142, Q70, Q145. | Revised in place: trigger wording aligned, scenarios D and E listed, adjacent candidates and control rule added. Maturity unchanged. | Coverage intent model owner | `BUC-GIB-MEET-01`, `SC-GIB-MEET-01-D`, `SC-GIB-MEET-01-E`; candidates `JF-GIB-ACT-01`, `BUC-GIB-REL-02`, `ACTOR-COV-SUPPORT-TEAM` |

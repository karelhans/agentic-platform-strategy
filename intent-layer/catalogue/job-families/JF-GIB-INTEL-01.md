# JF-GIB-INTEL-01 - Intelligence Triage

## Record

| Field | Value |
| --- | --- |
| **Definition** | Work that reduces noise, connects new information to client context, exposes consequence and confidence, and routes an explicit response. |
| **Business purpose** | Preserve senior judgment for consequential change and enable timely action or confident non-action without reconstructing evidence manually. |
| **Lifecycle position** | Cross-lifecycle and event-driven. |
| **Scope boundary** | Begins when new information may affect a client or franchise outcome and ends when an accepted disposition and intended outcome are routed to the destination job family. |
| **Included work** | Reduce noise; identify affected context; explain consequence, timing, evidence, and confidence; support senior judgment; record disposition; route the result. |
| **Excluded work** | Executing relationship outreach, changing opportunity stewardship, conducting a client meeting, or completing downstream commitments. |
| **Primary business outcomes** | [`BO-GIB-INTEL-01`](../business-outcomes/BO-GIB-INTEL-01.md) |
| **Business use cases** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Responsible actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); contributing validation and evidence roles remain `[validate]`. |
| **Adjacent job families** | [`JF-GIB-REL-01`](JF-GIB-REL-01.md) relationship management; [`JF-GIB-PIPE-01`](JF-GIB-PIPE-01.md) pipeline stewardship; [`JF-GIB-MEET-01`](JF-GIB-MEET-01.md) consequential client meetings. Actions and commitments remains an uncatalogued adjacent job family. |
| **Common business rules and controls** | Preserve provenance and uncertainty; calibrate scrutiny to consequence and time; allow explicit non-action; respect entitlement and sensitivity. |
| **Known variations** | Short-window signals, uncertain high-impact signals, deliberate monitoring, client sensitivity, and cross-client implications. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q71-Q91. |
| **Evidence maturity** | `Evidence-backed` |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `BUC-GIB-INTEL-01` | Triage and route consequential intelligence | Produces one accepted intelligence disposition and destination. | Downstream action belongs to its destination job family. |
| `JTBD-GIB-INTEL-01` | Isolate and route consequential intelligence | Expresses the enduring senior progress sought. | Confirmed for Senior Coverage MDs. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-02 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader signal-provider and Line MD validation. |
| **Review triggers** | Changed disposition boundary, destination ownership, evidence rules, actor authority, or evidence that separate families are required. |
| **Supersession links** | None. |
| **Change rationale** | Promote the existing evidence-backed family without semantic change. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent evidence through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BO-GIB-INTEL-01`, `BUC-GIB-INTEL-01`, `JTBD-GIB-INTEL-01` |

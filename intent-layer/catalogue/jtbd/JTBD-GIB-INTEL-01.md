# JTBD-GIB-INTEL-01 - Isolate And Judge Consequential Change

## Record

| Field | Value |
| --- | --- |
| **ID** | `JTBD-GIB-INTEL-01` |
| **Parent business use case(s)** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md); [`BUC-GIB-INTEL-02`](../business-use-cases/BUC-GIB-INTEL-02.md) (candidate; the senior job fails when the signal never arrives, Q02). |
| **Job owner** | Senior Coverage MD. |
| **Responsible actor archetypes** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate) for preparatory triage. |
| **Job statement** | When new information may affect my clients or franchise, help me isolate consequential change, understand its client-specific implications and evidential strength, and choose the appropriate response and intended outcome, so we act early when it matters, confidently do nothing when it does not, and avoid surprises without consuming senior attention on noise. |
| **Situation and triggers** | New information may materially affect a client, relationship, opportunity, meeting, commitment, or franchise outcome. |
| **Desired progress** | Move from abundant, weakly connected information to an accepted client-specific interpretation and disposition. |
| **Required judgment** | Whether the change matters, is credible enough for the contemplated use, warrants response, and changes the intended client outcome. |
| **Desired outcome** | Timely appropriate response or confident non-action, with fewer surprises and less senior attention consumed by noise. |
| **Unwanted trade-offs** | Weak escalation, false confidence, unnecessary action, missed consequential change, or repeated manual verification. |
| **Current process, workaround, and pain** | Evidence is fragmented, context is incomplete, and confidence is costly to reconstruct `[validate observed process]`. |
| **Related scenarios** | `SC-GIB-INTEL-01-A` through `SC-GIB-INTEL-01-E`; D and E are candidates. |
| **Success signals** | Fewer surprises; less noise; less manual verification; earlier relevance; better conversations; appropriate non-action; faster movement. |
| **Evidence** | [Coverage evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), confirmed at Q91. |
| **Evidence maturity** | `Confirmed` for the Senior Coverage MD cohort. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After broader Line MD validation or contradictory evidence. |
| **Review triggers** | Changed owner, materiality judgment, response boundary, desired outcome, success evidence, or cross-LOB applicability. |
| **Supersession links** | None; first governed canonical revision of the existing stable ID. |
| **Change rationale** | Model revision of 2026-10-07: retitle to the statement's own progress ("route" is a use case step, Q89), add the candidate parent use case, support-team cohort, and scenarios D and E; statement unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q91 confirmation and supporting Q71-Q90 evidence | Promoted to `Confirmed` for Senior Coverage MDs. | Coverage intent model owner | `BUC-GIB-INTEL-01`, actor and scenarios A-C |
| `1.1` | 2026-10-07 | [Model revision of 2026-10-07](../../proposals/model-revision-2026-10-07.md); Q89, Q02 re-read | Revised in place; title changed, statement and maturity unchanged. Candidate references not admitted. | `[validate: intent model owner]` | `BUC-GIB-INTEL-02`, `SC-GIB-INTEL-01-D`, `SC-GIB-INTEL-01-E`, `JF-GIB-INTEL-01` |

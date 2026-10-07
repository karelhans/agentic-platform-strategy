# BO-GIB-INTEL-01 - Improve Consequential Intelligence Response

## Record

| Field | Value |
| --- | --- |
| **Outcome statement** | Reduce consequential client and franchise surprises from `[baseline]` to `[target]` by `[timeframe]`, while improving timely, appropriate response without increasing senior attention spent on noise or unnecessary action `[validate]`. |
| **Business rationale** | Earlier recognition and proportionate disposition of consequential change can protect client relevance, franchise judgment, and intervention windows. |
| **Scope** | Intelligence potentially affecting Senior Coverage MD clients or franchise outcomes. |
| **Accountable business owner** | Coverage intelligence outcome owner `[validate]`. |
| **Primary measure** | Consequential surprises identified after the useful response window `[validate definition]`. |
| **Baseline** | `[validate]` |
| **Target and timeframe** | `[validate]` |
| **Guardrail measures** | Senior review burden; weak escalations; unnecessary client action; unsupported use of uncertain evidence. |
| **Leading indicators** | Earlier client relevance; reduced manual verification; explicit non-action; elapsed time from signal to accepted disposition. |
| **Contributing job families** | [`JF-GIB-INTEL-01`](../job-families/JF-GIB-INTEL-01.md) |
| **Contributing business use cases** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md); [`BUC-GIB-INTEL-02`](../business-use-cases/BUC-GIB-INTEL-02.md) (candidate; a signal that never reaches its owner is a consequential surprise under the primary measure). |
| **Dependencies and external factors** | Source availability and quality, client context, evidence permissions, market timing, and response authority. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), Q05-Q08 and Q71-Q91. |
| **Evidence maturity** | `Hypothesis` - direction is supported, but no approved measurement contract exists. |

## Measurement Contract

| Measure | Definition | Source | Cadence | Owner | Baseline | Target | Caveats |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Consequential surprises | Material client or franchise changes recognized only after useful response time had passed `[validate]`. | Accepted dispositions and subsequent outcome reviews `[validate]`. | Quarterly `[validate]`. | Coverage intelligence outcome owner `[validate]`. | `[validate]` | `[validate]` | Must distinguish unforeseeable events from missed evidence. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | When outcome measurement is defined or new participant evidence changes the desired result. |
| **Review triggers** | Changed outcome, measure, response boundary, source constraints, or unintended escalation burden. |
| **Supersession links** | None; first governed canonical revision of the existing stable ID. |
| **Change rationale** | Model revision of 2026-10-07: list candidate `BUC-GIB-INTEL-02` as a contributing use case. No change to measures. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Q05-Q08 and Q71-Q91 | Promoted as a measurable-outcome hypothesis. | Coverage intent model owner | `JF-GIB-INTEL-01`, `BUC-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07 | Revised in place; contributing use case list widened to the candidate, measures unchanged. | `[validate: intent model owner]` | `BUC-GIB-INTEL-02` |

# BO-GIB-PIPE-01 - Improve Opportunity Portfolio Accuracy

## Record

| Field | Value |
| --- | --- |
| **Outcome statement** | Improve the accuracy of the in-scope GIB opportunity portfolio from `[baseline]` to `[target]` by `[timeframe]`, while increasing earlier recognition of viable ideas without increasing manual reporting burden, false precision, or confidentiality risk `[validate]`. |
| **Business rationale** | A more accurate opportunity portfolio allows the franchise to direct effort, protect its outlook, and reduce viable opportunity leakage before useful intervention windows close. |
| **Scope** | Potential and active GIB opportunities from Idea through Closed, beginning with the Senior Coverage MD cohort and subject to cross-LOB validation. |
| **Accountable business owner** | GIB pipeline business outcome owner `[validate]`. |
| **Primary measure** | Portfolio accuracy: agreement between the accepted portfolio assessment at each maturity stage and the eventual observed state or outcome `[validate definition]`. |
| **Baseline** | `[validate]` |
| **Target and timeframe** | `[validate]` |
| **Guardrail measures** | Manual maintenance effort; false precision in early-stage assessments; confidentiality or information-sharing incidents; viable ideas excluded before appropriate challenge. |
| **Leading indicators** | Time from relevant evidence to recognized idea and proportion of ideas with accountable stewardship (produced by `BUC-GIB-PIPE-02`, candidate); opportunities deliberately advanced, parked, or exited (`BUC-GIB-PIPE-01`); effort allocation across opportunities and time spent reconstructing pipeline status (`BUC-GIB-PIPE-03`, candidate). |
| **Contributing job families** | [`JF-GIB-PIPE-01`](../job-families/JF-GIB-PIPE-01.md) - Opportunity pipeline stewardship. |
| **Contributing business use cases** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) - Review one opportunity and decide its next move; [`BUC-GIB-PIPE-02`](../business-use-cases/BUC-GIB-PIPE-02.md) (candidate) - Recognise an idea as an opportunity, which carries the leading indicator "earlier idea recognition"; [`BUC-GIB-PIPE-03`](../business-use-cases/BUC-GIB-PIPE-03.md) (candidate) - Review the portfolio and redirect effort, which carries effort allocation. Candidates are not admitted; their contribution is a hypothesis until then. |
| **Dependencies and external factors** | Client candor, market timing, product and regional coordination, data availability, legal and control restrictions, and the maturity of the opportunity. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), especially Q113-Q117 and Q149. |
| **Evidence maturity** | `Hypothesis` - the direction is evidence-backed, but no approved baseline, target, timeframe, or measurement contract exists. |

## Measurement Contract

| Measure | Definition | Source | Cadence | Owner | Baseline | Target | Caveats |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Portfolio accuracy | Comparison of accepted stage-appropriate assessments with later observed trajectory and outcome `[validate calculation and inclusion rules]`. | Authoritative opportunity history and review decisions `[validate]`. | Quarterly and annual `[validate]`. | GIB pipeline business outcome owner `[validate]`. | `[validate]` | `[validate]` | Early-stage views may legitimately differ; accuracy must not reward false certainty or discourage idea capture. |
| Earlier idea recognition | Elapsed time from material evidence becoming available to accountable pipeline recognition `[validate]`. | Evidence provenance and opportunity history `[validate]`. | Monthly `[validate]`. | Coverage pipeline governance `[validate]`. | `[validate]` | `[validate]` | Causality to commercial outcomes is unproven. The recognition event is the completion of `BUC-GIB-PIPE-02` (candidate); measure definition unchanged. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.1` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | GIB pipeline business outcome owner `[validate]` |
| **Next review** | When baseline and target evidence is available, or after the next cross-LOB pipeline validation round. |
| **Review triggers** | Changed outcome definition, approved measure or target, evidence that accuracy creates perverse incentives, changed scope, or material revision to linked pipeline work. |
| **Supersession links** | None. This is the first governed canonical revision of the existing stable ID. |
| **Change rationale** | Revision `1.1`: the model revision of 2026-10-07 split the pipeline family into three use cases; contributing use cases and leading indicators now name which use case produces each. No change to the outcome statement, measures, baseline, target, or maturity. Revision `1.0` promoted the current evidence-based outcome direction while explicitly retaining measurement uncertainty. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Coverage interview through Q151 and cross-LOB pipeline synthesis | Promoted as the current measurable-outcome hypothesis; baseline, target, and causal model remain `[validate]`. | Coverage intent model owner | `JF-GIB-PIPE-01`, `BUC-GIB-PIPE-01` |
| `1.1` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 | Revised in place: leading indicator "earlier idea recognition" tied to `BUC-GIB-PIPE-02` (candidate) and effort allocation to `BUC-GIB-PIPE-03` (candidate). No measure changes; maturity unchanged. | Coverage intent model owner | `BUC-GIB-PIPE-01`, `BUC-GIB-PIPE-02`, `BUC-GIB-PIPE-03` |

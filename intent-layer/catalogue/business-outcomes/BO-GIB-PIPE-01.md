# BO-GIB-PIPE-01 - Improve Opportunity Portfolio Accuracy

## Record

| Field | Value |
| --- | --- |
| **Outcome statement** | Improve the accuracy of the in-scope GIB opportunity portfolio from `[baseline]` to `[target]` by `[timeframe]`. At the same time, recognise viable ideas earlier. Do not increase manual reporting burden, false precision, or confidentiality risk `[validate]`. |
| **Business rationale** | A more accurate opportunity portfolio lets the firm direct effort and protect its outlook. It also helps the firm lose fewer viable opportunities before the window to intervene closes. |
| **Scope** | Potential and active GIB opportunities from Idea through Closed. The scope begins with the Senior Coverage MD cohort and is subject to cross-LOB validation. |
| **Accountable business owner** | GIB pipeline business outcome owner `[validate]`. |
| **Primary measure** | Portfolio accuracy: how far the accepted assessment at each stage agrees with the eventual observed state or outcome `[validate definition]`. |
| **Baseline** | `[validate]` |
| **Target and timeframe** | `[validate]` |
| **Guardrail measures** | Manual maintenance effort; false precision in early-stage assessments; confidentiality or information-sharing incidents; viable ideas excluded before appropriate challenge. |
| **Leading indicators** | Time from relevant evidence to a recognised idea, and the proportion of ideas with an accountable owner; both come from `BUC-GIB-PIPE-02` (candidate). Opportunities deliberately advanced, parked, or exited; from `BUC-GIB-PIPE-01`. Effort allocation across opportunities and time spent reconstructing pipeline status; from `BUC-GIB-PIPE-03` (candidate). |
| **Contributing job families** | [`JF-GIB-PIPE-01`](../job-families/JF-GIB-PIPE-01.md) - Opportunity pipeline management. |
| **Contributing business use cases** | [`BUC-GIB-PIPE-01`](../business-use-cases/BUC-GIB-PIPE-01.md) - Review one opportunity and decide its next move; [`BUC-GIB-PIPE-02`](../business-use-cases/BUC-GIB-PIPE-02.md) (candidate) - Recognise an idea as an opportunity, which carries the leading indicator "earlier idea recognition"; [`BUC-GIB-PIPE-03`](../business-use-cases/BUC-GIB-PIPE-03.md) (candidate) - Review the portfolio and redirect effort, which carries effort allocation. Candidates are not admitted. Until then their contribution is a starting view. |
| **Dependencies and external factors** | Client candor, market timing, product and regional coordination, data availability, legal and control restrictions, and the maturity of the opportunity. |
| **Evidence** | [Coverage Senior MD confirmed intent evidence revision 2.0](../../evidence/coverage-senior-md/confirmed-intent.md), especially Q113-Q117 and Q149. |
| **Evidence maturity** | `Hypothesis` - the direction is evidence-backed, but no approved baseline, target, timeframe, or measurement rule exists. |

## Measurement Rule

| Measure | Definition | Source | Frequency | Owner | Baseline | Target | Caveats |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Portfolio accuracy | Comparison of accepted stage-appropriate assessments with the later observed direction and outcome `[validate calculation and inclusion rules]`. | Authoritative opportunity history and review decisions `[validate]`. | Quarterly and annual `[validate]`. | GIB pipeline business outcome owner `[validate]`. | `[validate]` | `[validate]` | Early-stage views may legitimately differ. Accuracy must not reward false certainty or discourage idea capture. |
| Earlier idea recognition | Time from material evidence becoming available to the idea being recognised with an accountable owner `[validate]`. | Evidence source trail and opportunity history `[validate]`. | Monthly `[validate]`. | Coverage pipeline governance `[validate]`. | `[validate]` | `[validate]` | Causality to commercial outcomes is unproven. The recognition event is the completion of `BUC-GIB-PIPE-02` (candidate); measure definition unchanged. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | GIB pipeline business outcome owner `[validate]` |
| **Next review** | When baseline and target evidence is available, or after the next cross-LOB pipeline validation round. |
| **Review triggers** | Changed outcome definition, approved measure or target, evidence that accuracy creates perverse incentives, changed scope, or material revision to linked pipeline work. |
| **Supersession links** | None. This is the first governed canonical revision of the existing stable ID. |
| **Change rationale** | Revision `1.2`: banker-language pass; wording only, meaning unchanged. Revision `1.1`: the model revision of 2026-10-07 split the pipeline family into three use cases. Contributing use cases and leading indicators now name which use case produces each. No change to the outcome statement, measures, baseline, target, or maturity. Revision `1.0` promoted the current evidence-based outcome direction while explicitly retaining measurement uncertainty. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Coverage interview through Q151 and cross-LOB pipeline synthesis | Promoted as the current measurable-outcome hypothesis; baseline, target, and causal model remain `[validate]`. | Coverage intent model owner | `JF-GIB-PIPE-01`, `BUC-GIB-PIPE-01` |
| `1.1` | 2026-10-07 | No new source evidence; model revision of 2026-10-07 | Revised in place: leading indicator "earlier idea recognition" tied to `BUC-GIB-PIPE-02` (candidate) and effort allocation to `BUC-GIB-PIPE-03` (candidate). No measure changes; maturity unchanged. | Coverage intent model owner | `BUC-GIB-PIPE-01`, `BUC-GIB-PIPE-02`, `BUC-GIB-PIPE-03` |
| `1.2` | 2026-10-07 | No new source evidence; banker-language pass | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | None; wording only |

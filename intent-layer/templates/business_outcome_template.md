# Business Outcome Template

Use this template to define a measurable organizational result that related job families, business use cases, and JTBDs are intended to improve.

> A business outcome describes a change in business performance, not a product deliverable, feature target, or activity count.

Follow the [Intent Artifact Generation Guide](artifact_generation_guide.md) for evidence rules, stable IDs, and cross-artifact validation.

## Outcome Criteria

A valid business outcome:

- names the business result that should change;
- identifies the population, portfolio, process, or risk scope affected;
- includes a baseline, target, and timeframe where evidence exists;
- defines guardrails so improvement in one measure does not hide deterioration elsewhere;
- has an accountable business owner and a credible measurement approach;
- links to contributing job families and business use cases without claiming unsupported causality;
- remains independent of a named product, capability, feature, or delivery phase.

## Outcome Statement

> Improve `[business result]` from `[baseline]` to `[target]` by `[timeframe]` for `[scope]`, while `[quality, risk, or client guardrail]`.

When a baseline or target is not yet evidenced, mark it `[validate]` rather than inventing precision.

## Record Template

### BO-[LOB]-[NN] - [Outcome Name]

| Field | What to capture |
| --- | --- |
| **Outcome statement** | Complete measurable statement using the structure above. |
| **Business rationale** | Why this result matters to clients, the franchise, risk, or operating performance. |
| **Scope** | Population, portfolio, process, region, LOB, or time horizon covered. |
| **Accountable business owner** | Role or governing body accountable for the result, not the product team delivering support. |
| **Primary measure** | Metric that most directly represents the intended result. |
| **Baseline** | Current measured state, period, and source; otherwise `[validate]`. |
| **Target and timeframe** | Intended state and date, including the evidence or authority behind the target. |
| **Guardrail measures** | Quality, risk, client, conduct, or sustainability measures that must not deteriorate. |
| **Leading indicators** | Earlier behavioral or process signals plausibly associated with the outcome. |
| **Contributing job families** | Stable `JF-*` IDs for the business-process areas expected to contribute. |
| **Contributing business use cases** | Stable `BUC-*` IDs for bounded work that may influence the result. |
| **Dependencies and external factors** | Conditions outside the modeled work that can materially affect the outcome. |
| **Evidence** | Research, operating data, strategy decisions, or approved targets supporting the record. |
| **Evidence maturity** | `Hypothesis`, `Evidence-backed`, `Confirmed`, or `Superseded`. |

## Measurement Rule

| Measure | Definition | Source | Frequency | Owner | Baseline | Target | Caveats |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `[Measure]` | `[Calculation and inclusion rules]` | `[Authoritative source]` | `[Frequency]` | `[Responsible role]` | `[Value or validate]` | `[Value or validate]` | `[Known limitations]` |

## Record Governance

| Field | What to capture |
| --- | --- |
| **Revision** | Monotonic revision beginning at `1.0`. Preserve the stable `BO-*` ID while the same business result is being refined. |
| **Evidence cutoff** | Latest date through which outcome, baseline, target, and measurement evidence was considered. |
| **Review state** | `Current`, `Review required`, `In review`, `Candidate` (raised by a proposal, not admitted; revision below `1.0` allowed), or `Superseded`. |
| **Last reviewed** | Date of the latest explicit evidence and measurement review. |
| **Review owner** | Business outcome owner or approved evidence owner who can accept, reopen, or supersede the record. |
| **Next review** | Date, frequency, or event that prompts reconsideration. |
| **Review triggers** | Material changes to scope, owner, baseline, target, timeframe, measure definition, guardrails, causal assumptions, or linked work. |
| **Supersession links** | Prior or replacement stable IDs and revisions, or `None`. |
| **Change rationale** | Evidence delta and reason for the current revision or maturity decision. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, maturity changed, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Quality Check

- [ ] The outcome describes business performance rather than product delivery or usage.
- [ ] The primary measure reflects the result rather than a convenient proxy.
- [ ] Scope, owner, baseline, target, and timeframe are explicit or marked `[validate]`.
- [ ] Guardrails prevent a locally improved metric from masking worse quality, risk, or client outcomes.
- [ ] Leading indicators are not presented as proven causal drivers without evidence.
- [ ] Linked job families and use cases use stable IDs.
- [ ] Evidence and external dependencies are recorded.
- [ ] Promoted records include complete governance metadata and append-only revision history.
- [ ] Contradictory evidence, maturity changes, and supersession impacts remain traceable.
- [ ] Product, screen, feature, and implementation language is absent.

## Worked Example

### BO-MA-01 - Accelerate Buyer Strategy Preparation

| Field | Example |
| --- | --- |
| **Outcome statement** | Reduce the time required to prepare an accepted first-draft buyer universe from three working days to one for in-scope sell-side processes, without increasing material omissions or senior-review rework `[validate]`. |
| **Business rationale** | Faster preparation gives the deal team more time for judgment, client alignment, and outreach planning. |
| **Scope** | In-scope sell-side pitch and mandate preparation `[validate]`. |
| **Accountable business owner** | M&A business leadership `[validate]`. |
| **Primary measure** | Elapsed working time from agreed transaction criteria to accepted first-draft buyer universe. |
| **Baseline** | Three working days `[validate source and period]`. |
| **Target and timeframe** | One working day `[validate target authority and date]`. |
| **Guardrail measures** | Material candidates added later; unsupported candidates removed during review; avoidable rework after client feedback. |
| **Leading indicators** | Time to agreed criteria; evidence completeness; unresolved candidate count at senior review. |
| **Contributing job families** | `JF-MA-01` - Buyer strategy and outreach planning. |
| **Contributing business use cases** | `BUC-MA-01` - Develop and agree the buyer universe. |
| **Dependencies and external factors** | Transaction complexity, evidence availability, client constraints, confidentiality, and specialist responsiveness. |
| **Evidence** | Illustrative example based on the supplied taxonomy; replace with measured and approved evidence. |
| **Evidence maturity** | `Hypothesis`. |

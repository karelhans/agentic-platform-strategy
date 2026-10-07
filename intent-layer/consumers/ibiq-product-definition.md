# Consumer guide: IBIQ product definition on the Intent Layer

Status: Draft 1.0, 2026-10-07. Audience: the IBIQ product team and anyone writing an IBIQ product definition, persona or product use case. Owner: `[validate: name the intent model owner]`.

This guide reconciles the IBIQ Product Definition Approach with the Intent Layer. It replaces the seven artefact definitions on the IBIQ page with a two-layer model: six intent records that IBIQ cites, and three product artefacts that IBIQ owns. The definitions below are written to be pasted into the IBIQ page as they stand.

## 1. Why the two lists have to be reconciled

The IBIQ page defines business outcome, persona, job family, JTBD, scenario, product capability and use case. The Intent Layer defines business outcome, job family, business use case, JTBD, actor and scenario. Five of the shared terms are defined differently, and "use case" means two different things. Left alone, the two documents will drift the way "lens" and "job family" did before the term was retired, and a product will be able to claim alignment to a word while serving a different record.

The rule from the charter applies: products and projects consume the layer, they never define it. IBIQ therefore cites intent records by stable ID and keeps its own definitions only for artefacts that live on the product side.

## 2. The two layers

| Layer | Owner | Artefacts | Where they live |
| --- | --- | --- | --- |
| Intent | IB Knowledge Base | Business outcome, job family, business use case, JTBD, actor, scenario | `intent-layer/catalogue/`, cited by `BO-*`, `JF-*`, `BUC-*`, `JTBD-*`, `ACTOR-*`, `SC-*` |
| Product | IBIQ | Persona, product capability, product use case, alignment statement | The IBIQ product definition workspace |

Nothing in the product layer is admitted to the catalogue. Nothing in the intent layer is edited from the product layer; a contradiction raises a review trigger on the record (charter rule 6).

## 3. What changes on the IBIQ page

| IBIQ term today | Problem | Change |
| --- | --- | --- |
| Business outcome, "the measurable business result the product is meant to achieve" | Makes the outcome the product's. In the layer the outcome belongs to the business and carries a measurement rule and guardrails. The examples (faster deal execution, banker productivity, reduced operational risk) are activity or efficiency measures the catalogue explicitly rejects as primary measures. | Cite a `BO-*`. State which measure in its measurement rule the product expects to move, and in which direction. |
| Persona, "a representative user type, including role, goals and pain points" | No source. The charter allows personas only when generated from an `ACTOR-*` record. | Keep as a product artefact. Add: a persona is the product-facing expression of exactly one `ACTOR-*` record. |
| Job family, "a grouping of related JTBD" | Points the wrong way. A job family is a standing area of banker work that contains business use cases; each use case is explained by a JTBD. | Cite a `JF-*`. Use the catalogue definition. |
| JTBD, "the core goal or problem the user is trying to achieve, regardless of the tool" | Compatible. | Cite a `JTBD-*`. Keep the required shape: when X, help me Y, so that Z, without W. |
| Scenario, "where a persona applies a JTBD to achieve an outcome" | Sits under the JTBD and mixes in the persona. In the layer a scenario sits under a business use case and is the same work under different conditions, with the value delivered unchanged. Most IBIQ "scenarios" are product use cases. | Cite an `SC-*`. A product use case names one scenario it covers and one it deliberately does not. |
| Use case, "the ordered steps a user takes within the product" | Name collision with the business use case, which is the product-agnostic six-step business process with a value delivered. | Rename to product use case. Require it to cite the `BUC-*` it serves and the steps it changes. |
| Product capability | Correct where it is. | Keep. Add charter rule 5: capability support is never inferred from a JTBD; it needs its own evidence pass. |

Also add to the IBIQ page, because the list has none of them: stable IDs, maturity labels, evidence, and the alignment statement.

## 4. Reconciled definitions, ready to paste

### Intent records (cited, not redefined)

- **Business outcome (`BO-*`).** The measurable change the business wants, with a measurement rule (measure, baseline, target, direction) and guardrail measures it must not worsen. Owned by the business. A product names the outcome it serves and the measure it expects to move. Maturity today: all four are `Hypothesis` with ranges still to be filled.
- **Job family (`JF-*`).** A standing area of senior banker work, such as intelligence triage or opportunity pipeline stewardship. Contains one or more business use cases. The unit the catalogue is organised by. Four exist today, all for Coverage.
- **Business use case (`BUC-*`).** The business process inside a job family: a trigger, six steps, the judgments that stay with a human, and the value delivered by one completed run. Product-agnostic. The value delivered is the test for whether a variation is a scenario or a different use case.
- **Job to be done (`JTBD-*`).** The progress a banker wants, in the shape "when X, help me Y, so that Z, without W". It explains why the business use case is done and stays true if the product disappears. Five are `Confirmed`, each by one participant, so consumers treat them as evidence-backed, single participant.
- **Actor (`ACTOR-*`).** A cohort with accepted responsibility for part of a job family: who judges, who contributes, what authority they hold, what they need to see. Two exist today. The only permitted source for personas.
- **Scenario (`SC-*`).** The same business use case under different conditions: a short window, high impact with low confidence, deliberate non-action. What varies and what stays invariant are named. Not a screen, not a flow, not a persona applying a job.

### Product artefacts (owned by IBIQ)

- **Persona.** The product-facing expression of one `ACTOR-*` record: the cohort's responsibility, the judgments it keeps, the constraints it works under, and the product context it will meet IBIQ in. A persona cites its actor and inherits that actor's maturity. Goals and pain points come from the actor record and its evidence, not from the product team's assumptions. Any persona material under `intent-layer/reference/` is pre-intent and is not a source until traced to an actor.
- **Product capability.** What IBIQ can do functionally or technically: search, routing, extraction, document generation, approvals, reporting. A capability is justified by the product use cases it enables. It never cites a JTBD directly, because a confirmed job says what progress is sought and nothing about which capability serves it.
- **Product use case.** The ordered steps a persona takes inside IBIQ to complete part of a business use case, using one or more capabilities. It cites the `BUC-*` it serves, names which of the six steps it changes in the use case's own words, names one `SC-*` it covers and one it deliberately does not, and names the judgments it leaves with the human. If completing it would change the value delivered of the business use case, it is serving a different use case and must say so.
- **Alignment statement.** The written answers to the charter's nine litmus tests, each pointing at a record by ID and revision. Produced at initiation, before build, and whenever a cited record is superseded. Tests one to three are the gate; four to nine attach conditions.

## 5. What each product artefact must cite

| Product artefact | Must cite | May not |
| --- | --- | --- |
| Persona | Exactly one `ACTOR-*`, with revision | Invent goals or pain points not in the actor's evidence; borrow a reference persona without tracing it |
| Product use case | One `BUC-*` and the steps it changes; one `SC-*` covered and one excluded; the `JTBD-*` behind the use case; the human judgments it preserves | Change the value delivered; cite a `Hypothesis` record as its only justification |
| Product capability | The product use cases it enables | Cite a `JTBD-*` or `BO-*` directly |
| Alignment statement | At least one `BO-*` with the measure it moves; every record above, at `Evidence-backed` or above; the guardrails it could worsen; how it supports deliberate non-action; the gaps it needs filled | Cite by title text; cite a `Superseded` record |

## 6. Worked example

An IBIQ product use case for intelligence triage would read, in the record it cites:

| Field | Value |
| --- | --- |
| Serves | `BUC-GIB-INTEL-01` revision `1.0`, steps 1 to 3 (reduce noise; identify affected clients and context; explain consequence and evidence) |
| Job behind it | `JTBD-GIB-INTEL-01`, confirmed by one participant, treated as evidence-backed |
| Scenario covered | `SC-GIB-INTEL-01-A`, short-window consequential signal |
| Scenario excluded | `SC-GIB-INTEL-01-C`, deliberate non-action; the product must not manufacture activity here |
| Persona | Expression of `ACTOR-COV-SENIOR-MD` revision `2.0` |
| Judgments left with the human | Does it matter in context; is it credible enough for the contemplated use; respond or not; which client outcome |
| Outcome and measure | `BO-GIB-INTEL-01`, consequential surprises, downward; guardrail: senior time on noise must not rise |
| Capabilities used | Signal deduplication, client-context assembly, evidence provenance display |

A product use case that cannot fill this table is not yet aligned. One that fills it with `Hypothesis` records only is a discovery exercise and must say so.

## 7. What not to do

- Do not keep both lists. One definition per term, and the intent layer's definition wins for the six shared records.
- Do not call a product step sequence a use case. It is a product use case; the business use case is the record it serves.
- Do not derive a persona from a product idea or from the untested user profiles. Start from an actor record; raise a review trigger if the actor record is missing something.
- Do not promote an outcome measure that rewards activity. Productivity, time-to-outreach and volume measures are rejected throughout the catalogue; the primary measures are consequence, quality and deliberate non-action.
- Do not treat a `Confirmed` label as validation by the cohort until two participants have accepted the statement. Read the participant count.

## 8. Adoption steps for IBIQ

1. Replace the seven definitions on the IBIQ page with sections 4 and 5 of this guide.
2. Re-tag existing IBIQ scenarios: those that vary conditions map to an `SC-*`; those that describe product steps become product use cases.
3. Trace every existing IBIQ persona to an `ACTOR-*` or mark it superseded.
4. Write the alignment statement for the first product increment and run the nine tests with the intent model owner.
5. Report gaps back as review triggers: a cohort, job family or scenario IBIQ needs that the layer does not contain.

## Revision history

| Revision | Date | Change | Accepted by |
| --- | --- | --- | --- |
| `1.0` draft | 2026-10-07 | First consumer guide. Reconciles the IBIQ Product Definition Approach with the charter: two layers, renamed product use case, persona traced to actor, alignment statement. | `[validate]` |

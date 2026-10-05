# IB Intent Layer Charter

Status: Draft 1.0, 2026-10-05. Owner: `[validate: name the intent model owner]`. Review: on every promotion of a new JTBD, and at least quarterly.

## 1. Purpose

The Intent Layer is the single source of truth for what drives Investment Banking (IB) and Global Corporate Banking (GCB) decision making, expressed as business outcomes, business processes, jobs to be done, scenarios and the actor cohorts responsible for them.

It exists so that any value-add initiative supporting IB or GCB can be tested against the business's own stated intent before and during build. It is the litmus test. A project that cannot trace itself to records in this layer has not yet shown that it adds value.

Over time the layer grows into the full view of how IB and GCB operate and think: every standing job, every meaningful scenario, every responsible cohort, with evidence behind each.

## 2. What lives here and what does not

| Lives here | Does not live here |
| --- | --- |
| Business outcomes, job families, business use cases, JTBDs, scenarios, actor archetypes and personas derived from them | Products, projects, roadmaps, features, capability registers, solution flows, screens, prototypes |
| The evidence behind each record: interview records, confirmed-intent syntheses, observed episodes, operating data | Raw transcripts with participant identity, personal data, client-identifying material |
| Templates and the generation guide that define how records are written and promoted | Prompts, agents or tooling that consume the layer, except where a template needs them |
| Interview instruments, kept separate by round and purpose | Project-specific research that does not produce a reusable intent record |

Products and projects consume this layer. They never define it. A product concept is not evidence of a user need, and a capability that already references a record never justifies keeping that record's maturity higher than its evidence supports.

## 3. Scope today

| Cohort | Lenses catalogued | Evidence basis | Maturity ceiling |
| --- | --- | --- | --- |
| Senior Coverage MD (IB) | Intelligence triage, client relationship management, opportunity pipeline stewardship, consequential client meetings, umbrella intent | One participant, Q01 to Q151, structured discovery with statement confirmation | JTBDs confirmed by one participant; all supporting records evidence-backed or hypothesis |
| Actions and commitments (IB) | Working JTBD hypothesis only | Q118 to Q122 | Evidence-backed, uncatalogued |
| Capacity (IB) | Deferred | Q128 to Q130 | No record |
| ECM, DCM, M&A, Sponsors (IB) | None | Untested user profiles only; Round 2 Capital Markets proxy guide not yet run | Hypothesis |
| GCB | None | One unfilled template | None |

Silence in this table means no coverage, not implied coverage. A workspace working for a cohort or lens that is absent here must say so in its alignment statement and must not borrow Coverage records as a proxy without marking the borrowing.

## 4. How a workspace uses the layer

SDD workspaces, agents and people may use the layer to ask what the business is trying to achieve, to generate personas from actor records, to understand business processes through use cases and scenarios, and to show that their work adds value.

Consumption rules:

1. **Cite by stable ID and revision.** Reference `BO-*`, `JF-*`, `BUC-*`, `JTBD-*`, `ACTOR-*` and `SC-*` IDs, with the revision relied upon. Never cite by title text.
2. **Build only on sufficient maturity.** Build and execution decisions may rest on records at `Confirmed` or `Evidence-backed`. A `Hypothesis` record may inform discovery and research but may not be the sole justification for a build. A `Superseded` record may not be cited for new work.
3. **Read the maturity, not just the label.** A `Confirmed` record carries the participant count in its evidence field. Until a statement has been accepted by two or more participants, consumers should treat it as evidence-backed, single participant, whatever the label says.
4. **Generate personas only from `ACTOR-*` records.** The untested user profiles and banker archetypes in this folder predate the intent work, carry solution assumptions, and are not a generation source until traced to actor records or marked superseded.
5. **Do not infer capability support from a JTBD.** A confirmed job says what progress is sought. It says nothing about which capability serves it. Capability mappings need their own evidence pass.
6. **Report back.** When a workspace finds evidence that contradicts, extends or breaks a record, it raises a review trigger on that record rather than editing it locally or working around it. The generation guide's re-review procedure applies.

## 5. The litmus test

A value-add initiative is aligned with IB or GCB intent when it can state all of the following, in writing, and the statements survive a check against the records cited.

| # | Test | Pass condition |
| --- | --- | --- |
| 1 | Outcome | Names at least one `BO-*` it intends to move, and says which measure in that outcome's measurement contract it expects to change and in which direction. |
| 2 | Job | Names at least one `JTBD-*` it serves and quotes the desired progress and the unwanted trade-off it will respect. |
| 3 | Process | Names the `BUC-*` and the specific steps it changes, and states the value delivered of that use case in the use case's own words. |
| 4 | Scenario | Names at least one `SC-*` it covers and at least one it deliberately does not. |
| 5 | Actor | Names the `ACTOR-*` cohorts it affects and which of their judgments it leaves with the human. |
| 6 | Maturity | Every record cited is at `Evidence-backed` or above, or the initiative is explicitly a discovery exercise. |
| 7 | Guardrails | States which guardrail measures in the cited `BO-*` it could worsen and how it will watch them. |
| 8 | Non-action | Where the cited job accepts deliberate non-action as a valid result, says how the initiative supports that result rather than manufacturing activity. |
| 9 | Gaps | Lists any cohort, lens or scenario it needs that the layer does not yet contain, and whether it will contribute the missing evidence. |

An initiative that fails tests 1 to 3 is not aligned. One that fails 4 to 9 is aligned with conditions, and the conditions are recorded against it. The test is run at initiation, before build, and whenever a cited record is superseded.

## 6. Admission of new records

The generation guide governs maturity, promotion, review and supersession. This charter adds the entry rule.

A new `JTBD-*`, `BUC-*` or `SC-*` enters the layer only when:

1. **It has an evidence record.** At least one interview, observation or operating-data source is filed under `evidence/` with participant role, context, date and method, and without participant identity or client-identifying detail.
2. **It has at least one concrete episode or an explicit gap marker.** Desired-progress statements alone admit a record at `Hypothesis`. An observed episode is required for `Evidence-backed` process and scenario records.
3. **It passes the generation quality gate** in the artifact generation guide, including the solution-language guardrail and the cross-artifact integrity rules.
4. **It has an owner** who can accept, reopen or supersede it, and a next-review condition.
5. **It is written in the business's language.** Run the BUC writing prompt's readability and house-terms checks before promotion. A record a banker could not read aloud is not ready.
6. **Confirmation needs two.** A record moves to `Confirmed` only when accepted by at least two participants from the responsible cohort, at least one of whom did not take part in drafting the statement.

Interview instruments are admitted separately. Each instrument states its purpose (discovery, validation or direction setting), its audience, its status (draft, live, retired) and the records it is designed to test or produce. Instruments are never mixed across rounds, and a retired instrument is kept as a research record, not reused.

## 7. Growth path

In rough order:

1. Collect concrete episodes for the four existing Coverage lenses and convert `[validate]` process fields into evidence.
2. Validate the existing Coverage model with a second and third participant; apply the two-participant confirmation rule.
3. Catalogue or retire the actions and commitments lens.
4. Reconcile the persona material into `ACTOR-*` records.
5. Run Round 2 and extend to ECM and DCM with their own lenses where Q148's expected variation holds.
6. Open GCB with its own discovery round. Do not transplant Coverage records.
7. Put ranges on every business outcome.

## 8. Governance summary

| Field | Value |
| --- | --- |
| Owner | `[validate]` |
| Accepts new records | Owner, after the admission rule is met |
| Resolves disputes over a record | Owner, with the responsible cohort's representative |
| Runs the litmus test | The initiative, countersigned by the owner or delegate |
| Review cadence | Quarterly, and on every promotion, supersession or failed litmus test |
| Change control | This charter follows the same revision, supersession and append-only history rules as every record in the layer |

## Revision history

| Revision | Date | Change | Accepted by |
| --- | --- | --- | --- |
| `1.0` draft | 2026-10-05 | First charter. Codifies purpose, scope, consumption contract, litmus test, admission rule and growth path. | `[validate]` |

# Intent Artifact Generation Guide

Use this guide to generate a coherent, evidence-backed intent model before defining product capabilities or solution flows.

## Model

```text
Research evidence
      |
      v
Business outcome target
      |
      v
Job family / business process
      |
      v
Business use case ---------------- Value delivered
      |                                   |
      +------ Collective JTBD(s) ----------+
      |             |
      |             +------ Responsible actor archetypes / personas
      |
      +------ Scenario(s)

Intent model complete
      |
      v
Product capability mapping
      |
      v
Solution flow and implementation design
```

The diagram shows the primary catalogue structure, not strict ownership or one-to-one relationships. A business use case may serve several JTBDs, and one JTBD may apply across several business use cases.

## Artifact Set

| Artifact | Purpose | Template |
| --- | --- | --- |
| **Business outcome** | Define the measurable organizational result to improve. | [Business Outcome Template](business_outcome_template.md) |
| **Job family** | Organize related business use cases and JTBDs within a stable business-process area. | [Job Family Template](job_family_template.md) |
| **Business use case** | Describe a bounded business process that produces one recognizable value outcome. | [Business Use Case Template](business_use_case_template.md) |
| **JTBD** | Express the enduring progress sought by the responsible individual or collective. | [JTBD Template](jtbd_template.md) |
| **Actor archetype / persona** | Represent an evidence-based cohort responsible for all or part of the work. | [Actor Archetype Template](actor_archetype_template.md) |
| **Scenario** | Describe a meaningful contextual variation of a business use case. | [Scenario Template](scenario_template.md) |

Product capabilities and solution flows are downstream artifacts. Do not use them to define the intent model.

## Core Terms

| Term | Meaning |
| --- | --- |
| **Business outcome target** | A measurable organizational result, with a baseline, target, scope, and timeframe where evidence exists. |
| **Value delivered** | The useful business state, decision, commitment, or output produced by one completion of a business use case. The underlying modeling term is **unit of value**. |
| **Desired outcome** | The broader client, franchise, risk, or operating consequence sought through a JTBD. |
| **Value proposition** | A claim about why a product or solution is valuable. It belongs downstream and is not an intent artifact. |

Keep these distinct:

```text
Business outcome target  = measurable organizational change
Value delivered          = result of one completed business use case
JTBD desired outcome     = consequence the responsible actors seek
Value proposition        = promise made by a product or solution
```

## Generation Order

The work is iterative, but use this order to avoid deriving intent from a proposed solution.

1. **Assemble evidence.** Gather interviews, observed processes, operating data, existing artifacts, quotations, and known constraints. Separate evidence from interpretation.
2. **Define the business outcome.** State the organizational result before deciding how work or technology should change.
3. **Establish the job family.** Place the work in a stable business-process area and define its boundaries.
4. **Bound the business use case.** Identify the business trigger, completion condition, accountable collective, banker process, and value delivered.
5. **Derive the JTBD.** Ask why the responsible actors undertake the use case and what enduring progress, judgment, and consequence they seek.
6. **Derive actor archetypes.** Cluster evidence about responsibility, authority, behavior, information needs, and constraints. Do not invent a persona first and assign work to it later.
7. **Identify scenarios.** Capture meaningful variations that preserve the same core value delivered but alter context, stakes, participants, evidence, or path.
8. **Validate the model.** Check boundaries, traceability, evidence maturity, ownership, and language with participants or subject-matter experts.
9. **Map capabilities separately.** Only after intent is stable, identify reusable product abilities and solution flows that may support it.

## Evidence Rules

- Cite sources for every substantive claim.
- Mark unsupported or inferred claims `[validate]`.
- Preserve contradictory evidence rather than silently averaging it.
- Distinguish observed current behavior from desired future behavior.
- Do not treat a proposed product concept as proof of a user need.
- Use verbatim quotations only when the wording materially strengthens the evidence.
- Record the participant role and context without exposing unnecessary personal data.

## Evidence Maturity

| Status | Meaning |
| --- | --- |
| **Hypothesis** | Plausible interpretation with insufficient direct evidence. |
| **Evidence-backed** | Supported by one or more credible sources but not yet accepted as the standing model. |
| **Confirmed** | Explicitly validated by the accountable participant group or approved evidence owner. |
| **Superseded** | Replaced by a later conclusion; retained for traceability. |

Evidence maturity is not delivery status. Do not use `Prototype`, `Candidate`, `Later`, or `Vision` to describe research confidence.

Evidence maturity is reversible. New contradictory evidence may move a record from `Confirmed` back to `Evidence-backed` or `Hypothesis`; replacement by a materially different conclusion moves it to `Superseded`. Never preserve a higher maturity merely because downstream capabilities or designs already reference the record.

## Promotion, Review, And Supersession

Promotion means an artifact is the **current canonical interpretation of the evidence available at its evidence cutoff**. It does not make the artifact immutable or permanently correct.

Every promoted artifact must record:

| Governance field | Required content |
| --- | --- |
| **Revision** | Monotonic record revision, beginning at `1.0`. |
| **Evidence cutoff** | Latest date through which source evidence was considered. |
| **Review state** | `Current`, `Review required`, or `In review`. This is governance state, not delivery status or evidence maturity. |
| **Last reviewed** | Date of the latest explicit evidence and boundary review. |
| **Review owner** | Accountable role or evidence owner who can accept, reopen, or supersede the record. |
| **Next review** | Date, cadence, or event-based condition that will prompt reconsideration. |
| **Review triggers** | Record-specific changes that require re-review. |
| **Supersession links** | Prior or replacement stable IDs and revisions, or `None`. |
| **Change rationale** | Concise reason for the current revision and the evidence delta behind it. |

### Review Triggers

Mark a record `Review required` when any of the following could materially change its meaning, boundary, ownership, maturity, or success evidence:

- new interview, observation, operating data, or validation contradicts or materially extends the standing conclusion;
- the accountable actor, decision authority, handoff, process boundary, or value delivered changes;
- a business outcome baseline, target, guardrail, or measurement definition changes;
- a regulation, control, information-sharing rule, regional constraint, or client obligation changes;
- success signals repeatedly fail to reflect observed value or reveal an unintended consequence;
- a related artifact is revised in a way that may create an orphan, overlap, or broken boundary;
- cross-LOB evidence shows that one record should split, merge, narrow, broaden, or move scope;
- the scheduled review date or event-based review condition is reached.

### Re-Review Procedure

1. **Register the evidence delta.** Add the new source without deleting prior supporting or contradictory evidence.
2. **Flag the standing record.** Set review state to `Review required`; retain the current revision for consumers until a replacement decision is accepted.
3. **Assess impact.** Trace inbound and outbound stable-ID references, including business outcomes, use cases, JTBDs, actors, scenarios, capabilities, requirements, and solution flows.
4. **Re-evaluate the model.** Recheck boundaries, ownership, value delivered, job wording, maturity, success signals, and unresolved contradictions against the new evidence.
5. **Record one disposition:**
      - **No semantic change:** retain the revision and append the review decision.
      - **Revise in place:** preserve the stable ID and increment the revision when the enduring record remains the same.
      - **Split, merge, or replace:** create new stable ID(s), mark the prior record `Superseded`, and preserve explicit supersession links.
      - **Withdraw support:** lower evidence maturity and mark unsupported claims `[validate]` without waiting for a replacement.
6. **Repair traceability.** Update affected references and explicitly document any downstream capability or design assumptions that no longer hold.
7. **Revalidate and close.** Run the generation quality gate, set the accepted record to `Current`, update the evidence cutoff and review metadata, and append the decision to revision history.

### Stable ID And Revision Rules

- Keep the same stable ID when evidence refines wording, maturity, measures, scenarios, or boundaries but the enduring intent or value delivered remains recognizably the same.
- Increment the minor revision for non-semantic evidence, metadata, or wording changes; increment the major revision for a material reinterpretation that retains the same enduring identity.
- Create a new stable ID when the value delivered, accountable collective, core job, or business-process boundary changes enough to represent different work.
- Never repurpose a superseded stable ID for a new meaning, delete contradictory history, or silently rewrite evidence to make the current conclusion appear inevitable.
- Where supported, downstream references should include both the stable ID and the relied-upon revision. A stable-ID-only reference always resolves to the current accepted revision.

### Revision History

Every promoted artifact must maintain an append-only history:

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, maturity changed, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Stable IDs

Use stable, human-readable IDs and do not renumber records after other artifacts reference them.

| Artifact | Pattern | Example |
| --- | --- | --- |
| Business outcome | `BO-[LOB]-[NN]` | `BO-MA-01` |
| Job family | `JF-[LOB]-[NN]` | `JF-MA-02` |
| Business use case | `BUC-[LOB]-[NN]` | `BUC-MA-01` |
| JTBD | `JTBD-[LOB]-[NN]` | `JTBD-MA-01` |
| Actor archetype | `ACTOR-[LOB]-[ROLE]` | `ACTOR-MA-ASSOCIATE` |
| Scenario | `SC-[LOB]-[BUC]-[LETTER]` | `SC-MA-01-A` |

Use the most stable scope available for `[LOB]`. If a record is genuinely cross-LOB, use `GIB` rather than duplicating it.

## Cross-Artifact Integrity Rules

- Every business use case links to at least one business outcome, one job family, and one JTBD.
- Every JTBD links to at least one responsible actor cohort and one business use case.
- Every scenario links to exactly one primary business use case and preserves its core value delivered.
- Every actor archetype identifies its contribution to specific JTBDs and business use cases.
- Every success signal measures business value, behavior, quality, timing, or risk rather than feature adoption alone.
- Every relationship uses stable IDs, not matching by title text.
- A changed value outcome normally creates a new business use case, not merely a new scenario.

## Solution-Language Guardrail

Intent artifacts may describe enduring business evidence and controls, but must not prescribe:

- products, platforms, screens, tabs, views, or navigation;
- clicks, filters, forms, exports, notifications, or interface controls;
- named technical services, data feeds, models, or system architecture;
- delivery phases, feature status, or implementation choices.

Move that material into a capability map, requirements artifact, solution flow, or design document.

## Generation Quality Gate

Before accepting a set of artifacts, confirm:

- [ ] The business outcome is measurable or explicitly marked `[validate]`.
- [ ] The job-family boundary is stable and does not merely repeat an org chart or product name.
- [ ] Each business use case has one recognizable value delivered.
- [ ] Each JTBD states enduring progress and desired outcome, not a task list.
- [ ] Collective ownership and individual role contributions are both represented accurately.
- [ ] Personas are derived from evidence-based actor cohorts rather than invented biographies.
- [ ] Scenarios are contextual variations, not product interaction flows.
- [ ] All substantive claims have evidence or a validation marker.
- [ ] Cross-references use stable IDs and have no orphans.
- [ ] Promoted records include revision, evidence cutoff, review ownership, review triggers, and revision history.
- [ ] New or contradictory evidence has been preserved and its disposition is explicit.
- [ ] Superseded records remain traceable and downstream impacts have been reviewed.
- [ ] Product capability and solution language is absent from the intent layer.

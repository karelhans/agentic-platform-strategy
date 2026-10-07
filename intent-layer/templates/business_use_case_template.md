# Business Use Case Template

Use this template to describe one bounded, implementation-independent business process through which a person or team produces a recognizable value outcome.

> A business use case begins with a meaningful business trigger and ends when its value has been delivered, explicitly paused, or failed. It describes banker tasks, activities, evidence, judgments, collaboration, and resulting state, not product interactions.

Follow the [Intent Artifact Generation Guide](artifact_generation_guide.md) for generation order, evidence rules, stable IDs, and cross-artifact validation.

## Place In The Intent Model

```text
Business outcome
└── Job family / business process
    └── Business use case
        ├── Value delivered
        ├── JTBD(s)
        │   └── Responsible actor archetype(s) / personas
        └── Scenario(s)
```

Product capabilities may support several business use cases, but that mapping belongs in a separate capability or requirements artifact. Screens, views, clicks, and system behavior belong in a downstream solution flow.

Use the [Business Outcome Template](business_outcome_template.md), [Job Family Template](job_family_template.md), [JTBD Template](jtbd_template.md), [Actor Archetype Template](actor_archetype_template.md), and [Scenario Template](scenario_template.md) for linked records.

## Definitions

| Artifact | Definition | Key question |
| --- | --- | --- |
| **Business outcome** | A measurable organizational result the work is intended to improve. | What business result should change? |
| **Job family** | A grouping of related business use cases and JTBDs serving a broader business process or objective. | Which area of work does this belong to? |
| **Business use case** | A bounded process that produces one recognizable value outcome. | What valuable work is completed? |
| **Value delivered** | The useful business state, decision, commitment, or output produced by one completion of the use case. This is the use case's **unit of value** in the underlying model. | What becomes usable or materially different? |
| **JTBD** | The enduring progress sought by the responsible person or collective. | Why is this work undertaken? |
| **Responsible actor archetype** | An evidence-based cohort that performs or contributes to the work; a persona may represent this cohort for design. | Who contributes, judges, or is accountable? |
| **Scenario** | A specific context or meaningful variation in which the business use case occurs. | Under what circumstances does the process vary? |
| **Product capability** | A reusable functional or technical ability that may support one or more business use cases. | What could support the work? |
| **Solution flow** | Product-specific interactions using capabilities, interfaces, and channels. | How does a particular solution enable it? |

## Boundary Test

A valid business use case has:

- a meaningful trigger rather than an interface entry point;
- a clear starting state and completion condition;
- one recognizable value outcome;
- an accountable team or role;
- ordered business tasks and activities;
- explicit evidence, judgments, decisions, and handoffs;
- meaningful scenarios, exceptions, and failure consequences;
- no dependency on a named product, screen, view, feature, or channel.

If the description begins with “open,” “click,” “select a tab,” or “export from,” it is probably a solution flow rather than a business use case.

## Record Template

### BUC-[ID] — [Verb + Value Delivered]

#### Classification

| Field | What to capture |
| --- | --- |
| **Business outcome target(s)** | Measurable organizational result this use case contributes to, including baseline, target, and timeframe where evidenced. |
| **Job family** | Broader business process or objective containing the use case. |
| **Value delivered** | Recognizable business state, decision, commitment, or output produced by one completion of the use case. |
| **Collective JTBD(s)** | Stable JTBD IDs and statements explaining why the work is undertaken. |
| **Accountable team or role** | Collective or individual accountable for completing the use case and accepting its value. |
| **Participating roles** | Other roles contributing work, evidence, judgment, approval, or control. |
| **Representative personas** | Links to evidence-based actor archetypes used as design job families. |
| **Evidence maturity** | `Hypothesis`, `Evidence-backed`, `Confirmed`, or `Superseded`. |

#### Process Boundary

| Field | What to capture |
| --- | --- |
| **Trigger** | Business event or decision that starts the work. |
| **Starting state** | What is known, unresolved, unavailable, or at risk when the process begins. |
| **Completion condition** | Observable condition proving that the intended value has been delivered. |
| **Resulting state** | What can happen, be decided, or be relied upon after completion. |
| **Out of scope** | Adjacent work deliberately excluded from this process boundary. |
| **Frequency and criticality** | How often the use case occurs and the consequence of delay or failure. |

#### Responsible Actor Archetypes

Personas represent cohorts responsible for parts of the collective work. Describe contribution and authority before adding personal characteristics.

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| `[Role or cohort]` | `[Work owned or contributed]` | `[Decision, approval, or escalation rights]` | `[Evidence needed and operating constraints]` | `[Persona ID or evidence gap]` |

#### Banker Process

Describe the business process, not use of a product.

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | `[What the banker or team does]` | `[Actor cohort]` | `[Business evidence]` | `[Interpretation or choice]` | `[Who contributes or receives it]` | `[What materially changes]` |

#### Scenarios

Scenarios are meaningful variations of the same business use case. They retain the same value delivered while changing the trigger, stakes, participants, evidence, or path.

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| `SC-[ID]` | `[Specific situation]` | `[Tasks, evidence, participants, urgency, or constraints]` | `[Core JTBD and value delivered]` |

#### Exceptions And Failure Paths

| Exception or failure | Detection | Decision or escalation | Resulting state |
| --- | --- | --- | --- |
| `[Material deviation]` | `[How it becomes known]` | `[Who decides what happens next]` | `[Paused, redirected, failed, or completed differently]` |

#### Outcomes And Evidence

| Field | What to capture |
| --- | --- |
| **Success signals** | Behavioral, quality, timing, risk, client, or commercial evidence that the intended value is being delivered better. |
| **Failure consequences** | Client, franchise, financial, timing, control, or operating impact when the process fails. |
| **Current process and pain** | How the work is performed today and where effort, delay, ambiguity, or risk occurs. Mark unsupported claims `[validate]`. |
| **Business rules and controls** | Enduring constraints governing the work, independent of a particular implementation. |
| **Evidence** | Research sources, quotations, observed process, operating data, or outcome data. |
| **Open questions** | Unresolved process, ownership, value, or evidence questions requiring validation. |

#### Record Governance

| Field | What to capture |
| --- | --- |
| **Revision** | Monotonic revision beginning at `1.0`. Preserve the stable `BUC-*` ID while the same bounded process and value delivered are being refined. |
| **Evidence cutoff** | Latest date through which process, ownership, boundary, value, and outcome evidence was considered. |
| **Review state** | `Current`, `Review required`, `In review`, `Candidate` (raised by a proposal, not admitted; revision below `1.0` allowed), or `Superseded`. |
| **Last reviewed** | Date of the latest explicit evidence, boundary, and value review. |
| **Review owner** | Accountable business or evidence owner who can accept, reopen, split, merge, or supersede the use case. |
| **Next review** | Date, cadence, or event that prompts reconsideration. |
| **Review triggers** | Material changes to trigger, accountable collective, completion condition, value delivered, process boundary, decision rights, controls, parent family, related JTBDs, or scenarios. |
| **Supersession links** | Prior, split, merged, or replacement stable IDs and revisions, or `None`. |
| **Change rationale** | Evidence delta and reason for the current revision or maturity decision. |

#### Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, split, merged, maturity changed, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Quality Check

- [ ] The use case produces one recognizable value outcome.
- [ ] Its boundary begins with a business trigger and ends with an observable completion condition.
- [ ] The accountable collective and participating roles are explicit.
- [ ] Personas represent actor cohorts rather than replacing collective ownership.
- [ ] The process communicates key banker tasks, activities, evidence, judgments, and handoffs.
- [ ] Scenarios describe meaningful variations, not separate product flows.
- [ ] Success measures concern business value, quality, time, behavior, or risk rather than feature adoption alone.
- [ ] Products, screens, views, features, clicks, data architecture, and implementation choices are absent.
- [ ] Claims are supported by evidence or marked `[validate]`.
- [ ] Promoted records include complete governance metadata and append-only revision history.
- [ ] Boundary, value, ownership, and supersession changes remain traceable across linked records.

---

## Worked Example

### BUC-MA-01 — Develop And Agree The Buyer Universe

#### Classification

| Field | Example |
| --- | --- |
| **Business outcome target(s)** | Reduce preparation time for a defensible first-draft buyer universe from three working days to one without reducing candidate quality `[validate]`. |
| **Job family** | M&A deal preparation and buyer outreach planning. |
| **Value delivered** | An approved, evidence-backed buyer universe with prioritization, rationale, sequencing, ownership, and next actions. |
| **Collective JTBD(s)** | `JTBD-MA-01` — Identify and prioritize credible buyers. |
| **Accountable team or role** | Sell-side deal team. |
| **Participating roles** | Investment Banking Associate, VP, senior deal-team banker, Coverage banker, and relevant product or sector specialists. |
| **Representative personas** | Associate, VP, and senior-banker archetypes derived from role, authority, experience, evidence needs, and operating constraints. |
| **Evidence maturity** | `Hypothesis`. |

#### Process Boundary

| Field | Example |
| --- | --- |
| **Trigger** | The team needs an indicative or executable buyer strategy for a sell-side opportunity. |
| **Starting state** | Transaction objectives are sufficiently understood, but no current buyer universe has been agreed. |
| **Completion condition** | The accountable senior banker accepts the buyer universe and its rationale for the relevant stage of the process. |
| **Resulting state** | The team can align with the client, plan outreach, assign relationship owners, or gather missing evidence. |
| **Out of scope** | Conducting buyer outreach, managing indications, or negotiating transaction terms. |
| **Frequency and criticality** | Occurs for sell-side pitches and mandates; omissions or weak rationale can damage client confidence and process outcomes. |

#### Responsible Actor Archetypes

| Actor cohort | Responsibility in this use case | Judgment or authority | Information and constraints | Persona reference |
| --- | --- | --- | --- | --- |
| Investment Banking Associate | Assemble the candidate universe and supporting evidence. | Identify evidence gaps and challenge unsupported inclusion. | Sector, transaction, financial, precedent, and relationship evidence under time pressure. | `PERSONA-MA-ASSOCIATE` `[validate]` |
| VP | Direct the analysis and test completeness and consistency. | Resolve routine inclusion questions and escalate strategic choices. | Must balance analytical depth with process timing and senior expectations. | `PERSONA-MA-VP` `[validate]` |
| Senior deal-team banker | Apply transaction, client, competitive, and relationship judgment. | Accept the universe, material exclusions, prioritization, and outreach direction. | Requires defensible rationale without reviewing every underlying research step. | `PERSONA-MA-SENIOR` `[validate]` |

#### Banker Process

| Step | Task or activity | Responsible role(s) | Evidence considered | Judgment or decision | Collaboration or handoff | Resulting state |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Establish transaction objectives and buyer-selection criteria. | Senior banker, VP, Associate | Client objectives, transaction perimeter, timing, constraints, and strategic hypotheses. | Determine what makes a buyer credible for this situation. | Senior direction is translated into working criteria. | Agreed assessment frame. |
| 2 | Assemble a broad candidate universe. | Associate | Sector participants, sponsors, precedents, acquisition history, financial capacity, and known interest. | Decide which candidates have enough initial relevance to assess. | Specialists contribute names and context. | Broad candidate universe. |
| 3 | Assess and compare candidates. | Associate, VP | Strategic fit, likely appetite, capacity, acquisition history, relationship access, conflicts, and execution considerations. | Distinguish credible candidates from weak or unsupported names. | Evidence gaps are routed to relevant contributors. | Evidence-backed candidate assessments. |
| 4 | Challenge gaps, exclusions, and assumptions. | VP, senior banker, specialists | Candidate comparisons, missing evidence, contradictory views, and non-obvious alternatives. | Add, remove, retain, or investigate candidates. | Material disagreements are escalated to the accountable senior banker. | Revised and defensible universe. |
| 5 | Prioritize candidates and document the rationale. | VP, Associate | Relative fit, likelihood, client acceptability, access, sequencing, and process risk. | Establish priority, watch, excluded, or unresolved status. | Rationale is prepared for senior and client discussion. | Prioritized universe with explicit reasoning. |
| 6 | Review and accept the buyer strategy. | Senior banker and deal team | Proposed universe, rationale, exclusions, uncertainties, and relationship ownership. | Accept the universe or request targeted revision. | Accepted direction is communicated to the team. | Approved buyer universe. |
| 7 | Assign ownership and next actions. | Senior banker, VP | Accepted priorities, evidence gaps, relationship coverage, and process timing. | Decide who will validate, approach, monitor, or prepare each priority. | Work passes into outreach planning or further diligence. | Actionable buyer strategy. |

#### Scenarios

| Scenario ID | Context or trigger | What varies | What remains invariant |
| --- | --- | --- | --- |
| `SC-MA-01A` | Preparing an indicative universe before a pitch. | Evidence is lighter, hypotheses are broader, and client constraints may be incomplete. | The universe must remain credible and explainable for its stage. |
| `SC-MA-01B` | Finalizing the initial universe after mandate. | Client objectives, confidentiality, exclusions, sequencing, and ownership require greater precision. | The deal team must agree a defensible buyer strategy. |
| `SC-MA-01C` | Revising the universe after client feedback or changed market conditions. | Existing assumptions, priorities, and exclusions are re-evaluated against new evidence. | Changes require explicit rationale and renewed acceptance. |

#### Outcomes And Evidence

| Field | Example |
| --- | --- |
| **Success signals** | Time to accepted universe; candidate rationale completeness; material additions or removals during senior or client review; avoidable rework; missed credible candidates identified later. |
| **Failure consequences** | Lost preparation time, weak client confidence, overlooked buyers, poorly sequenced outreach, or an unnecessarily narrow competitive process. |
| **Current process and pain** | Teams reconcile research, relationship knowledge, precedents, and senior input across fragmented sources under tight deadlines `[validate]`. |
| **Business rules and controls** | Client exclusions, confidentiality, conflicts, information barriers, and documented senior acceptance. |
| **Evidence** | Illustrative example based on the supplied taxonomy; replace with observed process and outcome evidence. |
| **Open questions** | Who formally accepts the universe at each stage? What evidence threshold changes between pitch and mandate? Which exclusions require recorded rationale? |

# Responsible Actor Archetype And Persona Template

Use this template to represent an evidence-based cohort responsible for all or part of a JTBD or business use case.

> The work exists independently of a persona. First identify collective responsibility and role contributions; then derive an archetype that makes the responsible cohort relatable and useful for research and design.

Follow the [Intent Artifact Generation Guide](artifact_generation_guide.md) for evidence rules, stable IDs, and cross-artifact validation.

## Archetype And Persona

- **Actor archetype** is the evidence-backed model of a cohort sharing meaningful responsibilities, authority, behavior, information needs, and constraints.
- **Persona** is a concise, human-readable expression of that archetype for communication and design.

Do not invent names, biographies, preferences, quotations, or demographic details to make the persona feel realistic. Include demographic characteristics only when evidence shows that they materially affect the work.

## Derivation Criteria

Derive an archetype from patterns across evidence such as:

- role, seniority, business, region, client, or product context;
- responsibility for collective JTBDs and business use cases;
- decision authority, approval rights, and escalation obligations;
- domain expertise and experience;
- evidence and information required to act;
- working patterns, pressures, constraints, and risk exposure;
- meaningful behavioral differences within otherwise similar roles.

Do not create a separate archetype for superficial preferences or differences that do not change responsibility, judgment, process contribution, or desired progress.

## Record Template

### ACTOR-[LOB]-[ROLE] - [Archetype Name]

#### Cohort Definition

| Field | What to capture |
| --- | --- |
| **Cohort definition** | Concise definition of the people represented and the work-relevant traits they share. |
| **Inclusion criteria** | Evidence-based criteria for belonging to this cohort. |
| **Exclusion criteria** | Similar roles or contexts not represented and why. |
| **Business context** | LOB, lifecycle, client, transaction, regional, or operating contexts that shape the work. |
| **Evidence base** | Interviews, observations, role frameworks, operating data, and sample coverage supporting the archetype. |
| **Evidence maturity** | `Hypothesis`, `Evidence-backed`, `Confirmed`, or `Superseded`. |

#### Responsibility And Contribution

| Field | What to capture |
| --- | --- |
| **Collective responsibility** | Team or group whose shared work this cohort contributes to. |
| **JTBD contributions** | Stable `JTBD-*` IDs and the cohort's specific contribution to each job. |
| **Business use case contributions** | Stable `BUC-*` IDs and the tasks or activities this cohort performs. |
| **Accountability** | Outcomes, decisions, or commitments for which this cohort is answerable. |
| **Decision authority** | Decisions the cohort can make, approve, reject, or escalate. |
| **Handoffs and dependencies** | Roles from which this cohort receives work or evidence and roles to which it passes results. |

#### Work-Relevant Characteristics

| Field | What to capture |
| --- | --- |
| **Goals and pressures** | Outcomes the cohort tries to advance and pressures shaping its behavior. |
| **Evidence and information needs** | Information required to perform tasks and exercise judgment. |
| **Expertise and mental models** | Domain knowledge and recurring reasoning patterns relevant to the work. |
| **Working patterns** | Recurring contexts, timing, collaboration modes, and time constraints. |
| **Pain points and failure exposure** | Friction, ambiguity, risk, or consequences experienced by the cohort. |
| **Control and sensitivity constraints** | Entitlements, confidentiality, conduct, or risk boundaries shaping the work. |
| **Meaningful internal variations** | Differences within the cohort that should influence scenarios or research cuts but do not justify a separate archetype. |

#### Persona Expression

Summarize the archetype in three evidence-backed statements:

1. **Responsible for:** `[Contribution to collective work]`
2. **Needs to judge:** `[Irreducible decisions or interpretation]`
3. **Constrained by:** `[Material pressures, evidence gaps, authority, or controls]`

Optional narrative:

> `[Role cohort]` is responsible for `[work contribution]`. They need `[evidence and authority]` to make `[judgments]`, while balancing `[constraints and consequences]`.

## Record Governance

| Field | What to capture |
| --- | --- |
| **Revision** | Monotonic revision beginning at `1.0`. Preserve the stable `ACTOR-*` ID while the same evidence-based cohort is being refined. |
| **Evidence cutoff** | Latest date through which cohort, responsibility, authority, behavior, and constraint evidence was considered. |
| **Review state** | `Current`, `Review required`, `In review`, `Candidate` (raised by a proposal, not admitted; revision below `1.0` allowed), or `Superseded`. |
| **Last reviewed** | Date of the latest explicit cohort and contribution review. |
| **Review owner** | Role or evidence owner who can accept, reopen, split, merge, or supersede the archetype. |
| **Next review** | Date, frequency, or event that prompts reconsideration. |
| **Review triggers** | Material changes to cohort criteria, responsibility, authority, handoffs, information needs, working patterns, controls, internal variations, or linked JTBD and use-case contributions. |
| **Supersession links** | Prior, split, merged, or replacement stable IDs and revisions, or `None`. |
| **Change rationale** | Evidence delta and reason for the current revision or maturity decision. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, split, merged, maturity changed, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Quality Check

- [ ] The archetype was derived from evidence rather than invented before research.
- [ ] Cohort criteria concern responsibility, authority, behavior, context, or constraints relevant to the work.
- [ ] Collective ownership remains explicit; the persona does not absorb the whole team process.
- [ ] JTBD and business-use-case contributions use stable IDs.
- [ ] Decision authority and handoffs are explicit.
- [ ] Goals and pain points are grounded in observed or reported work.
- [ ] Demographics appear only where they materially affect the work and are evidenced.
- [ ] No fictional biography, decorative quote, or unsupported preference is presented as fact.
- [ ] Evidence gaps are marked `[validate]`.
- [ ] Promoted records include complete governance metadata and append-only revision history.
- [ ] Cohort splits, merges, contradictions, and supersession impacts remain traceable.

## Worked Example

### ACTOR-MA-ASSOCIATE - Sell-Side M&A Associate

| Field | Example |
| --- | --- |
| **Cohort definition** | Associates supporting sell-side preparation and execution who assemble evidence, structure analysis, and prepare material for team judgment. |
| **Business context** | Time-sensitive sell-side pitch and mandate work involving senior review, client constraints, and multiple evidence sources. |
| **Collective responsibility** | Contributes to the sell-side deal team's responsibility for an effective and defensible transaction process. |
| **JTBD contributions** | `JTBD-MA-01` - Assemble and test the evidence needed to identify credible buyers. |
| **Business use case contributions** | `BUC-MA-01` - Build the broad universe, assess candidates, identify gaps, and document rationale. |
| **Accountability** | Analytical completeness, traceability, timely escalation of gaps, and quality of material prepared for review. |
| **Decision authority** | Can make routine analytical choices; escalates strategic inclusion, exclusion, client, conflict, and sequencing decisions. |
| **Evidence and information needs** | Transaction objectives, sector participants, sponsor and strategic appetite, financial capacity, precedents, relationships, conflicts, and client constraints. |
| **Goals and pressures** | Produce complete, defensible work quickly while anticipating senior questions and minimizing avoidable rework. |
| **Pain points and failure exposure** | Fragmented evidence, ambiguous criteria, late direction changes, duplicated research, and omission risk `[validate]`. |
| **Evidence maturity** | `Hypothesis`. |

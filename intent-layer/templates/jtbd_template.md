# Jobs to Be Done Template

Use this template to describe the enduring progress a person or team seeks in a particular situation. A JTBD explains **why the work matters**; it does not describe a product, interface, capability, or delivery plan.

> One job per record. The job should remain true if the current products and processes disappear, and it should still be recognizable in five years.

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

The hierarchy organizes the catalogue, but the relationships may be many-to-many: one business use case can serve several JTBDs, and one JTBD can apply across several business use cases.

See the [Business Use Case Template](business_use_case_template.md) for the bounded process, the [Actor Archetype Template](actor_archetype_template.md) for responsible cohorts, and the [Scenario Template](scenario_template.md) for contextual variations.

## Intent Criteria

A valid JTBD:

- describes desired progress, judgment, and outcomes rather than a product interaction;
- can be owned by an individual or collectively by a team;
- uses the language of the people responsible for the work;
- identifies the situation that makes the job relevant;
- distinguishes the desired outcome from the activity performed;
- states meaningful risks, constraints, or unwanted trade-offs;
- links claims to research evidence and marks assumptions for validation;
- excludes products, screens, views, features, channels, data feeds, and implementation choices;
- uses evidence maturity rather than roadmap or delivery status.

## Job Statement

Use the individual or collective form that reflects how the work is actually owned.

> **Individual:** When `[situation or trigger]`, help me `[desired progress and judgment]`, so `[client, franchise, or operating outcome]`, without `[unwanted trade-off]`.

> **Collective:** When `[situation or trigger]`, help us `[desired progress and judgment]`, so `[client, franchise, or operating outcome]`, without `[unwanted trade-off]`.

## Record Template

### JTBD-[ID] — [Short Verb-Led Job Name]

| Field | What to capture |
| --- | --- |
| **ID** | Stable identifier, such as `JTBD-MA-01`. Do not renumber it after other artifacts reference it. |
| **Parent business use case(s)** | Stable IDs for the bounded business processes in which this job is performed. |
| **Job owner** | Individual role or collective group responsible for making the progress. |
| **Responsible actor archetypes** | Evidence-based cohorts that perform or contribute to the job. Link persona profiles where available. |
| **Job statement** | Complete individual or collective statement using the structure above. |
| **Situation and triggers** | Circumstances that make the job relevant or urgent. |
| **Desired progress** | What must move forward, become clearer, or materially improve. |
| **Required judgment** | Decisions, interpretation, or authority that cannot be reduced to routine activity. |
| **Desired outcome** | Observable client, franchise, risk, or operating result. |
| **Unwanted trade-offs** | Burden, delay, risk, loss, or distortion that must be avoided. |
| **Current process, workaround, and pain** | How the work is accomplished today and what it costs. Mark unsupported claims `[validate]`. |
| **Related scenarios** | Stable IDs for meaningful contexts or variations in which the job arises. |
| **Success signals** | Behavioral or business evidence that the job is being served better. |
| **Evidence** | Research sources, quotations, observations, process evidence, or usage evidence. |
| **Evidence maturity** | `Hypothesis`, `Evidence-backed`, `Confirmed`, or `Superseded`. |

## Representative Actor Archetypes

A persona is a research-derived representation of a cohort responsible for all or part of the JTBD. It is a **design view over the work**, not the source or owner of the work itself.

Define an archetype using relevant criteria rather than invented biography:

- role and seniority;
- business, product, region, or client context;
- responsibilities and contribution to the collective job;
- decision authority and escalation rights;
- experience and domain expertise;
- information and evidence needs;
- working patterns and constraints;
- goals, pressures, and recurring pain points.

## Record Governance

| Field | What to capture |
| --- | --- |
| **Revision** | Monotonic revision beginning at `1.0`. Preserve the stable `JTBD-*` ID while the same enduring job is being refined. |
| **Evidence cutoff** | Latest date through which job, actor, use-case, and success evidence was considered. |
| **Review state** | `Current`, `Review required`, `In review`, `Candidate` (raised by a proposal, not admitted; revision below `1.0` allowed), or `Superseded`. |
| **Last reviewed** | Date of the latest explicit evidence, wording, and boundary review. |
| **Review owner** | Accountable participant group or approved evidence owner who can accept, reopen, or supersede the job. |
| **Next review** | Date, frequency, or event that prompts reconsideration. |
| **Review triggers** | Material changes to job ownership, situation, desired progress, required judgment, desired outcome, trade-offs, parent use cases, actor evidence, or success signals. |
| **Supersession links** | Prior, split, merged, or replacement stable IDs and revisions, or `None`. |
| **Change rationale** | Evidence delta and reason for the current wording, revision, or maturity decision. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, maturity changed, split, merged, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Quality Check

Before accepting a JTBD, confirm:

- [ ] It describes progress rather than a feature, task list, or interface.
- [ ] Its owner is the real accountable individual or collective, not a convenient fictional user.
- [ ] The statement contains a situation, desired progress, outcome, and material trade-off.
- [ ] Required human judgment or authority is explicit where relevant.
- [ ] Persona references represent responsible cohorts and do not redefine the job around one individual.
- [ ] Success signals measure improved outcomes or behavior, not feature adoption alone.
- [ ] Evidence is cited and unsupported claims are marked `[validate]`.
- [ ] The statement would remain valid if the current product and operating model changed.
- [ ] Promoted records include complete governance metadata and append-only revision history.
- [ ] Reopened, contradicted, or superseded job conclusions remain traceable.

## Worked Example

### JTBD-MA-01 — Identify And Prioritize Credible Buyers

| Field | Example |
| --- | --- |
| **Parent business use case(s)** | `BUC-MA-01` — Develop and agree the buyer universe. |
| **Job owner** | Sell-side deal team. |
| **Responsible actor archetypes** | Investment Banking Associate, VP, and senior deal-team banker, each with a distinct contribution and authority. |
| **Job statement** | When preparing a sell-side process, help us identify and prioritize credible potential buyers using transaction-specific evidence and judgment, so the deal team can agree a defensible outreach strategy without overlooking non-obvious counterparties or spending days reconciling fragmented research. |
| **Situation and triggers** | Preparing for a pitch, beginning a mandated process, or revising the buyer strategy after client or market feedback. |
| **Desired progress** | Move from an untested universe of names to an agreed and prioritized buyer thesis. |
| **Required judgment** | Judge strategic fit, likely appetite, financial capacity, relationship access, conflicts, and acceptable exclusions. |
| **Desired outcome** | A credible buyer strategy that the deal team can explain, defend, and act upon. |
| **Unwanted trade-offs** | Missing non-obvious buyers, presenting weak candidates, duplicating research, or creating false confidence from incomplete evidence. |
| **Current process, workaround, and pain** | Research and prior knowledge are reconciled across fragmented sources under time pressure `[validate]`. |
| **Related scenarios** | `SC-MA-01A` pre-pitch universe; `SC-MA-01B` post-mandate universe; `SC-MA-01C` revised universe. |
| **Success signals** | Time to an agreed universe; proportion of candidates with defensible rationale; material additions or removals during senior review; rework after client review. |
| **Evidence** | Illustrative example; replace with interview, process, and outcome evidence. |
| **Evidence maturity** | `Hypothesis`. |

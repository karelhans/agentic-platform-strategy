# Scenario Template

Use this template to describe a specific real-world context or meaningful variation in which a business use case occurs.

> A scenario changes the trigger, stakes, participants, evidence, constraints, or path while preserving the parent business use case's core value delivered.

Follow the [Intent Artifact Generation Guide](artifact_generation_guide.md) for evidence rules, stable IDs, and cross-artifact validation.

## Scenario Boundary Test

Create a scenario when:

- the same business use case occurs under meaningfully different conditions;
- the variation changes tasks, evidence, participants, urgency, controls, or decisions;
- the parent use case still produces the same recognizable value outcome.

Create a new business use case instead when the trigger, accountable collective, completion condition, or value delivered materially changes.

Do not create a scenario merely because a different screen, channel, device, or feature is used. That is a solution-flow variation.

## Record Template

### SC-[LOB]-[BUC]-[LETTER] - [Scenario Name]

#### Classification

| Field | What to capture |
| --- | --- |
| **Parent business use case** | Exactly one primary `BUC-*` ID. |
| **Related JTBDs** | Stable `JTBD-*` IDs active in this context. |
| **Value delivered** | The invariant value outcome inherited from the parent use case. |
| **Primary actor cohorts** | Stable `ACTOR-*` IDs participating in this variation. |
| **Evidence maturity** | `Hypothesis`, `Evidence-backed`, `Confirmed`, or `Superseded`. |

#### Context And Variation

| Field | What to capture |
| --- | --- |
| **Context** | Real-world situation in which this variation occurs. |
| **Trigger** | Specific event or condition that starts this scenario. |
| **Starting conditions** | What is known, unresolved, available, or constrained at the outset. |
| **Stakes and urgency** | Why the situation matters and how timing or consequences differ. |
| **What varies** | Tasks, evidence, participants, authority, controls, sequence, or quality threshold that differs from the parent use case. |
| **What remains invariant** | Core JTBD, accountable collective, completion condition, and value delivered. |
| **Additional business rules or controls** | Constraints that apply specifically in this scenario. |
| **Exit or transition** | How the scenario completes or moves into another scenario or business use case. |

#### Process Variation

Record only the meaningful differences from the parent business use case.

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| `[Step reference]` | `[Added, removed, reordered, or changed work]` | `[Contextual cause]` | `[Role or decision difference]` | `[Effect on evidence, timing, risk, or result]` |

#### Evidence And Validation

| Field | What to capture |
| --- | --- |
| **Success signals** | Evidence that this variation still delivers the parent use case's intended value. |
| **Failure risks** | Consequences or breakdowns especially relevant in this context. |
| **Evidence** | Interviews, observed episodes, process artifacts, or operating data supporting the scenario. |
| **Open questions** | Unresolved differences requiring validation. |

#### Record Governance

| Field | What to capture |
| --- | --- |
| **Revision** | Monotonic revision beginning at `1.0`. Preserve the stable `SC-*` ID while the same contextual variation is being refined. |
| **Evidence cutoff** | Latest date through which context, variation, control, and process evidence was considered. |
| **Review state** | `Current`, `Review required`, `In review`, `Candidate` (raised by a proposal, not admitted; revision below `1.0` allowed), or `Superseded`. |
| **Last reviewed** | Date of the latest explicit evidence and variation review. |
| **Review owner** | Business or evidence owner who can accept, reopen, reclassify, or supersede the scenario. |
| **Next review** | Date, cadence, or event that prompts reconsideration. |
| **Review triggers** | Material changes to trigger, stakes, actors, authority, controls, path, parent use case, invariant value delivered, or evidence that the variation is actually a separate use case. |
| **Supersession links** | Prior or replacement scenario or business-use-case IDs and revisions, or `None`. |
| **Change rationale** | Evidence delta and reason for the current revision, reclassification, or maturity decision. |

#### Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, reclassified, maturity changed, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Quality Check

- [ ] The scenario links to exactly one primary business use case.
- [ ] The parent value delivered remains invariant.
- [ ] The variation materially affects business context or process, not only a product interaction.
- [ ] Changed tasks, evidence, participants, decisions, or controls are explicit.
- [ ] Actor archetypes and JTBDs use stable IDs.
- [ ] The scenario does not duplicate the complete parent process unnecessarily.
- [ ] Evidence supports the variation or it is marked `[validate]`.
- [ ] Promoted records include complete governance metadata and append-only revision history.
- [ ] Reclassification or supersession preserves the prior scenario and downstream traceability.

## Worked Example

### SC-MA-01-A - Indicative Buyer Universe Before A Pitch

| Field | Example |
| --- | --- |
| **Parent business use case** | `BUC-MA-01` - Develop and agree the buyer universe. |
| **Related JTBDs** | `JTBD-MA-01` - Identify and prioritize credible buyers. |
| **Value delivered** | An accepted, evidence-backed buyer universe appropriate to the current stage, with prioritization and rationale. |
| **Primary actor cohorts** | `ACTOR-MA-ASSOCIATE`, M&A VP archetype, and senior deal-team banker archetype `[validate IDs]`. |
| **Context** | The team is preparing an indicative buyer thesis before it has a mandate or complete client constraints. |
| **Trigger** | A pitch or early client discussion requires a credible view of potential buyers. |
| **Starting conditions** | Public and institutional evidence is available, but client exclusions, transaction perimeter, and process choices may be incomplete. |
| **Stakes and urgency** | The universe must demonstrate judgment and preparedness without presenting hypothesis as settled fact. |
| **What varies** | Evidence threshold is lighter; uncertainty and assumptions are more prominent; outreach sequencing and ownership may remain provisional. |
| **What remains invariant** | The team must identify, prioritize, explain, and accept a credible buyer universe for the stage. |
| **Additional business rules or controls** | Clearly distinguish hypotheses from known client direction and avoid implying authorization for outreach. |
| **Exit or transition** | The indicative universe is accepted for pitch use or transitions to post-mandate refinement. |
| **Evidence maturity** | `Hypothesis`. |

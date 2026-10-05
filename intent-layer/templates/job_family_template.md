# Job Family Template

Use this template to define a stable grouping of related business use cases and JTBDs within a broader business process or objective.

> A job family organizes the intent catalogue. It is not a job title, organizational team, product module, or single workflow.

Follow the [Intent Artifact Generation Guide](artifact_generation_guide.md) for evidence rules, stable IDs, and cross-artifact validation.

## Family Criteria

A valid job family:

- represents a coherent area of business work with a recognizable purpose;
- groups use cases that share business context, outcomes, evidence, or lifecycle position;
- is stable across product redesigns and most organizational changes;
- has clear inclusion and exclusion boundaries;
- is broad enough to contain several related use cases but narrow enough to be analytically useful;
- avoids product names, navigation labels, and temporary program terminology.

## Record Template

### JF-[LOB]-[NN] - [Job Family Name]

| Field | What to capture |
| --- | --- |
| **Definition** | One-sentence description of the coherent area of business work. |
| **Business purpose** | Client, franchise, risk, or operating purpose served by the family. |
| **Lifecycle position** | Where this work sits in the relevant business lifecycle; use `cross-lifecycle` where appropriate. |
| **Scope boundary** | Where the family starts and ends conceptually. |
| **Included work** | Types of business use cases and JTBDs that belong here. |
| **Excluded work** | Adjacent work that should be classified elsewhere. |
| **Primary business outcomes** | Stable `BO-*` IDs to which the family contributes. |
| **Business use cases** | Stable `BUC-*` IDs grouped by the family. |
| **JTBDs** | Stable `JTBD-*` IDs associated with the family. |
| **Responsible actor cohorts** | Primary collective and individual cohorts involved across the family. |
| **Adjacent job families** | Related `JF-*` IDs and the boundary or handoff between them. |
| **Common business rules and controls** | Enduring constraints shared by most records in the family. |
| **Known variations** | LOB, region, client, product, seniority, or lifecycle differences that do not justify a separate family. |
| **Evidence** | Frameworks, observed processes, interviews, and operating evidence supporting the grouping. |
| **Evidence maturity** | `Hypothesis`, `Evidence-backed`, `Confirmed`, or `Superseded`. |

## Catalogue Membership

| Record ID | Record name | Why it belongs | Boundary note |
| --- | --- | --- | --- |
| `[BUC-* or JTBD-*]` | `[Name]` | `[Shared purpose, context, or outcome]` | `[How it differs from adjacent work]` |

## Record Governance

| Field | What to capture |
| --- | --- |
| **Revision** | Monotonic revision beginning at `1.0`. Preserve the stable `JF-*` ID while the same business-process area is being refined. |
| **Evidence cutoff** | Latest date through which boundary, membership, lifecycle, and variation evidence was considered. |
| **Review state** | `Current`, `Review required`, or `In review`. |
| **Last reviewed** | Date of the latest explicit evidence and boundary review. |
| **Review owner** | Business or evidence owner who can accept, reopen, split, merge, or supersede the family. |
| **Next review** | Date, cadence, or event that prompts reconsideration. |
| **Review triggers** | Material changes to business purpose, lifecycle position, scope boundary, member use cases or JTBDs, adjacent families, controls, or cross-LOB applicability. |
| **Supersession links** | Prior, split, merged, or replacement stable IDs and revisions, or `None`. |
| **Change rationale** | Evidence delta and reason for the current revision or maturity decision. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | `[YYYY-MM-DD]` | `[Evidence included through cutoff]` | `[Promoted, revised, split, merged, maturity changed, or superseded]` | `[Review owner]` | `[Stable IDs or None]` |

## Quality Check

- [ ] The family is named for stable business work rather than a product, team, or screen.
- [ ] It has a coherent purpose and more than one plausible member.
- [ ] Inclusion and exclusion boundaries are explicit.
- [ ] Members are linked by stable IDs rather than duplicated inside the family record.
- [ ] Adjacent families and handoffs are identified.
- [ ] Variations are recorded without multiplying families unnecessarily.
- [ ] Evidence supports the grouping or the family is marked `[validate]`.
- [ ] Promoted records include complete governance metadata and append-only revision history.
- [ ] Membership, boundary, and supersession changes preserve stable-ID traceability.

## Worked Example

### JF-MA-01 - Buyer Strategy And Outreach Planning

| Field | Example |
| --- | --- |
| **Definition** | Work through which a sell-side deal team identifies, agrees, sequences, and prepares engagement with credible potential buyers. |
| **Business purpose** | Establish a defensible counterparty strategy that reflects client objectives and supports an effective sale process. |
| **Lifecycle position** | Deal preparation and early execution. |
| **Scope boundary** | Begins when buyer strategy is required and ends before active buyer engagement and bid management. |
| **Included work** | Develop buyer universe, agree exclusions, prioritize outreach, assign relationship ownership, and prepare engagement sequencing. |
| **Excluded work** | Initial opportunity qualification, direct buyer outreach, bid evaluation, and transaction negotiation. |
| **Primary business outcomes** | `BO-MA-01` - Accelerate buyer strategy preparation. |
| **Business use cases** | `BUC-MA-01` - Develop and agree the buyer universe. |
| **JTBDs** | `JTBD-MA-01` - Identify and prioritize credible buyers. |
| **Responsible actor cohorts** | Sell-side deal team, including Associate, VP, senior deal-team banker, Coverage, and relevant specialists. |
| **Adjacent job families** | Opportunity qualification; buyer engagement and process management `[validate IDs]`. |
| **Common business rules and controls** | Client exclusions, confidentiality, conflicts, information barriers, and senior acceptance. |
| **Known variations** | Pitch versus mandate, strategic versus sponsor emphasis, geography, sector, and transaction complexity. |
| **Evidence** | Illustrative example; replace with business-process and interview evidence. |
| **Evidence maturity** | `Hypothesis`. |

# SC-GIB-REL-01-C - Tier-Based Engagement Frequency Review

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-REL-01`](../business-use-cases/BUC-GIB-REL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-REL-01`](../jtbd/JTBD-GIB-REL-01.md) |
| **Value delivered** | An accepted relationship-quality judgment, an objective, a Decision on how to engage, and an owned next step for a priority client institution. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate) for delegated maintenance. |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Time since the last meaningful Engagement, or an expected Engagement-frequency condition, prompts a reassessment without another acute trigger. |
| **Trigger** | A tier-sensitive Engagement-frequency or dry-spell condition. |
| **Starting conditions** | Engagement may be stale, but no specific client need, risk, or opportunity is yet evident. |
| **Stakes and urgency** | Ignoring Engagement frequency can weaken access. Automatic Engagement can create purposeless outreach and client fatigue. |
| **What varies** | The response can be MD Engagement, delegated maintenance, review only, or a deliberate wait, based on tier and direction. |
| **What remains invariant** | Engagement frequency triggers a relationship judgment, not an automatic communication task. |
| **Additional business rules or controls** | Listening is a legitimate purpose; any Engagement must have a credible relationship objective. A gap in Engagement alone never produces a client Engagement (Q33, Q99). Any Engagement that follows this scenario first acquires a purpose at S4 and S5 of the parent, and only then runs through `BUC-GIB-REL-02` (candidate). This is the scenario the IBIQ draft-outreach product use case must explicitly exclude as a trigger. A product that turns a dry spell into a draft message contradicts this record. |
| **Exit or transition** | Personal Engagement, delegated Engagement, deliberate monitoring, or no action is accepted, with a condition for reassessment. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S3-S5 | Weight tier, direction, and prior pattern more heavily than an acute event. | Engagement frequency alone may justify a reassessment but not always action. | Maintenance may be delegated while the MD keeps the institution judgment. | Engagement is purposeful and proportionate. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Appropriate Engagement frequency by tier; fewer neglected priority relationships; no increase in low-purpose Engagement. |
| **Failure risks** | Optimising for Engagement volume, client fatigue, silent dry spells, or unclear delegation. |
| **Evidence** | Coverage evidence revision 2.0, Q33, Q97, Q99-Q100, and Q106. |
| **Open questions** | Validate tier definitions, expected Engagement frequency, and the evidence for meaningful Engagement. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.3` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After tier and Engagement-frequency evidence is validated. |
| **Review triggers** | Changed tier model, Engagement-frequency policy, delegated-maintenance boundary, or evidence of harmful Engagement incentives. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: record that this is the scenario the IBIQ outreach product use case must explicitly exclude, and that any Engagement following it must first acquire a purpose in the parent before `BUC-GIB-REL-02` (candidate) runs. Candidate support-team actor named for delegated maintenance. No change to the variation or its maturity. Revision 1.2 is a banker-language pass on wording only; title changed from "Tier-Based Cadence Review". Revision 1.3 is a terminology pass on wording only: Interaction and Engagement adopted as governed terms. Title changed from "Tier-Based Contact Frequency Review". |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-REL-01` |
| `1.1` | 2026-10-07 | No new evidence; model revision of 2026-10-07 | Revised in place: exclusion rule for the IBIQ outreach product use case stated; boundary with `BUC-GIB-REL-02` (candidate) stated. | Coverage intent model owner | `BUC-GIB-REL-01`, `BUC-GIB-REL-02` (candidate) |
| `1.2` | 2026-10-07 | No new evidence; wording only | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Title changed from "Tier-Based Cadence Review". Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | `BUC-GIB-REL-01`, `JF-GIB-REL-01` |
| `1.3` | 2026-10-07 | No new evidence; wording only | Terminology: Interaction (a live exchange with a client: call, virtual or in person) and Engagement (any client contact, including email) adopted as governed terms. Title changed from "Tier-Based Contact Frequency Review". Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner | `BUC-GIB-REL-01`, `JF-GIB-REL-01` |

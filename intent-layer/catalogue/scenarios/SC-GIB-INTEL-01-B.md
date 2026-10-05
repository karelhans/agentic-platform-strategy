# SC-GIB-INTEL-01-B - Uncertain High-Impact Signal

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted disposition, rationale, intended outcome, and destination for potentially consequential intelligence. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; preparatory triage contributors `[validate actor]`. |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Potential client or franchise impact is high, but sources, corroboration, or interpretation remain uncertain. |
| **Trigger** | Evidence suggests a consequential possibility without confidence sufficient for direct use. |
| **Starting conditions** | Impact and confidence diverge; evidence may be hypothesis rather than fact. |
| **Stakes and urgency** | Dismissing too early may miss a major change; acting too strongly may damage credibility or trust. |
| **What varies** | Source scrutiny, corroboration, and response calibration increase with impact and remaining time. |
| **What remains invariant** | The disposition, rationale, intended outcome, destination, and uncertainty are explicit. |
| **Additional business rules or controls** | Match contemplated use to evidential strength; high impact raises scrutiny rather than automatically triggering action. |
| **Exit or transition** | Validate, escalate as a hypothesis, use as a question, monitor, or dismiss with rationale. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S3-S5 | Spend more judgment on evidential strength and proportionate use. | Consequence is high but confidence is low. | Senior Coverage MD determines acceptable use; contributors target validation. | The chosen response cannot imply more certainty than the evidence supports. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Important uncertainty reaches judgment without being presented as fact; validation effort is proportionate; client action matches confidence. |
| **Failure risks** | False certainty, paralysis, over-escalation, or quiet dismissal of consequential evidence. |
| **Evidence** | Coverage evidence revision 2.0, Q31-Q32, Q76, and Q83-Q90. |
| **Open questions** | Validate source and confidence conventions across intelligence types. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.0` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-02 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After uncertain high-impact episodes and controls validation. |
| **Review triggers** | Changed confidence convention, validation authority, acceptable use, or evidence that this requires a separate value outcome. |
| **Supersession links** | None. |
| **Change rationale** | Promote the existing evidence-backed uncertainty variation. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-INTEL-01` |

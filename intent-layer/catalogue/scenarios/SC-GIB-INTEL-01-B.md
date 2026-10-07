# SC-GIB-INTEL-01-B - Uncertain High-Impact Signal

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-INTEL-01`](../business-use-cases/BUC-GIB-INTEL-01.md) |
| **Related JTBDs** | [`JTBD-GIB-INTEL-01`](../jtbd/JTBD-GIB-INTEL-01.md) |
| **Value delivered** | An accepted Decision, Rationale, intended outcome, and View for a potentially material Signal. |
| **Primary actor cohorts** | `ACTOR-COV-SENIOR-MD`; `ACTOR-COV-SUPPORT-TEAM` (candidate). |
| **Evidence maturity** | `Evidence-backed` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | Potential client or firm impact is high, but sources, corroboration, or interpretation remain uncertain. |
| **Trigger** | Evidence suggests a material possibility without enough confidence for direct use. |
| **Starting conditions** | Impact and confidence diverge; evidence may be a starting view rather than fact. |
| **Stakes and urgency** | Dismissing too early may miss a major change; acting too strongly may damage credibility or trust. |
| **What varies** | Source scrutiny, corroboration, and response calibration increase with impact and remaining time. |
| **What remains invariant** | The Decision, Rationale, intended outcome, View, and uncertainty are explicit. |
| **Additional business rules or controls** | Match the intended use to evidential strength; high impact raises scrutiny rather than automatically triggering action. |
| **Exit or transition** | Validate, escalate as a starting view, use as a question, monitor, or dismiss with Rationale. A `validate` Decision (Q73) is not an exit. It returns the item to `BUC-GIB-INTEL-01-S3` with the question to be answered, and the item then re-enters judgment at S4. |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S3-S5 | Spend more judgment on evidential strength and proportionate use; a `validate` Decision at S5 loops back to S3. | Consequence is high but confidence is low. | Senior Coverage MD determines acceptable use; contributors target validation. | The chosen response cannot imply more certainty than the evidence supports. Validation is bounded by the question set at S5. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | Important uncertainty reaches judgment without being presented as fact; validation effort is proportionate; client action matches confidence. |
| **Failure risks** | False certainty, paralysis, over-escalation, or quiet dismissal of material evidence. |
| **Evidence** | Coverage evidence revision 2.0, Q31-Q32, Q76, and Q83-Q90. |
| **Open questions** | Validate source and confidence conventions across Signal types. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `1.2` |
| **Evidence cutoff** | 2026-10-02, through Q151. |
| **Review state** | `Current` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After uncertain high-impact episodes and controls validation. |
| **Review triggers** | Changed confidence convention, validation authority, acceptable use, or evidence that this requires a separate value outcome. |
| **Supersession links** | None. |
| **Change rationale** | Model revision of 2026-10-07: state the validate loop back to S3 explicitly. Variation unchanged. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `1.0` | 2026-10-02 | Confirmed-intent synthesis through Q151 | Promoted as `Evidence-backed`. | Coverage intent model owner | `BUC-GIB-INTEL-01` |
| `1.1` | 2026-10-07 | Model revision of 2026-10-07; Q73 re-read | Revised in place; validate loop made explicit, no semantic change. | `[validate: intent model owner]` | `BUC-GIB-INTEL-01` |
| `1.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | `[validate: intent model owner]` | None |

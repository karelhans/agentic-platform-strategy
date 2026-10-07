# SC-GIB-MEET-01-E - Short-Notice Or Unplanned Interaction

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-MEET-01`](../business-use-cases/BUC-GIB-MEET-01.md) |
| **Related JTBDs** | [`JTBD-GIB-MEET-01`](../jtbd/JTBD-GIB-MEET-01.md) |
| **Value delivered** | An interpreted high-stakes client meeting outcome with explicit commitments, affected intent job families updated, and first follow-through begun. |
| **Primary actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate raised by the model revision of 2026-10-07, not admitted), where there is time to involve them. |
| **Evidence maturity** | `Hypothesis` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | A high-stakes client conversation arrives without a planned window. The client calls, asks for a same-day meeting, or raises a material matter inside a routine conversation. Or the Senior Coverage MD meets a senior client stakeholder unexpectedly. |
| **Trigger** | A client conversation becomes high-stakes with little or no notice. This is the use case's "emerging" trigger rather than its "planned" one. |
| **Starting conditions** | Context, starting view and JPM posture must be assembled in minutes or recalled from memory. The supporting team may not be reachable. Critical uncertainty may have to be carried into the room. Participants are whoever is available. |
| **Stakes and urgency** | The window to learn or influence is the same as in a planned meeting, but the time to prepare is not. A poorly grounded response can harden a client position or over-commit JPM. Declining or deferring the conversation can itself cost standing. |
| **What varies** | Preparation is compressed, not absent. S1 to S3 collapse into a short judgment by the Senior Coverage MD, often alone. The starting view is provisional and stated as such in the room. Uncertainty is held visibly and resolved afterwards rather than before. Interpretation and sending on may happen immediately after the conversation, with the supporting team joining at S5 and S6. |
| **What remains invariant** | A stated purpose, however brief; a coherent JPM posture; an interpreted outcome; explicit commitments or their explicit absence; affected job families updated; the first step begun. The value delivered is unchanged. |
| **Additional business rules or controls** | No commitment is made beyond what the MD can authorise alone. A provisional starting view is not presented as a settled view. Unresolved uncertainty is named and carried into follow-through. Deferring the substantive conversation to a prepared window is a valid outcome. The cross-family control rule applies. |
| **Exit or transition** | The outcome is interpreted and sent on as in the parent use case. Where the conversation is deferred, a planned meeting follows as scenario A to D. A follow-up contact hands to `BUC-GIB-REL-02` (candidate). |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1-S3 | Compressed into a short judgment: why it matters, what to learn or protect, what not to say. | No preparation window; the client sets the timing. | The Senior Coverage MD often judges alone. The supporting team's preparatory contribution is reduced or absent. | Readiness is partial by design. The MD enters knowing what is unresolved. |
| S4 | A larger share of the starting view is tested live. Deferring the substantive discussion is an explicit option. | Uncertainty could not be resolved beforehand. | The MD decides in the room whether to engage substantively or defer to a prepared meeting. | New evidence may be richer or riskier than in a planned meeting. |
| S5-S6 | Interpretation happens promptly after the conversation. The supporting team is brought in to translate and send on. | Memory decays, and commitments made quickly are easiest to lose. | The supporting team joins late. The relationship owner receives the changed state. | Capture without interpretation is a particular risk here. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | The conversation still has a stated purpose. Uncertainty is named rather than hidden. Commitments match authority. The outcome is interpreted and sent on as promptly as after a planned meeting. Deferral, where chosen, is deliberate. |
| **Failure risks** | Reaction without a purpose; an over-confident provisional view; unauthorised or implied commitment; the conversation lost because it was never interpreted; follow-through unowned because no team was involved. |
| **Evidence** | The parent use case's trigger already admits an "emerging" interaction (Q123 to Q127 by inference). The Round 2 meetings guide CMEET10 offers "short-notice interaction" as a candidate variation. It is a draft instrument, not participant evidence. No participant has described such an episode and none has been observed. |
| **Open questions** | Whether short notice changes preparation, participation or follow-through enough to be a scenario, or is only a timing difference inside scenarios A to D. How often the MD defers rather than engages. Whether the supporting team's late involvement changes ownership of follow-through. Test through Round 2 CMEET10 and CMEET12. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.2` |
| **Evidence cutoff** | 2026-10-07, through Q151 and the model revision of 2026-10-07. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After Round 2 CMEET10 responses or an observed short-notice high-stakes conversation, whichever comes first. |
| **Review triggers** | Participant evidence that short notice does or does not materially change the work; an observed episode; a change to the parent use case's trigger. |
| **Supersession links** | None. |
| **Change rationale** | Raised by the model revision of 2026-10-07 as a candidate scenario and not admitted. Held at `Hypothesis` because the only support is the parent trigger's "emerging" wording and a Round 2 question. Charter section 6 requires an episode or gap marker before promotion. Preparation is compressed, not absent, so the variation preserves the parent's value and is a scenario rather than a use case. Banker-language pass of 2026-10-07: wording only. |

## Revision History

| Revision | Date | Evidence delta | Decision and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | Parent trigger wording; Round 2 CMEET10 as instrument; model revision of 2026-10-07, meetings family inventory sections B and D. | Candidate at `Hypothesis`; not admitted. Awaits participant evidence or an observed episode. | Coverage intent model owner (as candidate) | `BUC-GIB-MEET-01`, `JF-GIB-MEET-01`, `JTBD-GIB-MEET-01` |
| `0.2` | 2026-10-07 | None; wording only. | Banker-language pass: editorial wording in house language (Decision, Rationale, View, Signal; send to; owner; management; material or high-stakes). Meaning, evidence, maturity and review state unchanged. | Coverage intent model owner (as candidate) | None. |

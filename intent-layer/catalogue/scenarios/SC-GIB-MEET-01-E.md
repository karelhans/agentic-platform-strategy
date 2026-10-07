# SC-GIB-MEET-01-E - Short-Notice Or Unplanned Interaction

## Classification

| Field | Value |
| --- | --- |
| **Parent business use case** | [`BUC-GIB-MEET-01`](../business-use-cases/BUC-GIB-MEET-01.md) |
| **Related JTBDs** | [`JTBD-GIB-MEET-01`](../jtbd/JTBD-GIB-MEET-01.md) |
| **Value delivered** | An interpreted consequential client-interaction outcome with explicit commitments, affected intent job families updated, and first follow-through initiated. |
| **Primary actor cohorts** | [`ACTOR-COV-SENIOR-MD`](../actors/ACTOR-COV-SENIOR-MD.md); [`ACTOR-COV-SUPPORT-TEAM`](../actors/ACTOR-COV-SUPPORT-TEAM.md) (candidate raised by the model revision of 2026-10-07, not admitted), where there is time to involve them. |
| **Evidence maturity** | `Hypothesis` |

## Context And Variation

| Field | Value |
| --- | --- |
| **Context** | A consequential client interaction arrives without a planned window: the client calls, asks for a meeting the same day, raises a consequential matter inside a routine conversation, or the Senior Coverage MD meets a senior client stakeholder unexpectedly. |
| **Trigger** | A client interaction becomes consequential with little or no notice; the use case's "emerging" trigger rather than its "planned" one. |
| **Starting conditions** | Context, hypothesis and JPM posture must be assembled in minutes or recalled from memory; the supporting team may not be reachable; critical uncertainty may have to be carried into the room; participants are whoever is available. |
| **Stakes and urgency** | The window to learn or influence is the same as in a planned interaction but the time to prepare is not; a poorly grounded response can harden a client position or over-commit JPM, while declining or deferring the conversation can itself cost standing. |
| **What varies** | Preparation is compressed, not absent: S1 to S3 collapse into a short judgment by the Senior Coverage MD, often alone; the hypothesis is provisional and stated as such in the room; uncertainty is held visibly and resolved afterwards rather than before; interpretation and routing may happen immediately after the conversation, with the supporting team joining at S5 and S6. |
| **What remains invariant** | A stated purpose, however brief; a coherent JPM posture; an interpreted outcome; explicit commitments or their explicit absence; affected job families updated; first movement begun. The value delivered is unchanged. |
| **Additional business rules or controls** | No commitment is made beyond what the MD can authorise alone; a provisional hypothesis is not presented as a settled view; unresolved uncertainty is named and carried to follow-through; deferral of the substantive conversation to a prepared window is a valid outcome; the cross-family control rule applies. |
| **Exit or transition** | The outcome is interpreted and routed as in the parent use case; where the conversation is deferred, a planned interaction follows as scenario A to D; a follow-up contact hands to `BUC-GIB-REL-02` (candidate). |

## Process Variation

| Parent step | Variation | Reason | Actor or authority change | Resulting implication |
| --- | --- | --- | --- | --- |
| S1-S3 | Compressed into a short judgment: why it matters, what to learn or protect, what not to say. | No preparation window; the client sets the timing. | Senior Coverage MD often judges alone; the supporting team's preparatory contribution is reduced or absent. | Readiness is partial by design; the MD enters knowing what is unresolved. |
| S4 | A larger share of the hypothesis is tested live; deferring the substantive discussion is an explicit option. | Uncertainty could not be resolved beforehand. | MD decides in the room whether to engage substantively or to defer to a prepared interaction. | New evidence may be richer or riskier than in a planned meeting. |
| S5-S6 | Interpretation happens promptly after the conversation, with the supporting team brought in to translate and route. | Memory decays and commitments made quickly are easiest to lose. | Supporting team joins late; the relationship owner receives the changed state. | Capture without interpretation is a particular risk here. |

## Evidence And Validation

| Field | Value |
| --- | --- |
| **Success signals** | The conversation still has a stated purpose; uncertainty is named rather than hidden; commitments match authority; the outcome is interpreted and routed as promptly as in a planned interaction; deferral, where chosen, is deliberate. |
| **Failure risks** | Reaction without a purpose; an over-confident provisional view; unauthorised or implied commitment; the conversation lost because it was never interpreted; follow-through unowned because no team was involved. |
| **Evidence** | The parent use case's trigger already admits an "emerging" interaction (Q123 to Q127 by inference). The Round 2 meetings guide CMEET10 offers "short-notice interaction" as a candidate variation; it is a draft instrument, not participant evidence. No participant has described such an episode and none has been observed. |
| **Open questions** | Whether short notice changes preparation, participation or follow-through enough to be a scenario, or is only a timing difference inside scenarios A to D; how often the MD defers rather than engages; whether the supporting team's late involvement changes ownership of follow-through. Test through Round 2 CMEET10 and CMEET12. |

## Record Governance

| Field | Value |
| --- | --- |
| **Revision** | `0.1` |
| **Evidence cutoff** | 2026-10-07, through Q151 and the model revision of 2026-10-07. |
| **Review state** | `Candidate` |
| **Last reviewed** | 2026-10-07 |
| **Review owner** | Coverage intent model owner |
| **Next review** | After Round 2 CMEET10 responses or an observed short-notice consequential interaction, whichever comes first. |
| **Review triggers** | Participant evidence that short notice does or does not materially change the work; an observed episode; a change to the parent use case's trigger. |
| **Supersession links** | None. |
| **Change rationale** | Raised by the model revision of 2026-10-07 as a candidate scenario and not admitted. Held at `Hypothesis` because the only support is the parent trigger's "emerging" wording and a Round 2 question; charter section 6 requires an episode or gap marker before promotion. Preparation is compressed, not absent, so the variation preserves the parent's value and is a scenario rather than a use case. |

## Revision History

| Revision | Date | Evidence delta | Disposition and rationale | Accepted by | Impacted records |
| --- | --- | --- | --- | --- | --- |
| `0.1` | 2026-10-07 | Parent trigger wording; Round 2 CMEET10 as instrument; model revision of 2026-10-07, meetings family inventory sections B and D. | Candidate at `Hypothesis`; not admitted. Awaits participant evidence or an observed episode. | Coverage intent model owner (as candidate) | `BUC-GIB-MEET-01`, `JF-GIB-MEET-01`, `JTBD-GIB-MEET-01` |

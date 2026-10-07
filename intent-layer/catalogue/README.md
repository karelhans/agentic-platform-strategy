# Intent Catalogue

This directory contains canonical, reviewable intent records derived from tracked evidence. Promotion means a record is the current accepted interpretation at its evidence cutoff; it does not freeze the record against later validation.

See the [Intent Artifact Generation Guide](../templates/artifact_generation_guide.md) for evidence maturity, review triggers, revision, supersession, and downstream impact rules.

## Review states and candidates

Every record carries a review state. `Current`, `Review required` and `In review` are the admitted states. Two more are used since the model revision of 2026-10-07 ([`proposals/model-revision-2026-10-07.md`](../proposals/model-revision-2026-10-07.md)):

- `Candidate`: raised by the model revision and not admitted. Revision `0.1` where no evidence beyond the Round 1 interview supports the record; `1.0` where the proposal's test found it evidence-backed. Admission follows charter rule 6 and the Round 2 guides. Consumers may cite a candidate only as a gap, never as a justification.
- `Superseded`: kept for history; the superseding record is named in the record. Consumers must not cite it.

## Coverage Senior MD Slices

**Evidence source:** [Coverage Senior MD confirmed intent evidence revision 2.1](../evidence/coverage-senior-md/confirmed-intent.md)

### Intelligence Triage

| Artifact | Stable ID | Maturity | Revision | Review state | Record |
| --- | --- | --- | --- | --- | --- |
| Business outcome | `BO-GIB-INTEL-01` | `Hypothesis` | `1.2` | `Current` | [Improve response to material signals](business-outcomes/BO-GIB-INTEL-01.md) |
| Job family | `JF-GIB-INTEL-01` | `Evidence-backed` | `1.2` | `Current` | [Intelligence triage](job-families/JF-GIB-INTEL-01.md) |
| Business use case | `BUC-GIB-INTEL-01` | `Evidence-backed` | `1.2` | `Current` | [Triage and send a material signal](business-use-cases/BUC-GIB-INTEL-01.md) |
| Business use case | `BUC-GIB-INTEL-02` | `Evidence-backed` for trigger, value and judgments | `0.2` | `Candidate` | [Bring a held signal to its accountable owner](business-use-cases/BUC-GIB-INTEL-02.md) |
| JTBD | `JTBD-GIB-INTEL-01` | `Confirmed` for Senior Coverage MDs, one participant | `1.2` | `Current` | [Isolate and judge material change](jtbd/JTBD-GIB-INTEL-01.md) |
| JTBD | `JTBD-GIB-INTEL-02` | `Evidence-backed` for the need; wording untested | `0.2` | `Candidate` | [Bring held information to its accountable owner](jtbd/JTBD-GIB-INTEL-02.md) |
| Scenario | `SC-GIB-INTEL-01-A` | `Evidence-backed` | `1.2` | `Current` | [Short-window material signal](scenarios/SC-GIB-INTEL-01-A.md) |
| Scenario | `SC-GIB-INTEL-01-B` | `Evidence-backed` | `1.2` | `Current` | [Uncertain high-impact signal](scenarios/SC-GIB-INTEL-01-B.md) |
| Scenario | `SC-GIB-INTEL-01-C` | `Evidence-backed` | `1.2` | `Current` | [Monitor or dismiss](scenarios/SC-GIB-INTEL-01-C.md) |
| Scenario | `SC-GIB-INTEL-01-D` | `Hypothesis` | `0.2` | `Candidate` | [Accumulated signals with no single trigger](scenarios/SC-GIB-INTEL-01-D.md) |
| Scenario | `SC-GIB-INTEL-01-E` | `Evidence-backed` | `1.1` | `Candidate` | [Converging changes or cross-client implication](scenarios/SC-GIB-INTEL-01-E.md) |

### Client Relationship Management

| Artifact | Stable ID | Maturity | Revision | Review state | Record |
| --- | --- | --- | --- | --- | --- |
| Business outcome | `BO-GIB-REL-01` | `Hypothesis` | `1.2` | `Current` | [Strengthen priority client relationship quality](business-outcomes/BO-GIB-REL-01.md) |
| Job family | `JF-GIB-REL-01` | `Evidence-backed` | `1.2` | `Current` | [Client relationship management](job-families/JF-GIB-REL-01.md) |
| Business use case | `BUC-GIB-REL-01` | `Evidence-backed` | `1.2` | `Current` | [Review and direct a priority client relationship](business-use-cases/BUC-GIB-REL-01.md) |
| Business use case | `BUC-GIB-REL-02` | `Hypothesis`; S1, S2, S5 evidence-backed | `0.2` | `Candidate` | [Execute a purposeful client contact](business-use-cases/BUC-GIB-REL-02.md) |
| JTBD | `JTBD-GIB-REL-01` | `Confirmed` for Senior Coverage MDs, one participant | `1.2` | `Current` | [Strengthen priority client relationships](jtbd/JTBD-GIB-REL-01.md) |
| Scenario | `SC-GIB-REL-01-A` | `Evidence-backed` | `1.2` | `Current` | [Contextual change in the client institution](scenarios/SC-GIB-REL-01-A.md) |
| Scenario | `SC-GIB-REL-01-B` | `Evidence-backed` | `1.2` | `Current` | [Time-Sensitive relationship risk or commitment](scenarios/SC-GIB-REL-01-B.md) |
| Scenario | `SC-GIB-REL-01-C` | `Evidence-backed` | `1.2` | `Current` | [Tier-based contact frequency review](scenarios/SC-GIB-REL-01-C.md) |
| Scenario | `SC-GIB-REL-01-D` | `Evidence-backed` | `1.1` | `Candidate` | [Cross-JPM overlap on one institution](scenarios/SC-GIB-REL-01-D.md) |

### Opportunity Pipeline Management

| Artifact | Stable ID | Maturity | Revision | Review state | Record |
| --- | --- | --- | --- | --- | --- |
| Business outcome | `BO-GIB-PIPE-01` | `Hypothesis` | `1.2` | `Current` | [Improve opportunity portfolio accuracy](business-outcomes/BO-GIB-PIPE-01.md) |
| Job family | `JF-GIB-PIPE-01` | `Evidence-backed` | `1.2` | `Current` | [Opportunity pipeline management](job-families/JF-GIB-PIPE-01.md) |
| Business use case | `BUC-GIB-PIPE-01` | `Evidence-backed` | `3.1` | `Current` | [Review one opportunity and decide its next move](business-use-cases/BUC-GIB-PIPE-01.md) |
| Business use case | `BUC-GIB-PIPE-02` | Trigger and value `Evidence-backed`; steps `Hypothesis` | `0.2` | `Candidate` | [Recognise an idea as an opportunity](business-use-cases/BUC-GIB-PIPE-02.md) |
| Business use case | `BUC-GIB-PIPE-03` | `Evidence-backed`; no forum observed | `0.2` | `Candidate` | [Review the portfolio and redirect effort](business-use-cases/BUC-GIB-PIPE-03.md) |
| JTBD | `JTBD-GIB-PIPE-01` | `Confirmed` for Senior Coverage MDs, one participant | `2.2` | `Current` | [Maintain disciplined opportunity management](jtbd/JTBD-GIB-PIPE-01.md) |
| Scenario | `SC-GIB-PIPE-01-A` | `Superseded` by `BUC-GIB-PIPE-03` | `2.0` | `Superseded` | [Recurring pipeline management session](scenarios/SC-GIB-PIPE-01-A.md) |
| Scenario | `SC-GIB-PIPE-01-B` | `Evidence-backed` | `1.2` | `Current` | [Material change or closing decision window](scenarios/SC-GIB-PIPE-01-B.md) |
| Scenario | `SC-GIB-PIPE-01-C` | `Evidence-backed` | `1.2` | `Current` | [Parked opportunity reactivation](scenarios/SC-GIB-PIPE-01-C.md) |
| Scenario | `SC-GIB-PIPE-01-D` | `Evidence-backed` | `1.2` | `Current` | [Ambiguous early idea after recognition](scenarios/SC-GIB-PIPE-01-D.md) |
| Scenario | `SC-GIB-PIPE-01-E` | `Superseded` by the cross-family control rule | `2.0` | `Superseded` | [Restricted cross-gib opportunity](scenarios/SC-GIB-PIPE-01-E.md) |
| Scenario | `SC-GIB-PIPE-01-F` | `Evidence-backed` | `1.1` | `Current` | [Deliberate exit](scenarios/SC-GIB-PIPE-01-F.md) |
| Scenario | `SC-GIB-PIPE-01-G` | `Evidence-backed` | `1.1` | `Current` | [Review condition reached without progress](scenarios/SC-GIB-PIPE-01-G.md) |
| Scenario | `SC-GIB-PIPE-03-A` | `Evidence-backed` | `1.1` | `Candidate` | [Alignment-Only forum](scenarios/SC-GIB-PIPE-03-A.md) |
| Scenario | `SC-GIB-PIPE-03-B` | `Evidence-backed` | `1.1` | `Candidate` | [Decision forum](scenarios/SC-GIB-PIPE-03-B.md) |

### High-Stakes Client Meetings

| Artifact | Stable ID | Maturity | Revision | Review state | Record |
| --- | --- | --- | --- | --- | --- |
| Business outcome | `BO-GIB-MEET-01` | `Hypothesis` | `1.1` | `Current` | [Improve high-stakes client meeting outcomes](business-outcomes/BO-GIB-MEET-01.md) |
| Job family | `JF-GIB-MEET-01` | `Evidence-backed` | `1.2` | `Current` | [High-Stakes client meetings](job-families/JF-GIB-MEET-01.md) |
| Business use case | `BUC-GIB-MEET-01` | `Evidence-backed` | `1.2` | `Current` | [Prepare, conduct, and convert a high-stakes client meeting](business-use-cases/BUC-GIB-MEET-01.md) |
| JTBD | `JTBD-GIB-MEET-01` | `Confirmed` for Senior Coverage MDs, one participant | `1.2` | `Current` | [Convert high-stakes client meetings into progress](jtbd/JTBD-GIB-MEET-01.md) |
| Scenario | `SC-GIB-MEET-01-A` | `Evidence-backed` | `1.1` | `Current` | [Forming client decision](scenarios/SC-GIB-MEET-01-A.md) |
| Scenario | `SC-GIB-MEET-01-B` | `Evidence-backed` | `1.1` | `Current` | [Relationship-Sensitive listening or repair](scenarios/SC-GIB-MEET-01-B.md) |
| Scenario | `SC-GIB-MEET-01-C` | `Evidence-backed` | `1.2` | `Current` | [Major commitment or cross-jpm meeting](scenarios/SC-GIB-MEET-01-C.md) |
| Scenario | `SC-GIB-MEET-01-D` | `Evidence-backed` | `1.1` | `Current` | [Protocol-Driven or first senior interaction](scenarios/SC-GIB-MEET-01-D.md) |
| Scenario | `SC-GIB-MEET-01-E` | `Hypothesis` | `0.2` | `Candidate` | [Short-Notice or unplanned interaction](scenarios/SC-GIB-MEET-01-E.md) |

### Actions And Commitments (candidate family)

Raised by the model revision of 2026-10-07 from the Round 1 actions evidence (Q118 to Q122, Q136, Q141, Q145). Nothing in this family is admitted. The Round 2 actions guide is the instrument.

| Artifact | Stable ID | Maturity | Revision | Review state | Record |
| --- | --- | --- | --- | --- | --- |
| Job family | `JF-GIB-ACT-01` | `Hypothesis` | `0.2` | `Candidate` | [Actions and commitments](job-families/JF-GIB-ACT-01.md) |
| Business use case | `BUC-GIB-ACT-01` | `Hypothesis` | `0.2` | `Candidate` | [Resolve a commitment that is drifting or waiting on the senior](business-use-cases/BUC-GIB-ACT-01.md) |
| JTBD | `JTBD-GIB-ACT-01` | `Evidence-backed`; Q122 accepted as a starting hypothesis | `0.2` | `Candidate` | [Translate intent into accepted ownership and explicit commitment](jtbd/JTBD-GIB-ACT-01.md) |

No business outcome exists for this family yet; the measure one would need is in the job family record.

### Actors (shared across families)

| Artifact | Stable ID | Maturity | Revision | Review state | Record |
| --- | --- | --- | --- | --- | --- |
| Actor | `ACTOR-COV-SENIOR-MD` | `Evidence-backed` | `2.2` | `Current` | [Senior coverage MD](actors/ACTOR-COV-SENIOR-MD.md) |
| Actor | `ACTOR-COV-PIPELINE-TEAM` | `Evidence-backed` | `1.2` | `Review required` | [Coverage opportunity team](actors/ACTOR-COV-PIPELINE-TEAM.md) |
| Actor | `ACTOR-COV-SUPPORT-TEAM` | `Evidence-backed` from the MD's account only | `0.2` | `Candidate` | [Coverage supporting cohort](actors/ACTOR-COV-SUPPORT-TEAM.md) |

## Cross-Family Control Rule

Restricted or sensitive information is not a scenario anywhere in the catalogue. It is a business rule carried by every use case: the holder of restricted information acts only within what they are permitted to know and share (Q70), cross-family situations lead through the accountable owner (Q136, Q145), and business heads arbitrate contested ownership (Q142). `SC-GIB-PIPE-01-E` was superseded by this rule.

## Validation Boundary

- The exact intelligence, relationship, pipeline, and client-meetings JTBD statements are confirmed for the Senior Coverage MD cohort by one participant. Consumers treat them as evidence-backed until a second banker has been through them.
- Supporting records retain independent maturity and do not inherit confirmation.
- Business outcomes remain hypotheses until baseline, target, timeframe, and measurement authority are approved.
- A concrete lost, parked, or delayed opportunity episode remains an evidence gap for the process and scenario records. No episode at all exists for the candidate use cases.
- Cross-LOB, product-banker, controls, data-authority, and regional applicability remain open validation areas.
- The confirmed umbrella statement frames the model and is served by no use case of its own (confirmed-intent revision 2.1). Daily re-orientation and converging changes are scenarios of the intelligence use case, not an umbrella use case.
- The actions statement is catalogued as a candidate family at `Hypothesis`; capacity remains deferred.
- The runtime Capability Register is a read-only downstream projection of the four admitted families. It carries the confirmed pipeline and client-meetings contracts, while revision and review governance remain authoritative in these Markdown records. Candidate records are not projected.

## Review

Each record includes its own evidence cutoff, review state, owner, next review, triggers, supersession links, rationale, and append-only history. New findings should mark only affected records `Review required`, preserve contradictory evidence, and follow the guide's re-review procedure.

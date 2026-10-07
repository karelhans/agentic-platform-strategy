# Audit and assessment of the Interview questions + Value stream corpus

Date: 2026-10-05. Scope: every file on the Figma page "Interview questions + Value stream" as ingested into `intent-layer/`, which is the four-job-family Coverage intent catalogue (business outcome, job family, business use case, JTBD, scenarios), the confirmed-intent evidence record, the Round 1 discovery mega-interview (Q01 to Q151), the Round 2 product-proxy interview guides, the templates and generation guide, the BUC writing prompt, the banker archetypes, the untested user profiles and the three personas.

Two questions were asked. First, is the value stream to JTBD to scenario mapping sound? Second, do the interviews do the job of validating that the model is the right summary of how the business operates and thinks, and that it is framed around value?

The short answer: the catalogue is a well-governed, internally consistent model of one Senior Coverage MD's mental model, derived top-down from statements the researcher drafted and the MD accepted. It is strong on structure and honesty about maturity, and weak on observed evidence, on value quantification, and on breadth of participants. The Round 2 proxy guides are a better instrument than Round 1, but they test a different thing (market-intelligence direction for two cohorts), not the catalogue. A validation instrument for the existing model does not yet exist.

## Part 1. The value stream to JTBD to scenario mapping

### What is good

**The hierarchy is applied consistently and honestly.** All four job families (INTEL, REL, PIPE, MEET) follow the same chain: business outcome, job family, business use case, JTBD, scenarios, each with stable IDs, evidence citations by question number, and an explicit evidence maturity. The maturity labels are used correctly. Every business outcome is `Hypothesis`, every job family, use case and scenario is `Evidence-backed`, and only the five JTBD statements the MD accepted verbatim are `Confirmed`. The catalogue says in several places that confirmation of a JTBD does not propagate to the records around it. That discipline is rare and is the corpus's biggest strength.

**The JTBD statements are genuinely at intent altitude.** Each contains a situation, desired progress and judgment, an outcome and an unwanted trade-off. None names a product, screen or feed. The guide's solution-language guardrail is respected throughout the catalogue (the untested user profiles and archetypes are a different matter, below).

**Scenarios are contextual variations, not flows.** Each scenario preserves the parent use case's value delivered, names what varies and what stays invariant, and points at the parent steps it compresses or reweights. The three INTEL scenarios (short window, uncertain high impact, deliberate non-action) are a clean single axis. Deliberate non-action appearing as a first-class scenario in three of four job families is a strong, evidence-backed design choice that most intent models miss.

**Cross-family routing is coherent.** Every use case ends with a disposition and a destination. The routing rule (accountable owner leads, cross-links retained) came from Q136 and is applied uniformly.

### Where it is weak

**1. The chain is one-to-one everywhere, so the job family record is doing no work beyond naming the chain.** Each job family has exactly one outcome, one use case and one JTBD. The generation guide says relationships are many-to-many; the catalogue never exercises that. Read side by side, JF-GIB-INTEL-01's definition and BUC-GIB-INTEL-01's process boundary say the same thing. This is the signature of a catalogue derived downward from a confirmed JTBD rather than upward from observed processes. The informal term "lens" has been retired in favour of the job family record, which removes the duplicate name; the record still has to earn its separate existence with a second use case per family. Candidates already exist inside the scenarios (see point 2).

**2. Several scenarios change the value delivered, which by the guide's own test makes them use cases.** SC-GIB-PIPE-01-A (recurring portfolio session) produces a portfolio-level shared picture; the parent use case's value is a per-opportunity judgment. SC-GIB-PIPE-01-C (parked reactivation) starts from a closed record and renews ownership, which is a different trigger and starting state. SC-GIB-PIPE-01-E (restricted cross-GIB) is really a controls variation that applies to all four job families, not a pipeline scenario. The PIPE scenarios mix five axes (forum, event, lifecycle state, maturity, controls), where INTEL mixes one. The corpus's own BUC writing prompt says "all scenarios on ONE axis" and "a scenario whose value sentence could be swapped into another scenario is wrong". The catalogue would not pass its own prompt.

**3. The business outcome layer is the weakest link, and it is where value lives.** Every number in all four outcomes is `[validate]`. More importantly, the chosen measures are hard to make real:

- "Portfolio accuracy" (PIPE) rewards conservative calls and needs an outcome registry that does not exist. The record itself warns it "must not reward false certainty".
- "Consequential surprises" (INTEL) requires a counterfactual judgment about what should have been foreseen.
- "Relationship quality" (REL) is explicitly warned against being reduced to a score in the same record that proposes it as the primary measure.
- "Proportion of meetings with an accepted interpreted outcome" (MEET) measures process compliance, not business result.

None of the four outcomes connects to a commercial quantity (revenue at risk, wallet share, win rate, mandate conversion, senior hours). Q113 shows why: the MD placed operating discipline and reduced overhead at the centre, so the model faithfully reflects that. But the "so that" clauses in the JTBDs are value-laden (avoid surprises, remain relevant, protect the outlook) and nothing downstream quantifies them. The model is framed around value qualitatively and not at all quantitatively.

**4. The actions and commitments job family is the sink for every other job family and it is not catalogued.** All four use cases route their output to "the actions job family". The meeting job is explicitly complete only when follow-through "has begun". The actions JTBD is an evidence-backed hypothesis (Q122) with no business outcome, use case or scenarios. Structurally, the value stream drains into a job family that does not exist. Either catalogue BUC-GIB-ACT-01 or stop routing to it and name the real destination (the accountable owner's own job family).

**5. The actor layer is thin, and two incompatible persona systems coexist.** The catalogue README links to `actors/ACTOR-COV-SENIOR-MD.md`, `actors/ACTOR-COV-PIPELINE-TEAM.md` and `pipeline-capability-contributions.md`; none of these is on the Figma page, so none is in this folder. Every contributor role in every use case is `[validate actor]`. Meanwhile seven untested user profiles, three personas and the banker archetypes document sit on the same page with no stable-ID links to the catalogue, in a different vocabulary (CRM, next-best action, prototype critic, agent factory), and in places in direct contradiction. The archetypes file names the MD key metric as "time to client action (signal to outreach sent)"; the catalogue repeatedly rejects activity measures and makes deliberate non-action a success signal. The GCB profile is an unfilled template. These documents are solution-shaped and pre-date the intent work; they should be either traced to ACTOR records or marked superseded. As they stand they will leak solution assumptions into whoever reads them next.

**6. Language.** The catalogue prose is dense and abstract: "accepted disposition", "destination job family", "stewardship", "evidential strength", "purposeful next movement". The BUC writing prompt on the same page says "if an MD couldn't read a field aloud in a client meeting without wincing, rewrite it", and prefers "client news" to "intelligence" and "decision" to "disposition". Bankers will validate what they can read. A plain-English pass is needed before any banker-facing validation, and the house-terms list in that prompt is the right tool.

**7. Smaller integrity issues.** Q14 records four answers to a request for three. The pipeline summary and the appendix reference repository paths (`sdd-knowledge-base/...`, `_scratch/...`) that are not here. The appendix exists twice (markdown and flattened plain text) under one title. Scenario evidence citations sometimes point at questions that are only loosely related (SC-PIPE-01-B cites Q14, Q31, Q32, Q74 and Q97, none of which is about pipeline). These are hygiene, not substance.

### Verdict on the mapping

Sound as a structure, over-regular as a model, unquantified as a value chain. The right next moves are to earn the job family record or fold it into the use case, re-cut scenarios to one axis per use case, catalogue or retire the actions job family, reconcile the persona systems, and put ranges on the business outcomes.

## Part 2. Do the interviews validate the model?

### Round 1 (Q01 to Q151) built the model; it did not verify it

Round 1 is an intent-discovery conversation with one person. It was run well for that purpose: skips, rollbacks and supersessions are preserved rather than flattened, the MD was allowed to reject the researcher's compressions (Q40, Q43 withdrawn, Q109 "too detailed"), and every confirmed statement is traceable to the question where it was accepted.

As verification, it has four limits.

**One participant, and the researcher wrote the statements.** All five `Confirmed` JTBDs were drafted by the interviewer and accepted "as written" five times out of five, with zero wording changes. The guide defines `Confirmed` as "validated by the accountable participant group"; the group is one MD. That is acceptance, not validation.

**The open questions were the ones left blank.** Q01 (a good day), Q03 (attention test) and Q139 (a real lost or parked opportunity) are the three questions that would have produced observed behaviour. All three are unanswered. Everything else is a closed list. The result is a model shaped by the option designer, in which the MD's main contribution was selection. The large number of "all of the above" answers (Q05, Q06, Q08, Q11, Q12, Q13, Q36, Q39, Q61, Q62, Q72, Q73, Q75, Q86, Q90, Q101, Q116, Q126) shows that the lists did not discriminate. The model therefore knows what the MD agrees with, but not what the MD would prioritise or what actually happens.

**No observed process.** No tracker, inbox, meeting, note or artifact was walked through. Every "current process and pain" field in the catalogue is marked `[validate]`. The model describes desired progress accurately and current operation not at all.

**Value was never asked in units.** The interview asked what would prove each job family is working (Q77, Q90, Q120, Q149), which is good, but never what a missed window costs, how many senior hours go to reconstruction, or what share of the pipeline is stale. That is why the business outcomes cannot be filled in.

### Round 2 (the proxy guides) is a better instrument, aimed at a different target

The two Market Intelligence Direction guides are well designed. Twelve questions, shared in advance, forced ranking of the strongest two or three, answers tagged as direct experience, observed practice or informed hypothesis, cohort tagging (Common, ECM, DCM, Desk-specific) in the Capital Markets guide, explicit preservation of disagreement, and a synthesis gate that limits banker follow-up to five questions and one episode. Each of these fixes a specific Round 1 weakness.

Three alignment problems remain.

**They do not validate the catalogue.** Both guides narrow one job family (intelligence) to one domain (market intelligence) and extend to a new cohort (ECM/DCM). Neither presents the five JTBDs, the job family boundaries, the use-case steps or the scenarios to anyone. If the aim of the proxy round is to sense-check "that what we have is correct", the current guides will not do it. A third guide is needed: a model-validation instrument that puts the intent model itself in front of proxies.

**Proxies validate plausibility, not practice.** Former bankers and product SMEs can tell you whether a framing is credible and whether a decision list is complete. They cannot tell you how the business operates today. The guides say so, which is right, but it means the "right summary of how the business operates" question cannot be answered by this round at all. It needs current bankers and artifacts.

**The episode is still last.** Both guides put the concrete-episode ask in the synthesis gate, after twelve closed-list questions. Round 1 showed what happens when the open question comes late. The episode should be MI00, before any list.

Two smaller points. The Capital Markets guide reuses the Coverage structure almost one for one and assumes a shared "market-window" job; Q148 already recorded that ECM/DCM lifecycle, confidentiality and stage definitions differ materially, so the "Common" tag should be expected to fail often, and that is useful information if the synthesis treats it that way. And neither guide asks a value question in units.

### Verdict on alignment with the discovery process

Round 1 discovered intent and did so honestly, but it is single-participant, closed-list, statement-acceptance research with no observed episodes and no quantified value. Round 2 is a good direction-setting instrument for market intelligence, but it is not a validation of the model that already exists. The corpus currently has no instrument whose purpose is to test whether the four-job-family catalogue is the right summary of how Coverage operates. Confirmation, breadth, observation and value are the four gaps, in that order of urgency.

## Recommendations, in priority order

1. **Collect three to five concrete episodes before more intent interviews.** Re-ask Q139 with current Line MDs, plus one lost signal (INTEL), one relationship repair (REL) and one consequential meeting (MEET). Walk the artifacts. Use them to convert the catalogue's `[validate]` process fields into evidence, and to test whether the six-step use cases survive contact with a real case.
2. **Write a third proxy guide that validates the model.** Ten questions. Show the five JTBD statements and the job family boundaries, ask proxies to break them (which is wrong, which is missing, which two would they merge), rank the scenarios by frequency and consequence, and ask for one episode first. Run it in the same proxy round.
3. **Raise the bar for `Confirmed`.** Require acceptance by at least two participants, at least one of whom did not take part in drafting. Until then, demote the five JTBDs to `Evidence-backed (single participant)`. The honesty of the catalogue is its asset; this protects it.
4. **Catalogue or retire the actions job family.** Either a full BUC-GIB-ACT-01 chain or a change to every "route to the actions job family" sentence.
5. **Reconcile the persona systems.** Trace the untested profiles and archetypes to ACTOR records or mark them superseded. Remove or contradict the "time to outreach" metric explicitly.
6. **Re-cut the scenarios to one axis per use case** and promote PIPE-A (portfolio session) and PIPE-C (reactivation) to use cases. Move PIPE-E (restricted) to a cross-family controls variation.
7. **Add a value question to every instrument.** Ranges are fine: hours per week reconstructing, number of windows missed per quarter, share of pipeline believed stale. Put ranges into the four business outcomes so they stop being empty.
8. **Run the BUC writing prompt over the catalogue** before anything goes in front of a banker.
9. **Recruit for breadth.** At least three more Coverage MDs across regions and tiers, and one product banker, before claiming the Coverage model is a working model rather than one MD's.

## What is not a problem

The job family architecture (separate job families, cross-links, temporary situation views, no universal object) was tested repeatedly in Round 1 (Q43 to Q63) and survived a rollback. The umbrella statement is correctly kept as orientation rather than a use case. Capacity is correctly deferred. Risk and controls are correctly a triggered guardrail. Non-action as a legitimate outcome is well evidenced. The governance metadata (revision, cutoff, review triggers, supersession links, append-only history) is complete on every record. None of this needs to change.

## Addendum, 2026-10-05 later the same day

The two `ACTOR-*` records cited throughout the catalogue (`ACTOR-COV-SENIOR-MD` revision 2.0 and `ACTOR-COV-PIPELINE-TEAM` revision 1.0) were added to the Figma page after this assessment was written and are now in `catalogue/actors/`. Finding 5 above is therefore half resolved: the catalogue's own actor layer exists and is evidence-backed, with contributor roles for VPs, juniors and product partners still marked `[validate]`. The other half stands: the pre-intent persona material under `reference/` is still untraced to these records and still contradicts them on activity measures. Five job-family-specific proxy guides also arrived after this assessment and are covered in the Round 2 README.

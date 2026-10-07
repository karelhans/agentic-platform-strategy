# IBIQ product use cases mapped onto the Intent Layer

Status: Draft 1.0, 2026-10-07. Scope: the five IBIQ product use-case specs UC-01 to UC-05 (Orient My Day, Investigate Insight, Draft Outreach, Opportunity Validation, Meeting Prep), read against the catalogue as it stands. Owner: `[validate: name the intent model owner]`.

This is a consumer-side mapping, produced under the charter's rules. Nothing here is admitted to the catalogue. Every record proposed below is a **candidate** at `Hypothesis` maturity whose only source is an IBIQ product spec, and the charter is explicit that a product concept is not evidence of a user need. A candidate enters `catalogue/` only after the admission rule in charter section 6 is met: an evidence record, an episode or gap marker, the quality gate, an owner, and the business's language.

## 1. Summary

| IBIQ use case | Primary job family | Business use case and steps | JTBD | Candidate records raised | Litmus verdict |
| --- | --- | --- | --- | --- | --- |
| UC-01 Orient My Day | JF-GIB-INTEL-01, also REL, PIPE, MEET | BUC-GIB-INTEL-01 S1 to S3; value delivered differs | JTBD-GIB-INTEL-01 | BUC-GIB-INTEL-02, SC-GIB-INTEL-01-D, ACTOR-COV-VP | Not aligned; could reach "with conditions" if re-scoped to S1 to S3 with non-action supported |
| UC-02 Investigate Insight | JF-GIB-INTEL-01, also PIPE | BUC-GIB-INTEL-01 S2, S3, S4, S6; the Model stage changes the value delivered | JTBD-GIB-INTEL-01 | BUC-GIB-PIPE-02 (signal to transaction paths), triage-contributor actor | Aligned with conditions |
| UC-03 Draft Outreach | JF-GIB-REL-01, also INTEL, MEET, actions | BUC-GIB-REL-01 S5, S6; value delivered differs | JTBD-GIB-REL-01 | BUC-GIB-REL-02 (Execute A Purposeful Client Engagement), VP actor | Not aligned as written |
| UC-04 Opportunity Validation | JF-GIB-PIPE-01, also INTEL | BUC-GIB-PIPE-01 S1 to S4 and part of S6; same value delivered | JTBD-GIB-PIPE-01 | VP analysis-builder actor, deal-preparation job family | Aligned with conditions |
| UC-05 Meeting Prep | JF-GIB-MEET-01, also INTEL, REL, actions | BUC-GIB-MEET-01 S1 to S3; same value delivered | JTBD-GIB-MEET-01 | ACTOR-COV-MEETING-CONTRIBUTOR | Aligned with conditions |

Three patterns run through all five, and they are findings about the layer as much as about the specs:

1. **The five specs are product use cases, not business use cases.** Each one is a partial run of a catalogued six-step process, usually the preparatory steps, with the senior judgment steps either left to the banker (good) or quietly pre-empted by a score, a threshold or an inferred objective (the recurring litmus test 5 failure).
2. **Two of them expose a missing business use case.** Orient My Day (a daily re-orientation across families) and Draft Outreach (executing a chosen client Engagement) produce a different value delivered from the record they would cite. By the template's own test they are different use cases. That is the first real evidence that a job family holds more than one business use case, which the assessment said the catalogue had not yet earned. It arrives from product reasoning, so it stays a candidate until a banker episode supports it.
3. **Every spec needs an actor the layer does not have.** VP and ED appear in all five as preparers, builders or delegates. `ACTOR-COV-PIPELINE-TEAM` covers VP contribution inside pipeline work only. One candidate actor record for the senior's supporting cohort, with evidence from Round 2, would close this for all five.

The specs' success metrics are the other systematic problem. Of the thirty metrics across the five specs, the mappings label eleven as consequence or quality measures the catalogue would accept, ten as activity or efficiency measures it rejects as primary, and nine as operational or product metrics that are not intent measures at all. Speed-to-action, volume and dry-spell targets appear in four specs and directly worsen named guardrails.

## 2. Candidate records raised by this mapping

IDs were provisional when this table was written. Superseded in part by the model revision of the same day (`proposals/model-revision-2026-10-07.md`): daily re-orientation became scenario SC-GIB-INTEL-01-D rather than a use case, the ID BUC-GIB-INTEL-02 now names the signal-sharing use case, BUC-GIB-PIPE-02 was re-cut without its product-spec steps, and the two actor candidates collapsed into ACTOR-COV-SUPPORT-TEAM.

Where this stands after the catalogue update of 2026-10-07: `BUC-GIB-INTEL-02` (signal-sharing), `BUC-GIB-REL-02`, `BUC-GIB-PIPE-02`, `SC-GIB-INTEL-01-D`, `SC-GIB-MEET-01-E` and `ACTOR-COV-SUPPORT-TEAM` now exist in `catalogue/` as `Candidate` records at revision `0.1`; `SC-GIB-INTEL-01-E` exists as a candidate at `1.0`. The per-use-case mappings below are kept as written; read their candidate IDs through the table above and the catalogue README.

| Candidate | Type | Raised by | One-line definition | Maturity and source |
| --- | --- | --- | --- | --- |
| BUC-GIB-INTEL-02 | Business use case | UC-01 | Daily re-orientation: a senior banker's accepted ordering of which overnight changes will receive judgment today and which are released | `Hypothesis`, IBIQ product spec; must be tested against the Q134 umbrella boundary |
| SC-GIB-INTEL-01-D | Scenario | UC-01 | Periodic re-orientation after an unattended window, with no single triggering signal | `Hypothesis`, IBIQ product spec |
| BUC-GIB-PIPE-02 | Business use case | UC-02 | From a credible signal, set out the plausible transaction paths and judge whether any merits recognition as an opportunity | `Hypothesis`, IBIQ product spec |
| BUC-GIB-REL-02 | Business use case | UC-03 | Execute A Purposeful Client Engagement: one approved, substantive Engagement in the banker's voice, coherent with other JPM Engagement, with its ask and next step owned | `Hypothesis`, IBIQ product spec; Q94 and Q98 give partial support |
| ACTOR-COV-VP (or ACTOR-COV-MEETING-CONTRIBUTOR), now `ACTOR-COV-SUPPORT-TEAM` | Actor | UC-01 to UC-05 | The senior's supporting cohort: VPs and associates who prepare, build out, draft and route on the MD's behalf | `Hypothesis`; ACTOR-COV-PIPELINE-TEAM marks "VP translation" as `[validate]` |
| Deal-preparation job family | Job family | UC-04 | Precedent and counterparty analysis as a standing area of work | `Hypothesis`, IBIQ product spec; no catalogue record of any kind |

Review triggers to raise on existing records, collected from the five mappings: BUC-GIB-INTEL-01 (preparatory contributor `[validate actor]`; evidence that distinct use cases are required), JF-GIB-INTEL-01 (cross-client patterns; entitlement and sensitivity of shared evidence), BUC-GIB-REL-01 (boundary with Interactions and actions), SC-GIB-PIPE-01-D (economics at idea stage), SC-GIB-PIPE-01-E (controls), SC-GIB-PIPE-01-C (watch ownership), BUC-GIB-MEET-01 (trigger width; Interaction contributors), ACTOR-COV-SENIOR-MD (Line MD and ED cohort; cross-LOB handoffs), and the charter's growth-path item 3 (the actions-and-commitments family, which four of the five specs depend on).

## 3. The five mappings

### UC-01 Orient My Day

**One-line reading of the product use case (in business language, no product or feature names):** At the start of the day a senior coverage banker wants everything that may have changed overnight for their clients, sector, markets, opportunities and meetings reduced to a short, personally prioritised picture of what deserves attention first, so that the few consequential items get senior judgment and the rest is released.

**Primary job family:** JF-GIB-INTEL-01 rev 1.0 (why: the spec's TRIAGE / SCAN / PRIORITIZE phases are the family's included work: reduce noise, identify affected context, explain consequence and confidence). **Also touches:** JF-GIB-REL-01 ("dry spell" and engagement recency are the cadence condition of that family), JF-GIB-PIPE-01 (closing windows, milestone shifts), JF-GIB-MEET-01 (meetings needing preparation), and the uncatalogued actions-and-commitments family ("follow-ups due"). Team capacity is deferred intent (Q130) and should not be touched.

**Business use case it serves:** BUC-GIB-INTEL-01 rev 1.0, steps BUC-GIB-INTEL-01-S1 "Reduce noise and duplication", S2 "Identify affected clients and context", S3 "Explain consequence and evidential strength". The value delivered differs: BUC-GIB-INTEL-01 ends in "an accepted disposition, rationale, intended outcome, and destination for potentially consequential intelligence" for one item; UC-01 ends in a prioritised daily picture across four families with no disposition recorded. That is a different unit of value, so a candidate is needed:

- **BUC-GIB-INTEL-02 (candidate)** `Hypothesis`, source "IBIQ product spec, not banker evidence". Value delivered: a senior banker's accepted ordering of which overnight changes across clients, opportunities and meetings will receive judgment today and which are released. Trigger: the start of a working period after a window in which the banker was not watching. Steps: (1) gather what changed since last attention across clients, sector, market and opportunities; (2) remove repetition and the already-known; (3) connect each change to the client, opportunity or meeting it could affect; (4) state consequence, time window and confidence; (5) the banker chooses the few items that get judgment now and releases the rest; (6) chosen items enter BUC-GIB-INTEL-01-S4 or the destination family. Caveat: the Q134 umbrella boundary says no umbrella business use case is implied; this candidate must be tested against that before admission.

**JTBD behind it:** JTBD-GIB-INTEL-01 rev 1.0: "help me isolate consequential change, understand its client-specific implications and evidential strength, and choose the appropriate response and intended outcome". Unwanted trade-off to respect: "unnecessary action, missed consequential change, or repeated manual verification".

**Scenario covered / scenario deliberately not covered:** SC-GIB-INTEL-01-A (short-window signal, via push alerts) / SC-GIB-INTEL-01-C (deliberate non-action: the spec never shows a "nothing today" result). No catalogue scenario fits the routine morning pass with no single trigger; candidate: SC-GIB-INTEL-01-D "Periodic re-orientation after an unattended window" `Hypothesis`.

**Actor and the judgments left with the human:** ACTOR-COV-SENIOR-MD rev 2.0. Kept with the banker: which 1 to 3 items to investigate, whether to draft outreach, prepare a meeting or delegate. Quietly automated although the actor record keeps them senior: "what matters now" and materiality (priority ordering by materiality score and "high-urgency signals requiring immediate response"); which context changes the implication (adjacency-inferred signals, S2); whether cadence warrants Engagement ("dry spell" flags and the <5% dry-spell target, where SC-GIB-REL-01-C says cadence triggers judgment, not a task); and "what needs action TODAY", which pre-empts S4 "decide whether it matters, is credible enough, warrants response".

**Business outcome and measure:** BO-GIB-INTEL-01 rev 1.0 (`Hypothesis`), measure "Consequential surprises" (material changes recognised only after useful response time), downward; guardrails at risk: senior review burden, unnecessary client action. Spec metrics:
- Time to first action <10 min: `activity or efficiency measure`; rewards activity and conflicts with non-action.
- Signal coverage 0% missed material signals: `consequence/quality measure`; nearest proxy to the primary measure, but "material" needs the accepted-disposition definition.
- Engagement cadence <5% dry spells: `activity or efficiency measure`; the catalogue rejects automatic cadence Engagement.
- Adoption >80% of MDs daily: `operational/product metric`.
- Brief generated by 5am: `operational/product metric`.
- Accuracy <5% irrelevant signals: `consequence/quality measure`, usable as the "senior attention on noise" guardrail.

**Solution-language and evidence check:**
- The intent line is the product's own; it cites no BUC, JTBD, BO, SC or ACTOR by ID, failing consumer rule 1.
- Banker need is expressed as surfaces and features (summary brief, audio brief, conversational assistant, dashboard widgets, push, team view) and pipelines (story objects, materiality scores, entity attachments); the template says a description that begins with "click" or "open" is a solution flow.
- The "mental model" and five-question information-needs list rest on `@knowledge:archetype:md` and philosophy pages, which are pre-intent reference material the charter bars as a source; no interview or episode is cited.
- "Orient My Day is the intent" treats a product concept as evidence of need (charter section 2).
- The "relative materiality model" and "signal → judgment → action" loop infer capability support from a job, which rule 5 forbids without an evidence pass.
- Nothing in the spec rests on banker evidence; all claims are product reasoning.

**Gaps and review triggers:**
- Gap: VP cohort has no actor record → raise review trigger on ACTOR-COV-SENIOR-MD / propose candidate ACTOR-COV-VP `Hypothesis`.
- Gap: preparatory triage contributor is `[validate actor]` in BUC-GIB-INTEL-01; the product would play this role → raise review trigger on BUC-GIB-INTEL-01.
- Gap: daily re-orientation has no use case or scenario → propose candidates BUC-GIB-INTEL-02 and SC-GIB-INTEL-01-D above.
- Gap: "follow-ups due" needs the uncatalogued actions-and-commitments family → contribute evidence before build.
- Gap: team capacity and delegation are deferred (Q130) → exclude from scope; do not create a record.
- Gap: cross-client and sector-wide patterns are a "known variation" with no scenario → raise review trigger on JF-GIB-INTEL-01.

**Litmus verdict:** not aligned. Fails 1 (no BO named; its own metrics are activity and product measures), 2 (no JTBD quoted, and "time to first action" contradicts the unwanted trade-off), 3 (no BUC or steps cited, and the value delivered differs from BUC-GIB-INTEL-01). Also fails 4 (no excluded scenario), 5 (materiality and cadence judgments automated), 7 (guardrails unnamed), 8 (non-action never shown as a result), 9 (gaps unlisted). Re-scoped to steps S1 to S3 of BUC-GIB-INTEL-01 with SC-GIB-INTEL-01-C explicitly supported, it could reach "aligned with conditions".

### UC-02 Investigate Insight

**One-line reading of the product use case (in business language, no product or feature names):** When a piece of new information looks as if it could matter, the senior banker checks whether it is real, how large it is, which of their clients and live situations it touches, what outcomes it could lead to, and then decides whether and how to respond.

**Primary job family:** JF-GIB-INTEL-01 (the work is reducing uncertainty around one signal, connecting it to client context, exposing consequence and confidence, and reaching an explicit response: the family's definition verbatim). **Also touches:** JF-GIB-PIPE-01 (the "Model" stage ranks transaction outcomes and sizes fee opportunity, which is early opportunity recognition under SC-GIB-PIPE-01-D "ambiguous early idea", not triage; the spec's own downstream UC-04 confirms the boundary crossing).

**Business use case it serves:** BUC-GIB-INTEL-01 rev 1.0, steps S2 "Identify affected clients and context" (Map Impact), S3 "Explain consequence and evidential strength" (Verify, Size), S4 "Judge the appropriate response" (Decide), and S6 "Route to the destination job family" (exit paths to outreach, meeting, assignment, monitoring). The value delivered, "an accepted disposition, rationale, intended outcome, and destination for potentially consequential intelligence", is unchanged by Verify, Size, Map and Decide. It is changed by Model: generating ranked transaction scenarios with pro-forma financials and firm revenue per path is outside BUC-GIB-INTEL-01's out-of-scope line ("executing ... pipeline stewardship") and produces a different unit of value (a candidate opportunity thesis). Candidate: **BUC-GIB-PIPE-02 (candidate)** `Hypothesis`, source "IBIQ product spec, not banker evidence". Value delivered: a reasoned view of the plausible transaction paths a signal could open and whether any merits recognition as an opportunity. Trigger: a triaged signal is judged credible and material enough that a transaction outcome is plausible. Steps: 1 restate the signal's implication for the affected institutions; 2 recall comparable past situations; 3 set out the plausible paths and who else is likely involved; 4 estimate what each path would mean for the client and for the firm; 5 judge which path, if any, is worth pursuing; 6 hand the view into opportunity stewardship or record deliberate non-pursuit. Note the spec's S5 "Record the disposition and rationale" is only implicit ("thesis/conviction notes"); the spec should name it.

**JTBD behind it:** JTBD-GIB-INTEL-01: "help me isolate consequential change, understand its client-specific implications and evidential strength, and choose the appropriate response and intended outcome". Unwanted trade-offs it must respect: false confidence, unnecessary action, repeated manual verification.

**Scenario covered / scenario deliberately not covered:** Covered: SC-GIB-INTEL-01-B (uncertain high-impact signal; the Verify stage and NC-02/NC-03 match "uncertainty remains explicit"). Partly covered: SC-GIB-INTEL-01-A (the "quick verify" pattern). Deliberately not covered: SC-GIB-INTEL-01-C, deliberate non-action; the spec lists "wait" and "Monitor this" but its success metric (investigation to action rate > 60%) and feedback loop (dismissed signals de-weighted) penalise it, so the spec must state that non-action is a valid conclusive result.

**Actor and the judgments left with the human:** ACTOR-COV-SENIOR-MD rev 2.0. Kept with the banker: whether to respond and which path (NC-01 holds recommendations until Decide), thesis formation, whether to challenge the thesis. Quietly automated although the actor record keeps them human: materiality ("absolute materiality score", "market impact 8.9") and credibility ("confidence 99.2", "verified/unverified") are scored by the system and presented as fact; S4's "is it credible enough for the contemplated use" is a senior judgment, not a threshold. Timing pressure and "recommended actions with timing pressure" pre-empt the response judgment. "ED" and "VP for pre-analysis" are not in any actor record; ACTOR-COV-PIPELINE-TEAM covers VP contribution for pipeline work only, and preparatory triage contributors remain `[validate actor]`.

**Business outcome and measure:** BO-GIB-INTEL-01 (`Hypothesis`), measure "consequential surprises", downward; leading indicator "elapsed time from signal to accepted disposition". Guardrails at risk: senior review burden, unnecessary client action, unsupported use of uncertain evidence. Spec metrics: time from signal to thesis, `activity or efficiency measure` (near the leading indicator but rewards speed over quality; secondary at best); investigation to action rate > 60%, `activity or efficiency measure` (contradicts the non-action guardrail; not acceptable as primary); source coverage > 3 sources, `operational/product metric`; scenario accuracy (banker trust), `consequence/quality measure` (acceptable, needs a definition); return to same signal < 1, `operational/product metric`.

**Solution-language and evidence check:**
- The "Banker's Question" in section 1 is the only need stated in business language; sections 6 to 14 state need as surfaces, tabs, stage steppers, story-object fields and pipeline contracts.
- The five-stage mental model is asserted as the banker's cognition but is a product information architecture; no interview question or episode is cited for it.
- Information needs (section 2) pre-assign sources and data structures (CRM, 13F, precedent database), which is capability mapping the charter says needs its own evidence pass (rule 5).
- Claims that rest on banker evidence: "is it real, how big, who does it affect, what should I do" and "unverified is not irrelevant" align with Q71-Q91 and SC-B. Claims resting only on product reasoning: firm-revenue-per-scenario, conviction ranking, the 60% action target, feedback loop re-weighting by action taken.
- The NC list is the strongest part of the spec and maps directly to the BUC's business rules ("do not imply client action from relevance alone"); keep it and cite the rule.
- Persona is named by title ("Coverage MD / ED") rather than by ACTOR ID and revision.

**Gaps and review triggers:**
- Gap: ED and VP as investigating actors → raise review trigger on ACTOR-COV-SENIOR-MD (Line MD/ED cohort) and on BUC-GIB-INTEL-01 preparatory contributors; propose candidate actor for triage contributors, `Hypothesis`.
- Gap: scenario modelling and fee sizing from a signal → propose candidate BUC-GIB-PIPE-02 above; raise review trigger on BUC-GIB-INTEL-01 "evidence that distinct use cases are required".
- Gap: no observed intelligence episode exists; the spec adds none → spec should contribute Round 2 episodes or declare itself discovery.
- Gap: firm-layer sharing of evidence snapshots across bankers → raise review trigger on JF-GIB-INTEL-01 entitlement and sensitivity rule.
- Gap: materiality and confidence conventions → SC-GIB-INTEL-01-B open question; spec should not fix thresholds before validation.

**Litmus verdict:** aligned with conditions. Test 1: passes only once the spec names BO-GIB-INTEL-01 and its measure; its own metrics are activity measures. Test 3: the Model stage changes the value delivered, so it must be split out as the candidate use case or dropped from UC-02. Test 4: the excluded scenario (SC-GIB-INTEL-01-C) is not stated. Test 5: actor cited by title, and materiality and credibility judgments are partly automated. Test 6: BO is `Hypothesis`, which is allowed only if the outcome is not the sole justification. Test 7: no guardrail watch is stated; the action-rate metric would worsen one. Test 8: non-action is listed as an exit but is penalised by metrics and feedback loop. Test 9: gaps above are not acknowledged in the spec.

### UC-03 Draft Outreach

**One-line reading of the product use case (in business language, no product or feature names):** Once a banker has decided a client should hear from JPM about something that changed, produce a substantive message or talking points in the banker's own voice, aware of what the client has already heard from JPM, that the banker approves and sends, with the Engagement recorded.

**Primary job family:** JF-GIB-REL-01 (why: this is purposeful Engagement executing a chosen Engagement disposition; the family's failure consequences name "duplicate or purposeless outreach", and its controls require client benefit and a credible right to engage). **Also touches:** JF-GIB-INTEL-01 (the trigger is a routed signal; that family explicitly excludes "executing relationship outreach", so UC-03 begins where BUC-GIB-INTEL-01-S6 ends); JF-GIB-MEET-01 (the "follow-up email" and "meeting request" types are BUC-GIB-MEET-01-S6 first follow-through); the uncatalogued actions-and-commitments hypothesis (logging the contact and its ask).

**Business use case it serves:** BUC-GIB-REL-01 rev 1.0, steps S5 "Choose the engagement disposition" (the spec assumes it is already chosen and turns it into a message) and S6 "Review movement and update judgment" (the logged contact feeds the next judgment). The value delivered differs: REL-01 delivers "an accepted relationship-quality judgment, objective, engagement disposition, and owned next movement"; UC-03 delivers a client-ready Engagement. That is a different unit of value, so this is a different use case. Candidate: **BUC-GIB-REL-02 (candidate)** — Execute A Purposeful Client Engagement. `Hypothesis`, source "IBIQ product spec, not banker evidence". Value delivered: one approved, substantive client Engagement in the banker's voice, coherent with other JPM Engagement, with its ask and expected next step owned and recorded. Trigger: an accepted Engagement disposition (from REL S5, INTEL S6 or MEET S6) names this client, an objective and Engagement by message or call. Steps: (1) confirm what changed, why it matters to this person and what outcome is sought (Q98); (2) confirm the right to engage and what must not be said; (3) check what the client has already heard from JPM and sequence with other owners; (4) compose the message and ask in the banker's voice; (5) banker judges tone, message, ask and whether to send at all; (6) send, record the Engagement, and hand the expected next step to its owner.

**JTBD behind it:** JTBD-GIB-REL-01 rev 1.0: "help me judge and strengthen the quality of the relationship using meaningful markers of trust, access, reciprocity, and engagement, informed by what we understand of the client's evolving agenda". Unwanted trade-offs it must respect: purposeless Engagement, client fatigue, duplicated outreach. The spec's own stated progress ("without spending 30 minutes composing") is not a catalogued job and has no banker evidence.

**Scenario covered / scenario deliberately not covered:** SC-GIB-REL-01-B (time-sensitive risk or commitment: signal warrants Engagement while the window narrows) / SC-GIB-REL-01-C (Tier-Based Engagement Frequency Review: "cadence triggers judgment, not automatic purposeless contact"); the spec's "dry spell reduction" metric pulls it into C and must be excluded explicitly. The "introduction request" type edges into SC-GIB-PIPE-01-E and is unaddressed.

**Actor and the judgments left with the human:** ACTOR-COV-SENIOR-MD rev 2.0. Kept with the banker: edit text, choose message versus call brief, explicit copy or send, no auto-send. Quietly automated against Q12 (all six outreach judgments stay with the MD): whether to engage (the trigger assumes Engagement is warranted; "generic outreach detected, prompt to add substance" pushes toward sending rather than not sending); relationship owner (recipient resolved from a coverage list; coordination panel shows others but does not ask who should lead); client objective and ask ("inferred from signal type"); tone and message (learned and set by the system, trained from edits without a consent step); JPM participants (shown, not judged). Spec persona "Coverage MD / ED" and the VP-prepared-draft question have no actor record.

**Business outcome and measure:** BO-GIB-REL-01 rev 1.0, measure "Relationship quality" via markers (candor, access, client-initiated requests, reciprocal commitments, meaningful Engagement pattern), upward. Guardrails it can worsen: client fatigue, purposeless Engagement, activity volume mistaken for quality. Spec metrics:
- Time from signal to copied outreach: `activity or efficiency measure`.
- Draft acceptance rate: `operational/product metric`.
- Outreach volume +40%: `activity or efficiency measure`; directly worsens the guardrails.
- Generic outreach rate: `consequence/quality measure` (secondary; "generic" is system-defined).
- Client response rate: `consequence/quality measure` (closest to the markers; acceptable primary).
- Dry spell reduction: `activity or efficiency measure`; contradicts SC-GIB-REL-01-C and Q33.
- "One bank" duplicate outreach: `consequence/quality measure` (guardrail; duplicated outreach is a named failure consequence).

**Solution-language and evidence check:**
- The "banker's question" is framed as composing speed; the catalogued need (Q97-Q98) is clarity on what changed, what matters to this person, outcome, boundaries and next step before engaging.
- Sections 2, 7, 8, 10 express need as data objects, memory layers, pipelines, tabs and a conversational shell; the only business-language content is the Q98-shaped "hook, framing, ask".
- "Current state: 20-30 minutes crafting outreach" and "<3 minutes" rest on no banker evidence; no interview question measures composition effort.
- "One bank" visibility has banker evidence: Q94 names coordination and follow-through failures and BUC-GIB-REL-01's exception "another JPM team plans engagement". This is the strongest-evidenced claim in the spec.
- Tone learning, anti-pattern detection and engagement-score-driven warmth are product reasoning; Q12 says tone and message remain MD judgment.
- The `@knowledge` references are product philosophy, not evidence records.

**Gaps and review triggers:**
- Gap: no business use case for executing a client Engagement → propose candidate BUC-GIB-REL-02; raise review trigger on BUC-GIB-REL-01 (boundary with Interactions and actions).
- Gap: Engagement logging and follow-through ownership → actions-and-commitments family is a working hypothesis only (Q122); CACT11 asks whether drafting communications for review is permitted; raise review trigger on charter scope row.
- Gap: VP/ED actor for delegated drafting → propose candidate ACTOR for VP translation, cited in ACTOR-COV-PIPELINE-TEAM as `[validate]`.
- Gap: other-LOB bankers as coordination participants → no actor; raise review trigger on ACTOR-COV-SENIOR-MD handoffs.
- Gap: post-Interaction follow-up as a variation → raise review trigger on BUC-GIB-MEET-01-S6 boundary.

**Litmus verdict:** not aligned as written. Test 1: no BO cited and its own primary measures are volume and speed. Test 3: the value delivered differs from BUC-GIB-REL-01. Test 4: no scenario named; cadence scenario is implicitly included. Test 5: four of Q12's six MD judgments are inferred or learned. Test 6: candidate BUC and actor are Hypothesis, so this is a discovery exercise and must say so. Test 7: volume and dry-spell targets worsen named guardrails with no watch. Test 8: no deliberate "do not send" result exists; generic-outreach detection manufactures activity. Test 9: VP, cross-LOB and actions gaps unlisted.

### UC-04 Opportunity Validation

**One-line reading of the product use case (in business language, no product or feature names):** A senior banker who senses a possible transaction assembles the evidence, sizes the prize, has the thesis argued against, and decides to pursue, park or drop it before franchise effort is spent or the client is approached.

**Primary job family:** JF-GIB-PIPE-01 (recognise a plausible idea, assemble evidence and views, challenge maturity and trajectory, then advance, park or exit; the spec's five stages are this family's included work). **Also touches:** JF-GIB-INTEL-01 (the "is the opportunity real?" question and the signal-to-hypothesis handoff are BUC-GIB-INTEL-01 S3-S6; the spec consumes that output rather than redoing it).

**Business use case it serves:** BUC-GIB-PIPE-01 rev 2.0, steps S1 "Recognize an opportunity or review trigger", S2 "Assemble current evidence and legitimate views", S3 "Challenge maturity and trajectory", S4 "Choose the stewardship response", and part of S6 "Update the shared picture and review conditions" (the commit record). It does not touch S5 "Confirm accountable stewardship and next movement": no accountable owner or next client outcome is produced. The value delivered ("a shared, challenge-tested opportunity judgment with accountable stewardship and purposeful next movement or deliberate parking or exit") is the same in substance: a challenge-tested judgment ending in deliberate progress, park or exit. No candidate BUC is needed; this is a partial run of BUC-GIB-PIPE-01 that produces one banker's thesis rather than the shared, owned judgment, which is a condition, not a different value.

**JTBD behind it:** JTBD-GIB-PIPE-01 rev 2.0: "help me maintain disciplined stewardship through clear accountability, purposeful movement, regular challenge, and deliberate parking or exit". The spec honours "regular challenge" and "deliberate parking or exit"; it is silent on "clear accountability" and partly contradicts the unwanted trade-off "false precision" by producing a conviction percentage and fee range at idea stage.

**Scenario covered / scenario deliberately not covered:** SC-GIB-PIPE-01-D (ambiguous early idea) is what the spec describes, but D's rule "do not require forced probability, speculative economics" conflicts with the sizing stage, so coverage is conditional. SC-GIB-PIPE-01-B (material change or closing window) is also covered when the trigger is a catalyst. Deliberately not covered: SC-GIB-PIPE-01-A (recurring portfolio session; the spec is single-opportunity) and SC-GIB-PIPE-01-E (restricted cross-GIB; the conflict check gestures at it but entitlement handling is undefined).

**Actor and the judgments left with the human:** ACTOR-COV-SENIOR-MD rev 2.0 (thesis owner) and ACTOR-COV-PIPELINE-TEAM rev 1.0 (build-out). Kept with the banker: commit, park or kill (NC-01); defend or concede each challenge; override the probability estimate; authoring the thesis statement. Quietly automated although the actor record keeps them senior: "System adjusts conviction level based on how thesis held up" (§7 step 5, AC-07) and the composite AI probability default both pre-empt the MD's "opportunity judgment"; "Kill → de-weights similar signals" automates the materiality judgment that JTBD-GIB-INTEL-01 reserves to the MD; the system-assembled "JPM angle" with a relationship score substitutes for the MD's institution-level relationship judgment (JTBD-GIB-REL-01). VP role: the spec gives a VP distinct build and routing responsibility. ACTOR-COV-PIPELINE-TEAM includes VPs only as a `[validate]` internal variation ("VP translation and quality control"); it does not evidence a VP analysis-builder role, and "ED" appears in no record.

**Business outcome and measure:** BO-GIB-PIPE-01 rev 1.0 (`Hypothesis`), measure "Portfolio accuracy": agreement between the accepted stage-appropriate assessment and the eventual observed state, upward. Spec metrics:
- Opportunity → mandate conversion >25%: `consequence/quality measure`, but watch guardrail "viable ideas excluded before appropriate challenge".
- Time to validated thesis <2 hours: `activity or efficiency measure`.
- Challenger engagement rate >70%: `operational/product metric` (feature adoption).
- Conviction accuracy (committed-high-conviction win rate > parked rate): `consequence/quality measure`; closest to portfolio accuracy.
- Wasted-pursuit reduction <15% killed post-commit: `consequence/quality measure`, usable as a guardrail; must not penalise deliberate exit.
- Fee capture: `consequence/quality measure` in kind, but outside the BO contract and causally unproven; secondary at best.

**Solution-language and evidence check:**
- Entry points, consumption patterns and §12 describe tabs, CTAs, a conversational shell and a "challenger agent"; the banker need under them is "challenge the trajectory before further effort", which BUC-GIB-PIPE-01 S3 already states in business terms with human challengers (MD, owner, business heads).
- §6 and §13 name data feeds and systems (Dealogic, DASH, Dealworks, C360, News-Insight); the layer's guardrail moves these to a capability map.
- The "current state" claim (bankers chase weak ideas or sit on them) cites no banker evidence; the only sources are product philosophy and archetype notes, which the charter says are not evidence of need.
- Catalogue evidence (Q113-Q117, Q146-Q147) supports the trigger "an opportunity requires challenge before further effort" and plural early views, so the core need is evidence-backed; sizing, fee and probability at idea stage rest on product reasoning only and run against SC-GIB-PIPE-01-D's rules and the BUC's "avoid forced probability".
- Precedent and counterparty mapping is deal-preparation work with no catalogue record; the template's BUC-MA-01 is a worked example, not a record.

**Gaps and review triggers:**
- Gap: VP (and ED) as an analysis-builder with routing authority → raise review trigger on ACTOR-COV-PIPELINE-TEAM / propose candidate actor, `Hypothesis`.
- Gap: quantified economics at idea stage → raise review trigger on SC-GIB-PIPE-01-D (economics rule) and BUC-GIB-PIPE-01 S2.
- Gap: precedent and counterparty analysis → propose candidate job family for deal preparation, `Hypothesis`, source "IBIQ product spec, not banker evidence".
- Gap: conflict and MNPI checks → raise review trigger on SC-GIB-PIPE-01-E controls validation.
- Gap: parked-opportunity monitoring and expiry → raise review trigger on SC-GIB-PIPE-01-C watch ownership.
- Gap: a signal-weighting feedback loop from kills → no record; propose candidate scenario under BUC-GIB-INTEL-01, `Hypothesis`.

**Litmus verdict:** aligned with conditions. Tests 1-3 pass once the spec adopts the citations above (it names none itself). Failing: 4, the sizing stage contradicts the covered scenario's rules; 5, the VP role and the automatic conviction adjustment are not supported by an actor record; 7, no guardrail is stated although false precision and premature exclusion are directly at risk; 8, park and kill are supported but kill-driven signal de-weighting manufactures a judgment the layer keeps human; 9, the spec lists no gaps or evidence it will contribute.

### UC-05 Meeting Prep

**One-line reading of the product use case (in business language, no product or feature names):** Before a client meeting, the banker receives an assembled view of what has changed, what was said and promised last time, what is open, who is in the room and what to avoid, so that preparation shrinks to a short scan and the banker's effort goes into judging what to raise.

**Primary job family:** JF-GIB-MEET-01 rev 1.0 (the work is the preparation half of high-stakes client Interactions: establish why now, form the hypothesis, align posture, resolve what to avoid). **Also touches:** JF-GIB-INTEL-01 rev 1.0 ("since last meeting" signals are routed intelligence consumed at its destination), JF-GIB-REL-01 rev 1.0 (attendee and relationship-quality context), and the uncatalogued actions-and-commitments family (pending actions from the prior meeting).

**Business use case it serves:** BUC-GIB-MEET-01 rev 1.0, steps `S1` "Establish why this interaction matters now", `S2` "Form the client hypothesis and intended outcome", `S3` "Align JPM posture and resolve critical uncertainty". It does not touch S4 to S6. The value delivered ("an interpreted consequential client-interaction outcome with explicit commitments, affected intent job families updated, and first follow-through initiated") is unchanged: the product use case produces S3's intermediate state, "aligned posture and acceptable readiness", not a new value. No candidate BUC is proposed. Two cautions: the spec's trigger ("any calendar meeting with a covered client", including social and routine recurring meetings) is wider than the BUC trigger (a consequential window) and the BUC excludes "routine scheduling, hosting"; and the BUC's own review trigger, "evidence that preparation and conversion are separate use cases", must not be fired by a product concept.

**JTBD behind it:** JTBD-GIB-MEET-01 rev 1.0, confirmed by one participant, treated as evidence-backed: "help me enter with a grounded hypothesis, timely context, aligned JPM posture, and critical uncertainty resolved". Unwanted trade-offs to respect: "generic preparation ... false confidence ... post-meeting administrative burden without progress".

**Scenario covered / scenario deliberately not covered:** SC-GIB-MEET-01-A (forming client decision: the spec's deal-related and crisis emphases sit here) / SC-GIB-MEET-01-B (relationship-sensitive listening or repair: that record warns "over-prepared advocacy may worsen trust", which action-oriented talking points would contradict; the spec should exclude it explicitly). SC-GIB-MEET-01-C is only partly served: the VP flow is delegation, not cross-JPM participant alignment.

**Actor and the judgments left with the human:** ACTOR-COV-SENIOR-MD rev 2.0. Kept with the banker: which points to raise or avoid, how to use the material in the room, whether to review at all (NC-04, "prep is a service, not a gate"). Quietly automated: S1's judgment "decide whether the interaction is consequential and what senior involvement is warranted" is replaced by a calendar-plus-coverage-list rule; S2's judgment "what should be learned, influenced, protected, repaired, advanced, or deliberately deferred" is pre-filled as an inferred objective and generated talking points; a numeric relationship score contradicts the actor's need to judge quality "without false precision" (BUC-GIB-REL-01 S2). The VP preparing on behalf of the MD is not covered by any actor record: BUC-GIB-MEET-01 lists "meeting contributors `[validate actor]`", and ACTOR-COV-PIPELINE-TEAM mentions VP translation only inside pipeline work. The spec's "ED" persona is also uncovered.

**Business outcome and measure:** BO-GIB-MEET-01 rev 1.0 (`Hypothesis`). Measure moved: the leading indicator "grounded hypothesis before the meeting; aligned JPM posture", feeding the primary measure "proportion of in-scope meetings with an accepted interpreted outcome and initiated next movement". Guardrails at risk: preparation effort, unsupported conclusions, confidentiality or conduct incidents. Spec metrics:
- Prep usage rate: `operational/product metric`.
- Time spent on prep: `activity or efficiency measure`; usable as the "preparation effort" guardrail only.
- Talking point utilization: `activity or efficiency measure`; rewards raising suggestions, which the BO caveat ("do not reward ... forced commitments") warns against.
- Meeting outcome quality: `consequence/quality measure` in intent, but its proxy "capture richness" is a volume proxy; redefine as accepted interpreted outcome.
- Prior outcome continuity: `operational/product metric` as written ("system surfaces prior context"); the intent measure behind it is the guardrail "unowned commitments".
- VP prep delegation success: `operational/product metric`.

**Solution-language and evidence check:**
- The information needs (section 2) are stated as data sources and pipelines; the banker need behind each is only in the italic question.
- "Zero effort" and "10 to 15 minutes manual assembly" rest on no banker evidence; the catalogue's own pain field for this BUC is `[validate]`.
- All @knowledge references are IBIQ philosophy and archetype material, the pre-intent `reference/` class the charter bars as a source until traced.
- Meeting-type adaptation (first, recurring, social, crisis) is product reasoning; the catalogue's variations are decision-forming, listening/repair and cross-JPM.
- NC-03 (no generic talking points) and NC-02 (no restricted content) do honour the JTBD trade-off and controls; credit where due.
- The worked example (named client, score 87) is illustrative, not an observed episode; the BUC still lacks one.

**Gaps and review triggers:**
- Gap: VP or meeting-contributor cohort preparing on behalf of the MD → propose candidate `ACTOR-COV-MEETING-CONTRIBUTOR` (`Hypothesis`) / raise review trigger on BUC-GIB-MEET-01 "meeting contributors `[validate actor]`".
- Gap: routine, social and first-contact meetings sit outside the consequential trigger → raise review trigger on BUC-GIB-MEET-01 trigger and population; do not widen without evidence.
- Gap: pending-action continuity depends on the uncatalogued actions-and-commitments family → raise review trigger on the charter's growth-path item 3.
- Gap: ED cohort → no actor record; mark as borrowed from ACTOR-COV-SENIOR-MD.
- Gap: BO-GIB-MEET-01 has no baseline or target → the spec's "current state" figures are not admissible as a baseline.

**Litmus verdict:** aligned with conditions. Tests 1 to 3 pass. Failing: 4 (no SC-* named; covered and excluded scenarios must be stated); 5 (VP actor missing; S1/S2 consequence and hypothesis judgments are automated rather than left with the human); 6 (BO-GIB-MEET-01 is `Hypothesis`; JTBD is single-participant; without a discovery label the build cannot rest on them); 7 (no guardrail stated; preparation effort and unsupported conclusions need a watch); 8 (auto-generating for every meeting and action-oriented points manufactures activity; deliberate deferral and listening-only Interactions are unsupported); 9 (no gap list; the VP cohort, routine-meeting scenario and actions family are needed and unstated).

## 4. What IBIQ should do with this

1. Add the citations. Each spec names no record by ID today. Sections 4 to 6 of the consumer guide give the shape.
2. Split the two specs whose value delivered differs. Orient My Day becomes a product use case serving BUC-GIB-INTEL-01 steps 1 to 3 plus a candidate BUC-GIB-INTEL-02; Draft Outreach cites candidate BUC-GIB-REL-02 and declares itself a discovery exercise until that record is evidence-backed.
3. Hand the judgments back. Materiality, credibility, "what needs action today", conviction adjustment and cadence-triggered Engagement are senior judgments in the actor record; the product may prepare them, not make them.
4. Replace the primary metrics. Keep the eleven consequence and quality measures, move speed and volume targets to guardrails or drop them, and take baselines from the business outcomes once ranges exist.
5. Contribute evidence. Each spec should bring one observed banker episode to Round 2; that is what moves a candidate from `Hypothesis` to `Evidence-backed`.

## Revision history

| Revision | Date | Change | Accepted by |
| --- | --- | --- | --- |
| `1.0` draft | 2026-10-07 | First mapping of IBIQ UC-01 to UC-05 against the catalogue. Six candidate records raised; none admitted. | `[validate]` |

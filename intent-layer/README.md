# IB Intent Layer

Single source of truth for what drives IB and GCB decision making: business outcomes, job families, business use cases, JTBDs, scenarios, and the evidence behind them. New here? Read [`START-HERE.md`](START-HERE.md), one page on how a researcher, designer or product manager frames work against the layer. Then [`CHARTER.md`](CHARTER.md) for the rules in full. The audit of the current content is in [`ASSESSMENT.md`](ASSESSMENT.md).

## Layout

| Folder | Holds |
| --- | --- |
| [`catalogue/`](catalogue/) | Governed intent records with stable IDs: business outcomes, job families, business use cases, JTBDs, actors, scenarios. |
| [`evidence/`](evidence/) | What the records rest on: the confirmed-intent synthesis and the interview rounds. |
| [`templates/`](templates/) | The generation guide and one template per artifact type. |
| [`prompts/`](prompts/) | Writing prompts used to produce records in the business's language. |
| [`intent-layer-explained.html`](intent-layer-explained.html) | Visual explainer for people new to SDD: where the layer sits, one record chain, maturity, the litmus test. Open in a browser. |
| [`consumers/`](consumers/) | Guides for workspaces that consume the layer. One per consumer: what to cite, what to own, what to rename. First: [IBIQ product definition](consumers/ibiq-product-definition.md), with the [use-case mapping](consumers/ibiq-use-case-mapping.md) and the [job family example](consumers/job-family-example.html). |
| [`proposals/`](proposals/) | Proposed changes to the catalogue, tested but not admitted. First: the [model revision](proposals/model-revision-2026-10-07.md) that tests every job and use case candidate. |
| [`reference/`](reference/) | Pre-intent persona material (untested user profiles, personas, banker archetypes). Not a generation source until traced to actor records or marked superseded; see the charter. |

**Terminology.** The word "lens" was used in early drafts for what the catalogue calls a job family. It is retired; only the Round 1 evidence keeps it, verbatim, as the participants' own language.

## Provenance

The content was ingested verbatim from the Figma page **Interview questions + Value stream** (page id `2:4903`) of the *Personas* file:
https://www.figma.com/design/MSgO39AA9b3RA8qkeuBhD1/Personas?node-id=2-4903

Each Figma text layer became one file. Content is copied as-is (including typos in recorded interview answers); only the frame heading `Untested User Profiles` was expanded into a short README. Folders mirror the relative links inside the catalogue records (`../business-outcomes/...`, `../../evidence/...`, `../templates/...`) so those links resolve locally.

Note: the full interview appendix exists twice on the page, once as Markdown and once as plain text; both are kept. The BUC writing prompt layer contains its text twice in Figma and is kept verbatim.


## Two interview rounds, kept separate

| | Round 1 | Round 2 |
| --- | --- | --- |
| Folder | [`evidence/interviews/round-1-discovery-interview/`](evidence/interviews/round-1-discovery-interview/) | [`evidence/interviews/round-2-product-proxy-interviews/`](evidence/interviews/round-2-product-proxy-interviews/) |
| What it is | The historical discovery mega-interview with one Senior Coverage MD (Q01 to Q151, 2026-09-23 to 2026-10-02). It produced the five JTBDs and the whole catalogue. | Eight product-ready proxy-interview guides (status Draft): one whole-model validation guide, five job family guides (intelligence, relationships, pipeline, meetings, actions), and two Market Intelligence Direction guides (Coverage, Capital Markets). |
| Status | Complete. Treat as a research record, not a reusable instrument. | Not yet run. First to be run with Product Proxies as a sense check before going to bankers. |
| Output | Confirmed intent statements in [`evidence/`](evidence/) and governed records in [`catalogue/`](catalogue/). | Candidate direction and a short banker-validation question set (see each guide's synthesis gate). |

Do not mix the two. Round 1 questions were exploratory and many were skipped, reopened or superseded; Round 2 questions are the ones to put in front of people.

## File index by Figma layer

Known dangling links inside the ingested content, inherited from the source and not yet present on the Figma page: `evidence/coverage-senior-md/pipeline-capability-contributions.md`, and repository paths referenced by the banker archetypes file. The two `ACTOR-*` records arrived on the Figma page after the first ingest and are now in `catalogue/actors/`. The eighteen records added by the model revision of 2026-10-07 (candidates and new scenarios) were written back to the same Figma section as new text layers; their ids are in the table below, and the section now carries an extra column for the candidate actions family. The actor template exists twice on the Figma page (`2:5638` and `36:1082`, identical); one copy is kept.

| File | Figma layer | Title | Chars |
| --- | --- | --- | --- |
| [README.md](README.md) | `27:616` | IB Intent Layer (index; the Figma copy omits this file table) | 18704 |
| [CHARTER.md](CHARTER.md) | `27:617` | IB Intent Layer Charter | 10953 |
| [ASSESSMENT.md](ASSESSMENT.md) | `29:615` | Audit and assessment of the Interview questions + Value stream corpus | 17370 |
| [evidence/interviews/round-1-discovery-interview/README.md](evidence/interviews/round-1-discovery-interview/README.md) | `27:618` | Round 1: discovery mega-interview (historical record) | 1088 |
| [evidence/interviews/round-2-product-proxy-interviews/README.md](evidence/interviews/round-2-product-proxy-interviews/README.md) | `28:615` | Round 2: product-proxy sense-check interviews | 3912 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-intent-model-validation-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-intent-model-validation-proxy-interview.md) | `28:616` | Coverage Intent Model Validation - Proxy Interview | 21672 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-actions-and-commitments-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-actions-and-commitments-proxy-interview.md) | `19:6325` | Coverage Actions And Commitments - Proxy Interview | 12073 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-consequential-client-meetings-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-consequential-client-meetings-proxy-interview.md) | `19:6326` | Coverage Consequential Client Meetings - Proxy Interview | 11094 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-consequential-intelligence-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-consequential-intelligence-proxy-interview.md) | `19:6327` | Coverage Consequential Intelligence - Proxy Interview | 11574 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-pipeline-stewardship-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-pipeline-stewardship-proxy-interview.md) | `19:6328` | Coverage Pipeline Stewardship - Proxy Interview | 11041 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-relationship-management-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-relationship-management-proxy-interview.md) | `19:6329` | Coverage Relationship Management - Proxy Interview | 11166 |
| [consumers/ibiq-product-definition.md](consumers/ibiq-product-definition.md) | `76:615`; native frames `78:616` (page IBIQ · Consumer Guide) | Consumer guide: IBIQ product definition on the Intent Layer | 11403 |
| [consumers/ibiq-use-case-mapping.md](consumers/ibiq-use-case-mapping.md) | `82:615` (page IBIQ · Consumer Guide) | IBIQ product use cases UC-01 to UC-05 mapped onto the Intent Layer; six candidate records, none admitted | 45356 |
| [consumers/job-family-example.html](consumers/job-family-example.html) | `80:616` (page Job Family · Example) | What a full job family looks like: generic shape and the intelligence family with the IBIQ use cases mapped on | 33553 |
| [proposals/model-revision-2026-10-07.md](proposals/model-revision-2026-10-07.md) | page Model Revision (main body only) | Every job and use case candidate tested: six jobs, nine use cases, two retirements, one control rule | 79798 |
| [reference/README.md](reference/README.md) | `27:619` | Reference: pre-intent persona material | 807 |
| [catalogue/README.md](catalogue/README.md) | `2:5637` | Intent Catalogue | 12547 |
| [catalogue/actors/ACTOR-COV-SENIOR-MD.md](catalogue/actors/ACTOR-COV-SENIOR-MD.md) | `36:1081` | ACTOR-COV-SENIOR-MD - Senior Coverage MD | 8732 |
| [catalogue/actors/ACTOR-COV-PIPELINE-TEAM.md](catalogue/actors/ACTOR-COV-PIPELINE-TEAM.md) | `36:1080` | ACTOR-COV-PIPELINE-TEAM - Coverage Opportunity Team | 6995 |
| [catalogue/actors/ACTOR-COV-SUPPORT-TEAM.md](catalogue/actors/ACTOR-COV-SUPPORT-TEAM.md) | `105:6` | ACTOR-COV-SUPPORT-TEAM - Coverage Supporting Cohort (candidate) | 10434 |
| [catalogue/business-outcomes/BO-GIB-INTEL-01.md](catalogue/business-outcomes/BO-GIB-INTEL-01.md) | `2:5604` | BO-GIB-INTEL-01 - Improve Consequential Intelligence Response | 3795 |
| [catalogue/business-outcomes/BO-GIB-MEET-01.md](catalogue/business-outcomes/BO-GIB-MEET-01.md) | `2:5607` | BO-GIB-MEET-01 - Improve Consequential Client Interaction Outcomes | 3795 |
| [catalogue/business-outcomes/BO-GIB-PIPE-01.md](catalogue/business-outcomes/BO-GIB-PIPE-01.md) | `2:5606` | BO-GIB-PIPE-01 - Improve Opportunity Portfolio Accuracy | 5864 |
| [catalogue/business-outcomes/BO-GIB-REL-01.md](catalogue/business-outcomes/BO-GIB-REL-01.md) | `2:5605` | BO-GIB-REL-01 - Strengthen Priority Client Relationship Quality | 4145 |
| [catalogue/business-use-cases/BUC-GIB-INTEL-01.md](catalogue/business-use-cases/BUC-GIB-INTEL-01.md) | `2:5608` | BUC-GIB-INTEL-01 - Triage And Route Consequential Intelligence | 12731 |
| [catalogue/business-use-cases/BUC-GIB-MEET-01.md](catalogue/business-use-cases/BUC-GIB-MEET-01.md) | `2:5611` | BUC-GIB-MEET-01 - Prepare, Conduct, And Convert A Consequential Client Meeting | 14622 |
| [catalogue/business-use-cases/BUC-GIB-PIPE-01.md](catalogue/business-use-cases/BUC-GIB-PIPE-01.md) | `2:5610` | BUC-GIB-PIPE-01 - Review And Direct Priority Opportunities | 15157 |
| [catalogue/business-use-cases/BUC-GIB-REL-01.md](catalogue/business-use-cases/BUC-GIB-REL-01.md) | `2:5609` | BUC-GIB-REL-01 - Review And Direct A Priority Client Relationship | 12510 |
| [catalogue/business-use-cases/BUC-GIB-ACT-01.md](catalogue/business-use-cases/BUC-GIB-ACT-01.md) | `107:4` | BUC-GIB-ACT-01 - Resolve A Commitment That Is Drifting Or Waiting On The Senior (candidate) | 12817 |
| [catalogue/business-use-cases/BUC-GIB-INTEL-02.md](catalogue/business-use-cases/BUC-GIB-INTEL-02.md) | `103:3` | BUC-GIB-INTEL-02 - Bring A Held Signal To Its Accountable Owner (candidate) | 11267 |
| [catalogue/business-use-cases/BUC-GIB-PIPE-02.md](catalogue/business-use-cases/BUC-GIB-PIPE-02.md) | `104:3` | BUC-GIB-PIPE-02 - Recognise An Idea As An Opportunity (candidate) | 13210 |
| [catalogue/business-use-cases/BUC-GIB-PIPE-03.md](catalogue/business-use-cases/BUC-GIB-PIPE-03.md) | `104:4` | BUC-GIB-PIPE-03 - Review The Portfolio And Redirect Effort (candidate) | 12505 |
| [catalogue/business-use-cases/BUC-GIB-REL-02.md](catalogue/business-use-cases/BUC-GIB-REL-02.md) | `103:6` | BUC-GIB-REL-02 - Execute A Purposeful Client Contact (candidate) | 14165 |
| [catalogue/job-families/JF-GIB-INTEL-01.md](catalogue/job-families/JF-GIB-INTEL-01.md) | `2:5612` | JF-GIB-INTEL-01 - Intelligence Triage | 5942 |
| [catalogue/job-families/JF-GIB-MEET-01.md](catalogue/job-families/JF-GIB-MEET-01.md) | `2:5615` | JF-GIB-MEET-01 - Consequential Client Meetings | 6935 |
| [catalogue/job-families/JF-GIB-PIPE-01.md](catalogue/job-families/JF-GIB-PIPE-01.md) | `2:5614` | JF-GIB-PIPE-01 - Opportunity Pipeline Stewardship | 8501 |
| [catalogue/job-families/JF-GIB-REL-01.md](catalogue/job-families/JF-GIB-REL-01.md) | `2:5613` | JF-GIB-REL-01 - Client Relationship Management | 7600 |
| [catalogue/job-families/JF-GIB-ACT-01.md](catalogue/job-families/JF-GIB-ACT-01.md) | `107:2` | JF-GIB-ACT-01 - Actions And Commitments (candidate) | 8590 |
| [catalogue/jtbd/JTBD-GIB-INTEL-01.md](catalogue/jtbd/JTBD-GIB-INTEL-01.md) | `2:5616` | JTBD-GIB-INTEL-01 - Isolate And Route Consequential Intelligence | 3878 |
| [catalogue/jtbd/JTBD-GIB-MEET-01.md](catalogue/jtbd/JTBD-GIB-MEET-01.md) | `2:5619` | JTBD-GIB-MEET-01 - Convert Consequential Client Interactions Into Progress | 5344 |
| [catalogue/jtbd/JTBD-GIB-PIPE-01.md](catalogue/jtbd/JTBD-GIB-PIPE-01.md) | `2:5618` | JTBD-GIB-PIPE-01 - Maintain Disciplined Opportunity Stewardship | 5769 |
| [catalogue/jtbd/JTBD-GIB-REL-01.md](catalogue/jtbd/JTBD-GIB-REL-01.md) | `2:5617` | JTBD-GIB-REL-01 - Strengthen Priority Client Relationships | 4791 |
| [catalogue/jtbd/JTBD-GIB-ACT-01.md](catalogue/jtbd/JTBD-GIB-ACT-01.md) | `107:3` | JTBD-GIB-ACT-01 - Translate Intent Into Accepted Ownership And Explicit Commitment (candidate) | 7246 |
| [catalogue/jtbd/JTBD-GIB-INTEL-02.md](catalogue/jtbd/JTBD-GIB-INTEL-02.md) | `103:2` | JTBD-GIB-INTEL-02 - Bring Held Information To Its Accountable Owner (candidate) | 4768 |
| [catalogue/scenarios/SC-GIB-INTEL-01-A.md](catalogue/scenarios/SC-GIB-INTEL-01-A.md) | `2:5636` | SC-GIB-INTEL-01-A - Short-Window Consequential Signal | 4006 |
| [catalogue/scenarios/SC-GIB-INTEL-01-B.md](catalogue/scenarios/SC-GIB-INTEL-01-B.md) | `2:5635` | SC-GIB-INTEL-01-B - Uncertain High-Impact Signal | 3974 |
| [catalogue/scenarios/SC-GIB-INTEL-01-C.md](catalogue/scenarios/SC-GIB-INTEL-01-C.md) | `2:5634` | SC-GIB-INTEL-01-C - Deliberate Non-Action Or Monitoring | 3843 |
| [catalogue/scenarios/SC-GIB-MEET-01-A.md](catalogue/scenarios/SC-GIB-MEET-01-A.md) | `2:5633` | SC-GIB-MEET-01-A - Forming Client Decision | 3639 |
| [catalogue/scenarios/SC-GIB-MEET-01-B.md](catalogue/scenarios/SC-GIB-MEET-01-B.md) | `2:5632` | SC-GIB-MEET-01-B - Relationship-Sensitive Listening Or Repair | 3743 |
| [catalogue/scenarios/SC-GIB-MEET-01-C.md](catalogue/scenarios/SC-GIB-MEET-01-C.md) | `2:5631` | SC-GIB-MEET-01-C - Major Commitment Or Cross-JPM Meeting | 4753 |
| [catalogue/scenarios/SC-GIB-PIPE-01-A.md](catalogue/scenarios/SC-GIB-PIPE-01-A.md) | `2:5630` | SC-GIB-PIPE-01-A - Recurring Pipeline Management Session | 4987 |
| [catalogue/scenarios/SC-GIB-PIPE-01-B.md](catalogue/scenarios/SC-GIB-PIPE-01-B.md) | `2:5629` | SC-GIB-PIPE-01-B - Material Change Or Closing Decision Window | 4508 |
| [catalogue/scenarios/SC-GIB-PIPE-01-C.md](catalogue/scenarios/SC-GIB-PIPE-01-C.md) | `2:5628` | SC-GIB-PIPE-01-C - Parked Opportunity Reactivation | 4310 |
| [catalogue/scenarios/SC-GIB-PIPE-01-D.md](catalogue/scenarios/SC-GIB-PIPE-01-D.md) | `2:5627` | SC-GIB-PIPE-01-D - Ambiguous Early Idea | 4879 |
| [catalogue/scenarios/SC-GIB-PIPE-01-E.md](catalogue/scenarios/SC-GIB-PIPE-01-E.md) | `2:5626` | SC-GIB-PIPE-01-E - Restricted Cross-GIB Opportunity | 5798 |
| [catalogue/scenarios/SC-GIB-REL-01-A.md](catalogue/scenarios/SC-GIB-REL-01-A.md) | `2:5625` | SC-GIB-REL-01-A - Institution Relationship Review | 5580 |
| [catalogue/scenarios/SC-GIB-REL-01-B.md](catalogue/scenarios/SC-GIB-REL-01-B.md) | `2:5624` | SC-GIB-REL-01-B - Time-Sensitive Relationship Risk Or Commitment | 4532 |
| [catalogue/scenarios/SC-GIB-REL-01-C.md](catalogue/scenarios/SC-GIB-REL-01-C.md) | `2:5623` | SC-GIB-REL-01-C - Tier-Based Cadence Review | 4400 |
| [catalogue/scenarios/SC-GIB-INTEL-01-D.md](catalogue/scenarios/SC-GIB-INTEL-01-D.md) | `103:4` | SC-GIB-INTEL-01-D - Accumulated Signals With No Single Trigger (candidate) | 5066 |
| [catalogue/scenarios/SC-GIB-INTEL-01-E.md](catalogue/scenarios/SC-GIB-INTEL-01-E.md) | `103:5` | SC-GIB-INTEL-01-E - Converging Changes Or Cross-Client Implication (candidate) | 5348 |
| [catalogue/scenarios/SC-GIB-MEET-01-D.md](catalogue/scenarios/SC-GIB-MEET-01-D.md) | `105:4` | SC-GIB-MEET-01-D - Protocol-Driven Or First Senior Interaction | 7088 |
| [catalogue/scenarios/SC-GIB-MEET-01-E.md](catalogue/scenarios/SC-GIB-MEET-01-E.md) | `105:5` | SC-GIB-MEET-01-E - Short-Notice Or Unplanned Interaction (candidate) | 6991 |
| [catalogue/scenarios/SC-GIB-PIPE-01-F.md](catalogue/scenarios/SC-GIB-PIPE-01-F.md) | `104:5` | SC-GIB-PIPE-01-F - Deliberate Exit | 4935 |
| [catalogue/scenarios/SC-GIB-PIPE-01-G.md](catalogue/scenarios/SC-GIB-PIPE-01-G.md) | `104:6` | SC-GIB-PIPE-01-G - Review Condition Reached Without Movement | 5218 |
| [catalogue/scenarios/SC-GIB-PIPE-03-A.md](catalogue/scenarios/SC-GIB-PIPE-03-A.md) | `105:2` | SC-GIB-PIPE-03-A - Alignment-Only Forum (candidate) | 4777 |
| [catalogue/scenarios/SC-GIB-PIPE-03-B.md](catalogue/scenarios/SC-GIB-PIPE-03-B.md) | `105:3` | SC-GIB-PIPE-03-B - Decision Forum (candidate) | 5288 |
| [evidence/coverage-senior-md/confirmed-intent.md](evidence/coverage-senior-md/confirmed-intent.md) | `2:5603` | Coverage Senior MD Confirmed Intent Evidence | 15619 |
| [evidence/interviews/round-1-discovery-interview/senior-coverage-md-intent-interview-full-appendix-plain-text.md](evidence/interviews/round-1-discovery-interview/senior-coverage-md-intent-interview-full-appendix-plain-text.md) | `2:5599` | Senior Coverage MD Intent Interview - Full Appendix | 95488 |
| [evidence/interviews/round-1-discovery-interview/senior-coverage-md-intent-interview-full-appendix.md](evidence/interviews/round-1-discovery-interview/senior-coverage-md-intent-interview-full-appendix.md) | `2:5661` | Senior Coverage MD Intent Interview - Full Appendix | 101241 |
| [evidence/interviews/round-1-discovery-interview/senior-coverage-md-pipeline-intent-interview-summary.md](evidence/interviews/round-1-discovery-interview/senior-coverage-md-pipeline-intent-interview-summary.md) | `2:5601` | Senior Coverage MD Pipeline Intent: Comprehensive Interview Summary | 29882 |
| [evidence/interviews/round-2-product-proxy-interviews/capital-markets-market-intelligence-direction-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/capital-markets-market-intelligence-direction-proxy-interview.md) | `19:6127` | Capital Markets Market Intelligence Direction - Proxy Interview | 14142 |
| [evidence/interviews/round-2-product-proxy-interviews/coverage-market-intelligence-direction-proxy-interview.md](evidence/interviews/round-2-product-proxy-interviews/coverage-market-intelligence-direction-proxy-interview.md) | `19:6128` | Coverage Market Intelligence Direction - Proxy Interview | 11585 |
| [reference/knowledge/banker-archetypes.md](reference/knowledge/banker-archetypes.md) | `2:5644` | --- | 5848 |
| [reference/personas/ib-coverage-analyst-junior.md](reference/personas/ib-coverage-analyst-junior.md) | `2:5657` | IB Coverage Analyst, Junior (A&A Coverage) | 7257 |
| [reference/personas/ib-ecm-analyst-junior.md](reference/personas/ib-ecm-analyst-junior.md) | `2:5658` | IB ECM Analyst, Junior (A&A Product) | 7036 |
| [reference/personas/ib-ecm-banker-md.md](reference/personas/ib-ecm-banker-md.md) | `2:5659` | IB ECM Banker, Managing Director | 5935 |
| [prompts/buc-entry-writing-prompt.md](prompts/buc-entry-writing-prompt.md) | `2:5622` | You write business use case (BUC) entries for an intelligence platform used by senior inve | 5197 |
| [templates/actor_archetype_template.md](templates/actor_archetype_template.md) | `2:5638` | Responsible Actor Archetype And Persona Template | 8616 |
| [templates/artifact_generation_guide.md](templates/artifact_generation_guide.md) | `2:5621` | Intent Artifact Generation Guide | 13786 |
| [templates/business_outcome_template.md](templates/business_outcome_template.md) | `2:5639` | Business Outcome Template | 7146 |
| [templates/business_use_case_template.md](templates/business_use_case_template.md) | `2:5640` | Business Use Case Template | 17365 |
| [templates/job_family_template.md](templates/job_family_template.md) | `2:5641` | Job Family Template | 6627 |
| [templates/jtbd_template.md](templates/jtbd_template.md) | `2:5642` | Jobs to Be Done Template | 9063 |
| [templates/scenario_template.md](templates/scenario_template.md) | `2:5643` | Scenario Template | 7183 |
| [reference/untested-user-profiles/README.md](reference/untested-user-profiles/README.md) | `2:5646` | Untested User Profiles | 156 |
| [reference/untested-user-profiles/ib-coverage-md.md](reference/untested-user-profiles/ib-coverage-md.md) | `2:5654` | IB Coverage MD (M&A / Coverage) | 6731 |
| [reference/untested-user-profiles/persona-agent-senior-corporate-coverage-banker.md](reference/untested-user-profiles/persona-agent-senior-corporate-coverage-banker.md) | `2:5645` | Persona Agent: Senior Corporate Coverage Banker (CRM Prototype Critic) — Ask Mode | 23279 |
| [reference/untested-user-profiles/persona-agent-senior-dcm-banker.md](reference/untested-user-profiles/persona-agent-senior-dcm-banker.md) | `2:5649` | Persona Agent: Senior DCM Banker (CRM Prototype Critic) — Ask Mode | 22752 |
| [reference/untested-user-profiles/persona-agent-senior-ecm-banker.md](reference/untested-user-profiles/persona-agent-senior-ecm-banker.md) | `2:5650` | Persona Agent: Senior ECM Banker (CRM Prototype Critic) — Ask Mode | 25570 |
| [reference/untested-user-profiles/persona-agent-senior-gcb-banker.md](reference/untested-user-profiles/persona-agent-senior-gcb-banker.md) | `2:5653` | Persona Agent: Senior GCB Banker (CRM Prototype Critic) — Ask Mode | 3792 |
| [reference/untested-user-profiles/persona-agent-senior-ma-banker.md](reference/untested-user-profiles/persona-agent-senior-ma-banker.md) | `2:5651` | Persona Agent: Senior M&A Banker (CRM Prototype Critic) — Ask Mode | 19921 |
| [reference/untested-user-profiles/persona-agent-senior-sponsor-banker.md](reference/untested-user-profiles/persona-agent-senior-sponsor-banker.md) | `2:5652` | Persona Agent: Senior Sponsor Banker (CRM Prototype Critic) — Ask Mode | 7789 |

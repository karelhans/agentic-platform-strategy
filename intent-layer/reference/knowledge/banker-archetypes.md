---
id: banker-archetypes
title: Banker Archetypes
layer: knowledge
status: stable
source: interim-committed
canonical: confluence-pending
promoted_from: _scratch/banker-archetypes.md
promoted_on: 2026-08-05
---

> **Provenance — interim committed copy.**
> This UX persona reference was promoted out of the git‑ignored `_scratch/` so it
> stops being a dead link from
> [persona-experience/design.md](../../openspec/changes/persona-experience/design.md#persona-reference-material--governance).
> **Canonical ownership will move to Confluence** (edited by PM · UX · Research),
> synced back here read‑only via `sync-reference-docs.js` (`type: confluence`,
> the commented `persona-reference` source in
> [config.yml](../config.yml)). Until that flow is wired, THIS file is the
> working reference. Do not fork the narrative into code — code cites persona IDs
> only.

# Banker Archetypes
> How different banker levels think, work, and consume intelligence

---

## MD / ED (Managing Director / Executive Director)

### Mental Model
- **Client-first**: every signal is evaluated through "what does this mean for my client relationships?"
- **Time-starved**: 80%+ of time should be with clients; AI must compress everything else
- **Judgment-centric**: value comes from pattern recognition + relationship context, not data retrieval
- **Action-oriented**: insights only matter if they lead to a client touchpoint or deal progression

### Daily Workflow
1. Morning: Orient → scan brief, identify what needs attention today (5–10 min max)
2. Pre-meeting: Prep → refresh on client context, recent signals, talking points (10–15 min)
3. Meeting: Engage → deep client conversation, relationship building, idea exploration
4. Post-meeting: Capture → voice note outcomes, actions, follow-ups (2–3 min walk-back)
5. Throughout day: React → respond to breaking signals, delegate, approve AI-proposed actions

### Pain Points
- Point-in-time engagement → episodic relationships, missed windows
- Manual synthesis across scattered sources → slow, incomplete picture
- Admin burden (prep, coordination, follow-ups) → less client time
- "Dry spells" — clients going unengaged due to capacity constraints

### AI Relationship
- Wants to *validate and refine*, not *build from scratch*
- Trust threshold is HIGH — won't send AI output to clients without review
- Expects AI to know their style, clients, history — personalization is table stakes

### Key Metric: Time to client action (signal → outreach sent)

---

## VP (Vice President)

### Mental Model
- **Execution bridge**: translates MD strategy into organized work streams
- **Context aggregator**: synthesizes data for MD decision-making
- **Quality gatekeeper**: ensures accuracy before client-facing delivery
- **Multi-client juggler**: managing 8–15 active relationships simultaneously

### Daily Workflow
- Monitors deal pipeline progression and flags blockers
- Prepares materials MDs will use in client meetings
- Reviews and refines AI-generated outputs before escalation
- Coordinates across product partners and sector specialists

### AI Relationship
- Power user of investigation tools — deep-dives into signals
- Wants comprehensive data, not just summaries
- Uses AI to draft, then heavily edits
- Values audit trail and source evidence

---

## Analyst / Associate (AN / AS)

### Mental Model
- **Throughput-focused**: measured on volume and accuracy of deliverables
- **Learning-oriented**: building pattern recognition through repetition
- **Detail-obsessed**: accuracy and completeness of data is paramount
- **Process-following**: clear workflows, templates, checklists

### Daily Workflow
- Producing analysis (comps, valuations, models)
- Building presentations (pitches, CIMs, board materials)
- Monitoring data feeds for updates to live processes
- Supporting VP/MD with ad-hoc research requests

### AI Relationship
- Highest adoption potential — most time spent on automatable tasks
- Productive AI target (document automation, model generation)
- Simulation-based upskilling (client interaction practice)
- May feel threatened by AI replacing tasks → positioning matters
 
## Cross-Level Patterns

### Information Consumption by Level
| Level | Prefers | Depth | Frequency | Channel |
|-------|---------|-------|-----------|---------|
| MD/ED | Narrative briefs, action recommendations | Headlines + "why it matters to my clients" | Morning + breaking alerts | Mobile, voice, email |
| VP | Structured analysis, evidence trails | Full detail with sources | Throughout day | Desktop, search, drill-down |
| AN/AS | Raw data, templates, precedents | Complete datasets | Continuous | Desktop-intensive, tool-heavy |

### Data Capture Behavior
- **Current state**: Only ~6% of GIB meetings include meeting notes
- **Shift required**: Make data creation a core front-office responsibility
- **Incentive alignment**: Data capture → better AI → less admin → more client time (flywheel)

### Team Dynamics (AI-Augmented)
- MDs managing "hybrid AI-human teams" — agents + junior bankers
- "Agent factory" concept: MDs deploy specialized agents the way they'd delegate to juniors
- Junior bankers shift to validation and judgment-building (not data retrieval)
- Knowledge institutionalized in searchable base (reduce "reinvention of the wheel")

---

## Trace to machine personas

How these human archetypes map to the executable identities in
[`identity.ts`](../../src/navigation/identity.ts) — see the full trace table in
[persona-experience/design.md](../../openspec/changes/persona-experience/design.md#the-human--machine--code-trace).

| Human archetype (this doc) | Machine identity | Seniority key |
|---|---|---|
| MD / ED | Sofia · Coverage (+ Daniel/M&A, Priya/ECM, Mateo/DCM) | `md` |
| VP | safe‑baseline identity | `vp` |
| Analyst / Associate | (switcher demo state) | `aa` |

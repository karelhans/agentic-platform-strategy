# Design Brief — Agentic Platform Strategy Presentation

**Prepared for:** GIB Agentic Platform stakeholders
**Source:** Direction from Michael Elanjian
**Status:** Draft for review

---

## 1. Background

We have an original prototype concept for an agentic platform serving the GIB (Global & Investment Banking) banker population. The next milestone is a presentation that moves the story from "prototype concept" to a credible product and experience strategy — grounded in real banker workflows, expressed in a production design language, and underpinned by a scalable pattern architecture.

The presentation must demonstrate three things, in a deliberate sequence: **who this is for and what they do** (use cases), **what it looks and feels like** (mobile-first SALT prototype), and **how it scales** (core experience patterns).

## 2. Objective

Produce a presentation that convincingly shows:

1. The breadth and depth of banker workflows the platform serves — across lines of business and across seniority levels, including agent participation.
2. A mobile-first, AI-optimized redesign of the original prototype in SALT, proving the concept works with real navigation and information architecture.
3. An experience strategy built on reusable patterns — built once, configured and personalized per banker through data and content — rather than bespoke UI per line of business.

## 3. Deliverable 1 — Key use cases: breadth and depth of the GIB banker population

Identify and dramatize key use cases that show how the platform serves the full GIB banker population, with two dimensions of coverage:

- **Inter-LOB:** workflows that cross lines of business (e.g., Coverage, M&A, Capital Markets).
- **Senior–junior–agent interactions:** how work flows between seniority levels and AI agents.

The use cases should illustrate the full lifecycle of an insight:

- **Receive** — how a senior banker receives insights.
- **Investigate** — how they dig into an insight.
- **Delegate and/or action** — how they act on it directly, or hand it off.
- **Propagate** — how those actions ripple through the ecosystem into other "desktops."

Illustrative scenarios to feature:

- A senior banker delegates a task to a junior banker to create a deck.
- A junior banker invokes an agent to spin up a new opportunity.
- All impacted LOBs (e.g., Coverage, M&A) are automatically notified as work propagates.

**Success looks like:** the audience sees that this is not a single-persona demo — it is an ecosystem where insights and actions flow between senior bankers, junior bankers, agents, and adjacent LOBs.

## 4. Deliverable 2 — Mobile-first, AI-optimized SALT prototype

Redesign the original prototype concept as a **mobile-first, AI-optimized** experience built in the **SALT design system**, and use it to walk through the real use cases from Deliverable 1.

Requirements:

- Mobile-first layouts — not a desktop concept shrunk down.
- Proper consideration for **navigation** and **information architecture** (not just screens; a coherent structural model).
- AI-optimized: the interface is designed around agentic and AI-driven interactions, not retrofitted with them.
- Fidelity sufficient to demonstrate how the Deliverable 1 use cases actually play out end-to-end.

**Success looks like:** the audience can follow a real banker scenario through the redesigned prototype and believe it would work in production.

## 5. Deliverable 3 — Concept and experience strategy: core patterns

Define a clear experience strategy centered on **core experience patterns — built once, then leveraged, configured, and personalized for bankers through data and content.**

The guiding principle: **we do not build a separate conversational chat UI for each line of business.** Instead, we define one pattern with guidelines for:

- How a chat surface **pulls in context** (user, role, LOB, current task, data entitlements).
- How it **invokes skills** specific to the user's needs.

Illustrative example: a junior capital markets banker leverages a **Market Monitor Compset skill** inside the chat to create a compset with the exact data and columns they want — no bespoke Cap Markets chat product required.

**Success looks like:** the audience understands the platform economics — a small set of patterns serving every LOB and persona through configuration and data, not duplicated builds.

## 6. Suggested presentation narrative arc

1. **The population** — who GIB bankers are; the senior–junior–agent web of interactions across LOBs.
2. **A day in the life** — the key use cases: insight received → investigated → delegated/actioned → propagated, with cross-LOB notification.
3. **The experience** — the mobile-first SALT prototype walking through those exact use cases.
4. **The strategy** — core experience patterns; build once, configure everywhere; the chat + context + skills model.
5. **Why this scales** — pattern reuse across LOBs and personas; what gets built vs. what gets configured.

## 7. Design principles

- **Ecosystem, not app** — actions propagate across desktops, roles, and LOBs.
- **Mobile-first, AI-optimized** — designed for how bankers actually work and how agents actually assist.
- **Patterns over products** — one pattern, many configurations; personalization comes from data and content.
- **Real workflows** — every screen shown maps to a named use case, not a hypothetical.

## 8. Scope

**In scope**

- Use case definition and selection (Deliverable 1).
- Mobile-first SALT redesign of the original prototype (Deliverable 2).
- Experience pattern strategy and guidelines, with the chat/context/skills model as the anchor example (Deliverable 3).
- Presentation deck weaving the three together.

**Out of scope (for this presentation)**

- Production build or engineering specification.
- Exhaustive pattern library — the strategy and anchor patterns, not the full catalog.
- Desktop-first redesign (mobile leads; other form factors follow the same patterns).

## 9. Open questions

- Which specific use cases make the final cut, and how many can the presentation carry without diluting the story?
- Which LOBs beyond Coverage, M&A, and Capital Markets should appear in the propagation scenarios?
- What is the initial skill catalog to reference alongside Market Monitor Compset?
- Presentation length, venue, and audience seniority — these will set the fidelity bar for the prototype walkthrough.

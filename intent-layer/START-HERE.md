# Start here: how to frame your work against the Intent Layer

One page. Read this before anything else in `intent-layer/`. The long versions are the charter, the consumer guide and the mapping; this page is enough to work from.

## The one rule

The Intent Layer says what the business is trying to achieve. It is written from bankers' evidence and owned by the IB Knowledge Base. Products, projects, research and design **cite it by ID**; they never add to it or edit it. If your work shows a record is wrong or missing, you raise a review trigger on that record and carry on.

## Six records, in plain words

| Record | Plain meaning | The question it answers | Example |
| --- | --- | --- | --- |
| Business outcome `BO-*` | What should change for the business, with a measure | What are we trying to move? | Fewer material surprises |
| Job family `JF-*` | One standing area of senior banker work | Which area of work is this? | Intelligence triage |
| JTBD `JTBD-*` | The progress a banker wants, in their own words | **Why** does the banker bother? | "When new information may affect my clients, help me isolate what matters, judge it and choose the response, without acting on noise" |
| Business use case `BUC-*` | The work that gets the job done: trigger, six steps, who judges, value delivered | **How** does the work run when it goes well? | Triage and send a Signal: reduce noise, find affected clients, explain what it means, MD decides, record, send to the owner |
| Scenario `SC-*` | The same use case under different conditions | What changes when conditions change? | Short window; high impact but low confidence; a Decision to monitor or dismiss |
| Actor `ACTOR-*` | A cohort with accepted responsibility, and the judgments it keeps | Who judges, who contributes? | Senior Coverage MD keeps: does it matter, is it credible, respond or not |

### JTBD versus business use case, because this is the one that confuses people

They look alike because most families began with exactly one of each. They are not the same thing. Since the model revision of 2026-10-07 the intelligence, relationship and pipeline families each carry a second or third use case as a candidate, and the test below is how they were told apart.

- The **JTBD** is about the person. It is what you hear in an interview and what stays true if every product disappeared. A researcher validates it.
- The **business use case** is about the process. It is what you observe in an episode: what triggered it, what happened step by step, who decided, what was left behind. A designer maps against it.
- One job can be served by more than one use case. "Isolate what matters and choose the response" is one job. Triaging a single signal and re-orienting at the start of the day are two different processes serving it, with different triggers and different outputs.

Test for which one you are holding: if it begins "when X, help me Y" it is a job; if it has a trigger and steps it is a use case; if it describes screens or clicks it is neither, it is a product use case and lives on the product side.

## What each role starts from, produces, and cites

| Role | Start from | Produce | Cite | Do not |
| --- | --- | --- | --- | --- |
| **Researcher** | The JTBD statements and the use case steps for the family you are studying, plus the Round 2 guide for it | Episodes (what actually happened, step by step), confirmations or edits to JTBD statements, value ranges for outcomes | `JTBD-*`, `BUC-*` and step numbers, `SC-*` the episode fell into | Write a new JTBD from a product idea; treat one participant's acceptance as confirmation |
| **Designer** | The business use case you are designing for, its scenarios, and the actor's list of judgments that stay human | Product use cases: the ordered steps a persona takes in the product to do part of a business use case | `BUC-*` and the steps you change, one `SC-*` you cover and one you deliberately do not, the `ACTOR-*` behind your persona | Call a product flow a use case; automate a judgment the actor record keeps with the human; derive a persona from anything but an actor record |
| **Product manager** | The business outcome and job family your initiative serves | The alignment statement: nine written answers, each pointing at a record by ID | `BO-*` and the measure you will move, then everything the designer and researcher cite | Use speed, volume or productivity as the primary measure; cite a `Hypothesis` record as the only justification for a build |
| **Anyone** | The maturity label on every record | A review trigger whenever your evidence contradicts a record | The record ID and revision | Edit the record locally or work around it |

## Read the label

Every record carries a maturity label and a review state. `Candidate` means raised by a proposal and not admitted: cite it only as a gap. `Superseded` means do not cite it. `Hypothesis` means plausible, little direct evidence. `Evidence-backed` means supported but not the standing model. `Confirmed` means accepted by the responsible group, and today that group is one Senior Coverage MD, so treat it as evidence-backed until a second banker has been through it. A product spec is never evidence of a user need, so anything raised from one stays `Hypothesis` until a banker episode supports it.

## Six words with fixed meanings

Capitalise these when they carry the meaning below. Do not use them loosely.

| Term | Meaning |
| --- | --- |
| Signal | A piece of new information that may affect a client. |
| Decision | The chosen response to a Signal: act, monitor, or dismiss. |
| Rationale | Why that Decision was made, in one sentence. |
| View | The workspace or person the Signal goes to next. |
| Interaction | A banker and a client meet live: a phone call, a virtual meeting or an in-person meeting. |
| Engagement | Any contact with a client, including emails, messages and Interactions. Every Interaction is an Engagement; not every Engagement is an Interaction. |

## Where things are

| Need | Go to |
| --- | --- |
| The rules in full | `CHARTER.md` |
| The six record types explained visually | `intent-layer-explained.html` |
| What a whole job family looks like, generic and worked | `consumers/job-family-example.html` |
| Definitions to paste into a product definition page | `consumers/ibiq-product-definition.md`, sections 4 and 5 |
| How five real product specs mapped, and what they got wrong | `consumers/ibiq-use-case-mapping.md`, section 1 is enough |
| The full test of every job and use case, and what should change | `proposals/model-revision-2026-10-07.md`, sections 2 to 5 |
| The records themselves, with maturity and review state per record | `catalogue/README.md` |
| The interview guides to run next | `evidence/interviews/round-2-product-proxy-interviews/` |

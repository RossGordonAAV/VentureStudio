# Venture Studio – charter

Ross Gordon's agent team for sketching early-stage business ideas. Private.

## The one rule: speed of action
Action creates information. Analysis doesn't. Every round ends with a **small, real-world test** that can start this week, not a better plan.

- **Don't overthink.** Each agent writes at most one page; five bullets is better.
- **Smallest test that changes a decision.** If the result wouldn't change what we do next, it isn't worth running.
- **Pass and kill criteria are set before the test starts**, never after.
- **Default test box:** two weeks, low cost (Ross sets the cap per idea; agents never fill one in).
- **Cheap first:** conversations, landing pages, smoke tests, concierge versions and letters of intent come before code, hires or spending.
- **Keep, pivot, park or kill** at every round. "Needs more research" is not an outcome on its own; it becomes a test.
- **Integrate, don't invent (Ross, 20 Nov 2026).** Ideas use technology that already exists and works. The business is in putting proven pieces together – logistics, contracts, data, regulation, partners – not in developing new or cutting-edge technology. No deep-tech development projects.
- **Recurring revenue, not consultancy (Ross, 20 Nov 2026).** Prefer business models with recurring revenue (subscriptions, service contracts, per-unit fees on a repeat basis). Transactional is fine if the market is big enough. Consultancy or one-off project work is not a business we want to build.
- **A small side business is a valid outcome (Ross, 20 Nov 2026).** If an idea isn't a scalable company but could run as a side business with low set-up cost and few hours a week, say so – it can still be a 'keep going'.
- **Get out the door.** Talking to people rates above desk work. If one conversation could answer the question, that's the test, and the agents name real people to call, each with a source (`shared/get-out-the-door.md`).

## The team
| Seat | Agent | Stance | One question |
|---|---|---|---|
| CEO | `ceo` | Optimist, orchestrator | How could this work, and what do we do this week? |
| CFO | `cfo` | Realist | What does it cost, and how long does the money last? |
| CTO | `cto` | Route-finder | Mountain in the way? Go via X. |
| Chief Scientific Officer | `cso-science` | Science scout (only when the idea rests on science) | Is it true, and what will science change in 2–3 years? |
| Chief Strategy Officer | `strategy` | Outside view | Who else, why now, and why do we win? |
| Go-to-Market | `go-to-market` | First-customer hunter | Name ten people who'd pay, and how we reach them. |
| Wedge check | `wedge` | Critical, not negative | Is there a real niche to start in, and can it grow into something substantial? |
| Audit team | `audit` | Light investor panel, sceptical, blind | Would we fund this on what's in front of us? If not, what instead? |

## Prototype Lab (physical products)
A separate subsection that turns a physical-product idea into a **V1 → V2 → V3** path. Runs when Ideas → Physical product is ticked and a round decides to build, or when Ross asks. Protocol: `shared/prototype-lab.md`.

| Seat | Agent | Stance | One question |
|---|---|---|---|
| Industrial design lead | `prototype/design-lead` | Runs the Lab; one product, three versions, one path | What are the best V1, V2 and V3, and what gets us from one to the next? |
| V1 – off the shelf | `prototype/v1-off-the-shelf` | Scavenger | What can a user hold within a week, from parts we can buy today? |
| V2 – custom | `prototype/v2-custom` | Specialist maker | Which parts do we make (3D print, laser, CNC, casting, sewing) for a small sellable batch, first units within a week? |
| Fit check | `prototype/fit-check` | Measure twice, cut once – independent, fresh eyes | Will every part actually fit together, by the spec sheet? |
| V3 – volume | `prototype/v3-volume` | Manufacturing engineer | At volume, which processes give a better product at lower unit cost, and when does tooling pay back? |

No tooling or minimum orders before the V2 → V3 gate. The Lab's costs feed the next round's CFO; its gates feed the CEO's next test.

## How a round runs
1. **Brief (CEO).** One-liner, who it's for, the question for this round, the riskiest assumption.
2. **Specialists in parallel.** CFO, CTO, Strategy, Go-to-Market, Wedge check (and CSO when science matters) each answer the brief **without seeing each other's output**.
3. **Synthesis (CEO).** One page: what we believe, what we don't, the proposed decision, the minimum next test and the people to talk to this week.
4. **Audit (blind).** The audit team sees **only** the CEO's one-page synthesis and the proposed test. No research, no specialist notes. It returns a verdict and alternative actions.
5. **One rebuttal.** CEO answers each audit point in a line: accept, adjust or reject with reason.
6. **Ross decides** with tick-boxes: decision, test to run, cost cap, owner, which people to approach. Logged in Airtable.

Full protocol: `shared/round-protocol.md`.

## Ideas stay separate
- One record per idea in the **Venture Studio** Airtable base; every round, test and decision links to exactly one idea.
- An agent works on one idea per run and reads nothing from another idea unless Ross asks for a comparison.
- Nothing from AAV portfolio or pipeline work goes in; AAV bases are out of bounds for this team.

## Where things live
| Layer | Where |
|---|---|
| Rules and personas | this repo (`shared/`, `agents/`) |
| Ideas, rounds, tests, decisions | Airtable → Venture Studio base (`shared/airtable-map.md`) |
| Overview | Venture Studio dashboard (Claude page) |
| Writing style | `RossGordonAAV/aav-agents` → `shared/writing-style.md` |

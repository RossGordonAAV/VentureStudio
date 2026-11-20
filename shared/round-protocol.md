# Round protocol

A round is one pass of the team over one idea. Target: done in one sitting.

## Triggers
- "New idea: X" → create the Idea record (Stage `Spark`) and run Round 1.
- "Run a round on X" / "X: next round" → next round on an existing idea.
- A test finishes (Result filled in) → propose a round to read the result.

## Steps
| # | Who | Sees | Produces | Written to |
|---|---|---|---|---|
| 1 | CEO | Idea record, last round, open tests | Brief: one-liner, customer, question for this round, riskiest assumption | Rounds → CEO brief |
| 2 | CFO, CTO, Strategy, Go-to-Market, Wedge, CSO (if `Science relevant`) | Brief + Idea record only | Own one-pager (see each SKILL.md) + up to 2 named people to talk to, with sources | Rounds → one field per seat; People to talk to → new rows |
| 3 | CEO | All of step 2 | Synthesis (≤1 page): believe / don't know / proposed decision / minimum next test / top 3–5 people to talk to this week | Rounds → CEO synthesis; Ideas → Wedge verdict proposed |
| 4 | Audit | **Synthesis and proposed test only** | Verdict + up to three alternative actions | Rounds → Audit verdict |
| 5 | CEO | Audit output | One-line answer per audit point: accept / adjust / reject (why) | Rounds → CEO rebuttal |
| 6 | Ross | Synthesis, audit, rebuttal | Tick-boxes: decision, which test, cost cap, owner, which people to approach | Rounds → Decision; new Tests row; approved people |

## Running it
- **Live in chat:** run steps 2 as separate sub-agents in parallel so seats don't see each other. Each gets: `shared/rules.md`, its own SKILL.md, the brief, the Idea record. Nothing else.
- Audit runs as its own sub-agent with only the synthesis text pasted in. Never give it the specialist notes, sources or Airtable access.
- Skip a seat if it has nothing material to add; say "CTO: no material view" rather than padding.

## The minimum next test
**Showstopper first, conversation first.** The test targets the single question that kills the idea if the answer is wrong. If talking to someone could answer the riskiest assumption, that is the test (`shared/get-out-the-door.md`).

Every synthesis also gives a **testability verdict** (Easy / Possible / Hard): can the showstopper be tested within 2 weeks for near-zero cost, with a real signal (money, pre-order, signed LOI – not likes)? Ross (20 Nov 2026).

Every synthesis proposes one, with:
- **Assumption** it tests (one sentence).
- **Method** (who, what, how many).
- **Pass** and **kill** criteria, numeric where possible.
- **Time box** (default 14 days) and **cost cap** `[Ross: confirm]`.
- **Owner** (default Ross).

Good tests: 10 customer calls with a set script, a landing page with a sign-up, a pre-order or letter of intent, a concierge version done by hand, a call with two labs on feasibility, a quote from a supplier.
Bad tests: "more desk research", "build an MVP", anything over a month.

## Decisions
- **Keep going** – run the test, next round on the result.
- **Pivot** – change customer, problem or route; new brief.
- **Park** – nothing to test now; note the trigger that would reopen it.
- **Kill** – note why in one line (useful later).

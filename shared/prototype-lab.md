# Prototype Lab – protocol

A subsection of the Venture Studio for **physical products**. It answers one question per idea: *what are the best V1, V2 and V3 of this product, and what must be true to move from one to the next?*

Runs only on ideas with **Ideas → Physical product** ticked, or when Ross asks ("prototype X", "Prototype Lab on X"). Same standing rules (`shared/rules.md`): speed, integrate don't invent, never estimate money, one idea per run.

## The three versions
| Version | Agent | Question | Typical make route | Volume |
|---|---|---|---|---|
| **V1 – off the shelf** | `v1-off-the-shelf` | What can we put in a user's hands **within a week** from parts we can buy today? | DIY store, Action, bol.com, Amazon, AliExpress, RS/Conrad/Misumi, hand assembly | 1–10 |
| **V2 – custom** | `v2-custom` | Where off-the-shelf falls short, which parts do we make – and how – to get a product we could sell in a small batch, **with first units in hand within a week**? | 3D printing (FDM, SLA, SLS/MJF), laser cutting, CNC, sheet metal, vacuum forming, silicone/urethane casting, sample-room sewing, PCB services | 10–500 |
| **V3 – volume** | `v3-volume` | At volume, which processes and suppliers give a better product at a lower unit cost, and at what volume does each pay off? | Injection moulding, extrusion, die-casting, stamping, blow moulding, cut-and-make, contract manufacturing | 1,000+ |

The **industrial design lead** (`design-lead`) runs the three and owns the result: one product, three versions, one path.

## One-week rule (Ross, 21 Nov 2026)
V1 and V2 should each be buildable, or have a working solution in hand, **within one week** of Ross's go.
- Lead time is a selection criterion, not a footnote: a part or service that can't arrive within the week loses to a slower-looking but faster-arriving alternative.
- Prefer NL/EU stock with next-day delivery, local print bureaus, fab labs and instant-quote services that ship in days. AliExpress and overseas suppliers only if delivery fits inside the week.
- **Local first where faster (Ross, 21 Nov 2026):** Ross is in Amsterdam and happy to pop to a DIY store, shop, print bureau or fab lab himself. Per part, pick whichever is faster – collect locally (name the store or branch; check stock where the site shows it) or order online (delivery days). Every V1/V2 parts table has a **Get it** column: Collect (place) / Order online (days).
- If no route fits a week, say so, give the fastest route with its real lead time, and name the part that's holding it up.
- V3 has no one-week rule; it's a plan until the V2 → V3 gate.

## How a Lab run works
| # | Who | Sees | Produces |
|---|---|---|---|
| 1 | Design lead | Idea record, latest round synthesis, earlier Prototypes rows | **Design brief**: user and use, the one job the product must do, critical-to-function features and dimensions, looks-like vs works-like split, what V1/V2/V3 must each prove |
| 2 | V1, V2, V3 in parallel | Design brief + Idea record only | Own one-pager (see each SKILL.md) |
| 3 | Design lead | All of step 2 | **Roadmap** (≤1 page, format below) + the minimum next build |
| 4 | Ross | Roadmap | Tick-boxes: which V1 to build, cost cap, which quotes to request, owner |

Live in chat: step 2 runs as three sub-agents in parallel, so V2 and V3 aren't anchored on V1 (same reason the C-suite seats run blind). Skip a version if it adds nothing now – "V3: not material until V1 sells" is a valid answer.

## Roadmap format (design lead)
| | V1 | V2 | V3 |
|---|---|---|---|
| Purpose – what it proves | | | |
| Make route | | | |
| Key parts / processes | | | |
| Unit cost (sourced) | | | |
| Set-up cost (tooling, files, jigs) | | | |
| Lead time | | | |
| Quality / look vs previous | | | |
| **Gate to next version** | | | — |

Then: **Day-by-day plan for the week** (V1 and V2: order day, delivery day, build day, first user) · **Design choices that carry through** (decide now so V1 isn't a dead end – e.g. keep the 75 mm bore so V3 can use stock extrusion) · **Minimum next build** (what, how many, by when, who) · **Quotes to request** (supplier, part, quantity) · up to two people to talk to.

## Gates (default, Ross can override per idea)
- **V1 → V2:** the product does its job for real users (e.g. 3+ households use it for 2 weeks) and someone has asked to buy one.
- **V2 → V3:** paid units sold at the target price (number `[Ross: confirm]`) and a supplier quote shows the V3 unit cost works.
- No tooling, moulds or minimum-order commitments before the V2 → V3 gate is passed. Ross sets every cost cap.

## Money and quotes
- Prices only with a source: a shop listing, a price page or a written quote. Otherwise `quote needed` or `[Ross: confirm]`.
- A missing price that matters is a **test**: "request quotes from 3 suppliers for 100 bases" goes to Tests like any other.
- Instant-quote tools (Hubs, Protolabs, JLCPCB, laser-cutting services) count as sourced when the quote is saved with its date and the inputs used.

## Link to the C-suite rounds
- A Lab run is triggered by a round decision ("Keep going – build V1") or by Ross directly.
- The CTO seat stays the route-finder in rounds and may say "send this to the Prototype Lab".
- The roadmap's unit costs and set-up costs feed the next round's CFO seat; the gates feed the CEO's minimum next test.
- Results are written to Airtable → **Prototypes** (`shared/airtable-map.md`), one row per version per Lab run.

## Get out the door
Prototyping questions are often answered fastest by someone who makes things: a supplier's sales engineer, a print bureau, a fab lab, a contract manufacturer. Same rules as `shared/get-out-the-door.md`: real names with a source, industry first. Ross's warm route for hands-on help is Matrix Innovation Center (Ivo Sweep, Raymond) – flag it when a workshop or lab would help.

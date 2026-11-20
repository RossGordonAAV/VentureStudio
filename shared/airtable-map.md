# Airtable map – Venture Studio base

Base **Venture Studio** `appKUC6vXhmMjQJiz` (Ross's own workspace, separate from all AAV bases).

## Ideas `tblwMK8pvZb8mEbEu` – one record per idea
| Field | ID | Notes |
|---|---|---|
| Idea (primary) | `fldsCu1m03Axu5x2i` | short name |
| One-liner | `fld93ZOSO86DedcjU` | |
| Stage | `fldsRhatULtjFjdhZ` | Spark · Framing · Testing · Building · Parked · Killed – **Ross only** |
| Customer | `fldfL6UYPsrGyqrO3` | |
| Riskiest assumption | `fldU5ZEEiXyXkJBT4` | |
| Minimum next step | `fldcnGphmVfzH0KWe` | shown on the dashboard |
| Next step due | `fldhFpIFK8Tv26tyW` | date |
| Potential | `fldVtWzrcyPsQVfdq` | rating 1–5, **Ross only** |
| Confidence | `flddWmsAhsb0nkKzb` | rating 1–5 |
| Science relevant | `flds6AH16737x3dwR` | ticked → CSO joins |
| Sector | `fldRfMe5b9odYtT3P` | |
| Partners | `fldDXYFRc50NV0Suy` | |
| Park or kill reason | `fldEP7UglNi1WbgVq` | |
| Started | `fldxtsLgG4MeJUbzP` | date |
| Notes | `fldpgAqnKIZNhrfVj` | |
| Wedge verdict | `fldj3GfAbvpTktuzh` | Clear wedge · Wedge too wide · Too close to incumbents · Dead-end niche |
| Round status | `fldDcO28XljXisyiV` | Agents working · Waiting for Ross · Idle – agent-managed (dashboard status light) |
| NABC | `fld8SUkjqLFjdmZa4` | CEO-managed, Ross's NABC template |
| Open decision | `fldJYG6CWzSPnsuBA` | agent-managed; what's waiting for Ross |
| Explainer | `fldkO3UkwIRnz9fTO` | CEO-managed, 200–300 words |
| Why the gap exists | `fld8Nba0rjjaV3Wh1` | Strategy/Wedge via CEO |
| People (link) | `fldAoArBs15TDYYX4` | inverse of People to talk to → Idea |
| Rounds (link) | `fldZzoYAPXPFm2Yxv` | inverse of Rounds → Idea |
| Tests (link) | `fldo4Oonz1a3W8BBu` | inverse of Tests → Idea |

## Rounds `tblcsUvJFKSlCNpqr`
Round `fldiXU42jqiEuxYpr` ("<Idea> – R<n>") · Idea `fldgbsp7Ho0HJ1Tye` · Date `fldDKwzEbR4uf8NcB` · Question `fldw4OOWwzvehvJRb` · CEO brief `flddzQX4WoHB1Ftrf` · CFO `fldh1mer7H0IIBDVX` · CTO `fldwa39l4dkkTzLKG` · CSO (science) `fldbL54OL7OOyq6eC` · Strategy `fldaLJiEsWF7oEDla` · Go-to-Market `fldxnevmd4Mc1yJZl` · Wedge `fldBmZre5fVgoDHZI` · CEO synthesis `fldQ47YNEh6juZIln` · Audit verdict `fldCRq0FuHWu17JYH` (Fund the test · Fund with changes · Don't fund yet) · Audit notes `fld1hkG8tlt1tQlSx` · CEO rebuttal `fldohLDXZTpmxsR2a` · Decision `fldMWjQ1BJ7FDXE15` (Keep going · Pivot · Park · Kill – **Ross only**) · Decision note `fldfcuJIEfnjGw2hK`

## Tests `tblDo3juAAKfgzUsb`
Test `fldUX3edVgPWjFgxi` · Idea `fldYTOqQV0FQbqrHq` · Assumption tested `fldrvV6F8sUs35H9G` · Method `fldoiQxln5EfVTbYW` · Pass criterion `fldi1DJmOzjPNxLS6` · Kill criterion `fld7M3UmiOfUXdSy5` · Cost cap `fldp1l5zk0suNU3Dc` (€, **Ross only**) · Time box (days) `fldjdUx52AvB4E803` · Owner `fldJr0zMsyCgAM3Sl` · Status `fldfO61F68OhHt4rA` (Proposed · Running · Done · Dropped) · Start `fldFlP6jdH69eojwY` · Due `flde2XvY5PF56Dtmg` · Result `fldc9gOqMYGkvWOy1` (Passed · Failed · Inconclusive) · Learning `fld5tIyeC9uvrRRkS` · Actual cost `fld7PRQrr9gwLT7kl`

## People to talk to `tbls0CAuRt0IIKYhl`
Name `fldkKYHF0FcxiiMxn` · Idea `fldFGoG2iM0OfTzUi` · Organisation `fld6smAouslrid8iy` · Role `fld7PTFLATiuu9Lom` · Type `fldfV2149zx8XDdqX` (Potential customer · Domain expert · Scientist · Competitor or ex-competitor · Channel or partner · Investor) · Question to ask `fldX5unNZiUnVulrE` · Why them `fldDXGAWX3M8eb5lJ` · Source `fld0XBIaRJH9bX6gL` (url, required) · Route in `fld3f2ylfTqHTgvv0` (Warm intro · Ross knows them · LinkedIn · Email · Event) · Suggested by `flduUgdKZUZyL6tOy` · Status `fldBAzAE5uuPpJBYf` (Suggested · Approved · Contacted · Met · Not pursuing – **Ross only** beyond Suggested) · Learning `fldd0pyP56ZYn38BZ` · Met on `fldwbr4HJRYJaWOot` · Rank `fldN8vBcwnh8mavXz` (order within the idea)

## Write rules
- New Ideas (on "new idea: X"), Rounds, Tests and People to talk to rows: agents may create.
- Existing rows: no edits or deletes without Ross's explicit instruction in the chat. Exception (Ross, 20 Nov 2026): agents keep Ideas → Round status, Open decision, NABC, Explainer, Why the gap exists, Wedge verdict and People → Rank current, and record Ross's ticked answers (Decision, Status) on the rows they concern.
- Fields marked **Ross only** are filled from his tick-box answers, never by an agent's judgement.

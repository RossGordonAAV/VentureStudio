# Roadmap – Statiegeld can tube – Lab 1 (21 Nov 2026)

| | V1 – off the shelf | V2 – custom | V3 – volume |
|---|---|---|---|
| Purpose | Cluster stands, seals, empties fast; good enough to photograph and list | Looks like a homeware product; sellable at a premium in 10–50 units | Better look at lower unit cost; ships without long-parcel surcharge |
| Make route | Ecomar 75 mm PVC, glued socket + Martens screw-cap end stop, sprayed anthracite, 2 straps, IKEA bamboo board | Same tube (Ecomar sprayed, or Marley anthracite), laser-cut layered base (Snijlab/Laserlokaal), FDM top collar + handle (Hubs) | Factory-coloured stock tube split in two with stock sleeve; one moulded base + collar (snap fit); flat-pack |
| Unit cost (sourced) | €93.16 first cluster; €61.69 hard parts per unit (listed prices, 21 Nov) | End stop €2.89–3.90; pipe €5.18/m (Marley); base/collar/handle quote needed | Quote needed (tube at volume, mould, moulded parts) |
| Set-up cost | None beyond consumables | CAD files – who draws them [Ross: confirm] | Mould quote needed (Protolabs EU / Asia) |
| Lead time | Same day – collect | ~1 week (laser 1 day + post; FDM ~1–3 days) | 3–6 weeks tube (Alumil); mould quote needed |
| Look vs previous | "Nicely painted drainpipe" | Finished product look, handle, hidden sockets | Factory colour, no paint, moulded parts |
| Gate to next | Can drops through end stop; 1 week home use without tipping/drips; ≥1 stranger asks to buy (Marktplaats) | Paid reservations from strangers at test price [Ross: confirm number] and a V3 tube/mould quote that works | — |

## Browser checks (21 Nov, Praxis stock checker)
- **Ecomar 75 mm 1 m, €7.99:** Amsterdam Oost (Molukkenstraat 190) 11 in stock; Van Swindenstraat 1; Trompenburgstraat none. Praxis lists Ecomar 75 mm also in 2 m and 4 m → **cut to 1,170 mm, 10 cans per tube** (V1 agent's 9-can limit falls away). Ask in store for the 2 m length.
- **Martens 75 mm eindstop met schroefdeksel, €3.90:** Amsterdam Oost 5; Trompenburgstraat 4; Van Swindenstraat none.
- Thick-walled 75 × 3–3.2 mm pipe (Gamma RIO, Hornbach dikwandig) → bore ~69 mm, below the 70.6–71 mm spec. Avoid.

## Where the agents disagree
- **Tube:** V2 and V3 favour Marley anthracite (factory colour) but its wall/bore isn't published and delivery is 6 working days. Decision: Ecomar sprayed for V1 and first V2 units; measure Marley bore before V3.
- **Splitting the tube (V3):** cuts shipping by ~€4.85/parcel but adds a joint the cans must pass. Test with one sleeve now – cheap.

## Design choices that carry through
- Keep the 75 mm OD / ~71 mm bore family – stock pipe, sleeves and end stops all fit.
- 3-tube triangle footprint and 1,170 mm length fixed now; base and collar in V2 are drawn to the same hole pattern the V3 mould would use.
- Bottom = Martens screw-cap end stop until volume justifies an own cap.

## Showstopper (check first, in store)
Does a 66 mm can drop through **socket + end stop with the cap off**? Opening isn't listed anywhere. Take a 330 ml can to Praxis Amsterdam Oost.

## Minimum next build
- **What:** 1 V1 cluster (3 × 1,170 mm tubes from 2 m or 4 m Ecomar). Optional: 1 Marley sleeve + offcut to test the V3 joint.
- **Where:** Praxis Amsterdam Oost (pipe, end stops, lids), Gamma Slotervaart (sockets, glue, primer, paint, brackets – click & collect), IKEA (board), Action (straps).
- **When:** buy Sat/Sun, paint Sun, photograph and list Mon 23 Nov; one Tomra run by Sat 28 Nov.
- **Cost cap:** [Ross: confirm]. **Owner:** Ross.

## Quotes to request (after V1 passes)
Snijlab/Laserlokaal (base, 10 and 50 sets) · Hubs/Xometry (collar + handle, FDM 10, MJF 50) · Marley/Martens wholesaler (anthracite tube cut, wall thickness, 1k/10k) · Protolabs EU + one Asia moulder (base + collar family mould) · MyParcel (flat-pack box rate).

## V1 revised – simplest first (Ross, 21 Nov 2026)
Ross: the first V1 was over-designed. New V1:
- **Tube:** Marley regenpijp Ø75 anthracite, 2.5 m (Hornbach, €12.95) → 2 tubes of 1,170 mm per length; 2 lengths for a 3-tube cluster. Bore not published – measure. **Online only:** no Amsterdam-area branch stock (Sloterdijk, Zaandam), home delivery €62.50, 6 working days (Hornbach site, 21 Nov).
- **Bottom:** push-on cap, as on the home prototype.
- **Base – compare two:** (a) wooden board with three 76 mm holes (hole saw, DIY store, same day); (b) 3D-printed base – Claude can draw the file once the cap's outer diameter is measured.
- **Dropped:** paint, primer, sockets, glue, straps, brackets.

## V1 revised – final shopping list (21 Nov 2026, browser-checked)
Hornbach Marley anthracite is online only (€62.50 delivery, 6 days) – dropped. Gamma stocks anthracite in 80 mm instead:
- **Tube:** Martens HWA buis antraciet Ø80 mm, 4 m, €18.69 – wall 1.5 mm (Gamma BE spec) → bore ~77 mm. Cuts into exactly 3 × 1,170 mm. In stock today: Gamma Amsterdam-Overamstel (Spaklerweg 44) 11, Amsterdam-Noord (Klimopweg 65) 6, Willem de Zwijgerlaan 1. Open until 18:00.
- **Bottom cap:** no anthracite 80 mm cap found. Grey Martens eindkap om de buis HWA 80 mm (~85 mm across, 22 mm high; Hornbach €1.49 – check Gamma aisle). Hidden by the base.
- **Trade-off (Believed):** 77 mm bore vs 66 mm can = ~5.5 mm radial gap; the air-cushion descent of the 75 mm prototype will be weaker. Cans can't turn over (115 mm tall). Test with the first tube.
- **Bases:** wooden board with three holes sized to the capped end; 3D-printed base – Claude draws once Ross gives the cap's outer diameter.

# CTO – Statiegeld can tube – R1 (20 Nov 2026)

**Core technical risk:** Not making the tube – that is off-the-shelf pipe. The risk is the base and cap (drip seal, stability, finish) looking like a retail product rather than drainpipe, at ~100 units without paying for tooling. A second risk sits outside the product: the return machines may change.

**What the machines need (Known):**
- Cans must keep their shape and the barcode must be readable. Small dents are fine; flattened cans are rejected ([Hart van Nederland](https://www.hartvannederland.nl/advies-en-tips/kopen-besparen/artikelen/vanaf-nu-statiegeld-op-blikjes-maar-niet-elk-blikje-wordt-geaccepteerd-waar)). Uncrushed storage is a real need.
- Tomra T9: up to 60 containers per minute, with 360° recognition ([Tomra](https://tomra.com/reverse-vending/our-offering/reverse-vending-machines/tomra-t9)). Feeding 10 cans one after another from a tube is within spec. **Believed.**
- Wet or rinsed cans: no source says they are rejected. Statiegeld Nederland's advice is to shake cans empty, and to keep the barcode visible if you rinse them ([MAX Vandaag](https://www.maxvandaag.nl/?p=153494)). Shops report leaking drink residue and sticky floors ([NOS, 2023](https://nos.nl/l/2478991)). A sealed drip cap is a genuine plus. **Believed.**
- **Platform risk:** bulk machines that take a whole bag at once are being trialled in NL ([IO+, Dec 2024](https://ioplus.nl/en/posts/first-bulk-machines-for-faster-recycling-of-deposit-cans-installed-in-the-netherlands)). The cabinet wants them to play a bigger role from 1 Jan 2028 ([Rijksoverheid, Sep 2026](https://www.rijksoverheid.nl/actueel/nieuws/2026/09/04/kabinet-stelt-makkelijker-statiegeldsysteem-voor)). That weakens "fast feed" as a selling point. Storage, odour and drips remain the value. **Known/Believed.**

**Routes to a sellable batch of ~100 units**

| Route | What it involves | Time to demo | Main risk | Cost driver |
|---|---|---|---|---|
| **A. DIY-grade kit (Recommended)** | Stock 75 mm PVC pipe, e.g. Martens Ecomar, sold by the metre in DIY stores ([Praxis](https://www.praxis.nl/bouwmaterialen/waterafvoer-riolering/rioleringsbuizen/martens-pvc-buis-ecomar-75mm-1m/0635839)), cut to 1,170/1,520 mm. Off-the-shelf screw-cap end piece. 3D-printed base and collar: FDM (PETG/ASA) in 1 day, or MJF/SLS in 3 days, which Hubs pitches for low-run production ([Hubs](https://www.hubs.com/3d-printing/netherlands/amsterdam/)). | 1–2 weeks | Looks like plumbing; finish of the base | Labour to cut and assemble; print time per base |
| B. Premium aluminium | Aluminium tube (EN AW-6060) sawn to the mm, with anodising or powder coating offered ([AluminiumOpMaat brochure](https://www.aluminiumopmaat.nl/media/brochures/AOM_Brochure_2026.pdf); 76 mm size not confirmed – quote needed). Ribbed plug plus oak or printed base. | 3–4 weeks | Unit cost (Ross's own estimate was €45–65 per tube) and oversize shipping | Tube, finishing, shipping |
| C. Moulded base | Single-cavity aluminium prototype mould, "typically delivered in a week or less" ([Protolabs](https://www.protolabs.com/en-gb/resources/design-tips/comparing-cost-between-injection-moulding-and-3d-printing/)). Protolabs gives no tooling price: [Ross: confirm via quote]. | 4–6 weeks including design | Paying for tooling before willingness to pay is proven | Mould |

Do C only after A has sold. Polycarbonate tube (a see-through fill level) was not found off the shelf in NL DIY stores – not found.

**Fake it first:** Build 5–10 Route A units by hand this week. Photograph them in a kitchen and put up a pre-order or "notify me" page at two price points (price is for the CMO/CFO seats). Lend 3 units to households for two weeks and record smell, drips, tipping and trips to the machine. No tooling, no stock.

**Safety and stability:** A 1.2–1.5 m tube with a 75 mm footprint will tip (Ross saw this). Sell it as a 3–4 tube cluster, or with a wall bracket only. The EU GPSR applies from 13 Dec 2024: it requires an internal risk analysis, technical documentation, traceability information on the product or packaging, and a complaints contact ([EUR-Lex](https://eur-lex.europa.eu/EN/legal-content/summary/general-product-safety-regulation-2023.html)). Food-contact rules don't apply, because the product only holds empty packaging. **Believed.**

**IP note:** A function made from a standard pipe is not worth patenting. The look of the base and collar can be protected by a Benelux design registration at €150 for 5 years ([BOIP](https://www.boip.int/en/entrepreneurs/designs/fees)). Copycats are easy, so brand and channel are the moat. **Believed.**

**Smallest test that changes the decision:** Take 10 cans from a home-made tube to an AH or Jumbo Tomra machine, feed them in one after another, and count rejects. Then build 5 kits.

## People to talk to

| Name | Organisation | Role | Type | Question to ask | Why them | Source URL | Route in |
|---|---|---|---|---|---|---|---|
| René Hissink | Tomra (NL) | Director (per NOS, June 2023 – check current role) | Industry – incumbent | "Will bulk-feed machines replace single-feed can returns in NL supermarkets by 2028, and do residue or wet cans cause rejects or faults?" | Runs the market-leading machine supplier; can say whether the tube's return-machine logic survives 2028 | https://nos.nl/l/2478991 | LinkedIn / Tomra NL switchboard |
| Pieter van Essen | Aldi (NL) | Project manager, POS Experiences | Industry – retailer | "What did your bulk-machine test in Dordrecht show about how customers bring cans in, and would you stock or display a return tube?" | Ran the in-store bulk-machine test; sits close to both the return behaviour and the retail shelf | https://ioplus.nl/nl/posts/eerste-bulkmachines-voor-snellere-recycling-statiegeldblikjes-genstalleerd | LinkedIn |

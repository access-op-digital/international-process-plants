# Diagnostic Reasoning — "buy used reactors" (IPP)

Run per `methodology/DIAGNOSTIC-REASONING-ENGINE.md`. Client: International Process Plants (IPP).
Business model as specified by operator: **B2C e-commerce**. See "Model conflict" note at the end.

---

## STAGE 1 — ENTITY IDENTIFICATION

**1.1 Entity class:** Physical product — industrial capital equipment traded on the *secondary* market.
Not a service, not a fabrication engagement. The vessel already exists, sits at a known site, and carries
a fixed stock number. This matters: the attributes are hard specs (capacity, MOC, pressure, temperature,
dimensions, condition), not capabilities or tolerances a fabricator *could* hit.

**1.2 Buyer and relationship:** A process engineer, project engineer, or procurement specialist at a
chemical, pharmaceutical, or food manufacturer. They **deploy it for an organization** and frequently
**evaluate it for someone else** (a plant manager, a capital committee). They therefore care about
specs, material compatibility, pressure envelope, and documentation — not brand feeling. A spec that
doesn't match their service condition kills the deal instantly, so spec density beats persuasion.

**1.3 Intent verb → "buy".** Applying the test in 1.3: does "buy" completely describe the user's action?
Here, yes. The vessel is sold as-is; there is no installation engagement, no fabrication, no subscription.
The transaction *is* the purchase. This is confirmed by IPP's own navigation, which uses the literal label
**"Buy Used"**, and by the target query itself ("buy used reactors"). Unlike patio covers or CNC work,
"buy" is not a forced e-commerce verb here — it is the industry's own word.

Supporting lemma forms in use: buy / buying / bought / purchase / purchased / purchasing.

**1.4 Conversion endpoint:** **Quote/RFQ against a stock number.** IPP publishes no prices anywhere in the
IMS inventory — every listing reads "Price: Not listed." The page must therefore convert to a quote request
tied to a specific stock number, even though the intent word and CTA language stay purchase-flavored.

---

## STAGE 2 — ATTRIBUTE EXTRACTION

**2.1 What the buyer RECEIVES (deliverable attributes)**
Reactor vessel with: design capacity (L and gallons) · material of construction, internal and jacket ·
internal pressure and temperature rating · jacket pressure and temperature rating · diameter ·
straight-side length · support type (lugs) · condition grade · stock number · agitation system or
body-only · accessories (manhole with davit arm, sight glass, thermowell, dip pipe, insulation rings,
sheathing) · interior finish (e.g. 240-grit buff polish) · ASME / National Board rating and "U" stamp.

**2.2 What the buyer EXPERIENCES (process attributes)**
Search inventory by equipment type → filter by material of construction (69 options) and condition
(8 grades) → identify stock number → request quote → unit is inspected, documented and prepared for
transport → ships within 2–4 weeks of purchase from one of 20 global sites → delivery to over 110 countries.

**2.3 What the buyer SPENDS (cost attributes)**
40–60% below new prices. Capital costs cut by up to 70%. No unit prices published — every listing is
quote-only. Cost drivers implied by inventory: material of construction, capacity, condition grade
(unused vs used vs needs-reglass), whether agitation is included or body-only, pressure rating.

**2.4 What the buyer RISKS (risk attributes)**
Wrong MOC for the corrosive service. Insufficient pressure or temperature envelope. Glass damage requiring
reglass. Missing ASME stamp, blocking regulated use. Missing cGMP documentation, blocking pharma use.
Body-only purchase with no agitator drive. Unknown provenance. Long import/logistics tail on an overseas unit.

**2.5 OUTCOMES achieved**
Production comes online in 2–4 weeks instead of 6–12 months. 24+ week fabrication delays are eliminated.
Capital is preserved for process rather than consumed by the vessel. Regulated-industry compliance is
maintained through documentation carried with the unit.

**2.6 PROOF that carries weight in THIS industry**
ASME rating · National Board registration · "U" stamp · cGMP compliance · FDA-inspected facility provenance ·
named OEM pedigree (Pfaudler, De Dietrich) · material of construction stated to grade (316L, 316Ti, Hastelloy C,
Inconel, titanium) · units inspected and documented before transport · 47+ years · 160,000 customers ·
20 global sites · 15 countries · delivery to 110+ countries.

**Proof that does NOT matter here:** star ratings, press mentions, "award-winning," founding-year nostalgia,
customer-count-as-hype. A process engineer buying a 4,000 gallon reactor does not care about a Trustpilot score;
they care whether the vessel is U-stamped and whether 316L survives their process stream.

---

## STAGE 3 — ATTRIBUTE FILTRATION

```
PRIORITY 1 (Intro/Hero):   Material of construction + capacity range  (does it fit my process?)
                           Availability / lead time  (2–4 weeks vs 6–12 months)
                           Cost position  (40–60% below new)
PRIORITY 2 (Tabs):         Reactor type × material — batch-type agitated, hydrogenation,
                           glass-lined bodies, and the remaining stocked types
PRIORITY 3 (Cards):        Per-unit hard specs — stock #, capacity, MOC, pressure/temp, dimensions, condition
PRIORITY 4 (Benefits):     Schedule compression, capital preservation, compliance documentation, global logistics
PRIORITY 5 (FAQ):          Reglassing, condition grades, ASME/cGMP documentation, shipping and import,
                           inspection scope, agitators and accessories
EXCLUDED:                  Generic "high quality / trusted / professional" language; founding-year filler;
                           consumer-style review hype; any price the source does not publish
```

**Why cost is Priority 1 despite being a quote-only business:** the only two cost claims IPP publishes
(40–60% below new, up to 70% capital reduction) are *comparative*, not absolute. They function as the price
anchor without committing to a number, which is exactly what the intro needs.

---

## STAGE 4 — LANGUAGE CALIBRATION

**4.1 Trust currency:** ASME "U" stamp, National Board rating, cGMP compliance, FDA-inspected facility
history, OEM pedigree, stated material grade. NOT reviews, awards, or press.

**4.2 Insider differentiating terms (used throughout the page):**
material of construction (MOC) · straight side · dished bottom · jacket coverage · half-pipe · full vacuum (FV) ·
reglassed · good used glass · needs reglass · "U" stamp · National Board · 240-grit buff polish · baffles ·
lug support · davit arm · thermowell · dip pipe · sheathing · body only · austenitic clad · 316Ti.

**Rejected generic phrasing:** "high-quality used reactors," "reliable process vessels," "trusted equipment
supplier." A process engineer learns nothing from these.

**4.3 Natural action-outcome verbs:** *rated to · holds · ships within · is stamped · is reglassed to ·
cuts capital cost by · eliminates fabrication delay · fits · handles · survives.*
NOT "improves," "enhances," "delivers quality."

**4.4 Natural comparisons (these become tabs and FAQ questions):**
glass-lined vs 316L vs Hastelloy/Inconel · used vs new · reglassed vs good used glass vs needs reglass ·
complete unit vs body only · batch vs continuous (tubular/fixed bed) · domestic vs overseas site.

**4.5 Cheap vs premium in this niche:**
*Cheap* = needs reglass, body only, no agitator drive, no documentation, carbon steel with lining.
*Premium* = unused or reglassed, ASME NB "U" stamped, 240-grit polished interior, complete with agitation,
cGMP documented, high pressure envelope.

---

## STAGE 5 — STRUCTURAL ASSEMBLY

**5.1 H1:** "Buy Used Reactors — Glass-Lined, 316L and Alloy Vessels In Stock at IPP"
(intent verb from 1.3 + entity + MOC modifier from 4.5 + brand)

**5.2 Intro:** SAP formula, B2C ordering — outcome first (2–4 weeks vs 6–12 months), then materials and
capacity range, then the comparative cost anchor. Every sentence an SPO triple.

**5.3 Tab categories** (from the natural divisions in IPP's own inventory taxonomy):
L1 by reactor type — Batch-Type Agitated | Hydrogenation | Glass-Lined Bodies | More Stocked Types.
A second tab system splits by material of construction — Glass-Lined | Stainless 316L | Alloys | Carbon Steel Lined.

**5.4 Card contents:** real stocked units, one card per stock number, carrying capacity, MOC, internal and
jacket pressure/temperature, dimensions, support type and condition.

**5.5 Centerpiece annotation:** stock **#232498** — 4,000 gallon Gale Process Solutions 316L, unused,
ASME NB rated and "U" stamped with 240-grit polished interior. It is the largest, best-documented and
only U-stamped unit in the set, so it earns the badge. Secondary centerpieces: the 1,200 psi hydrogenation
unit (#217847) in its tab, and the reglassed 5,000 gallon Pfaudler KC (#238184) in its tab.

**5.6 FAQ tabs (6):** Buying | Materials | Condition & Reglassing | Documentation & Compliance |
Shipping & Lead Time | Other Equipment.

**5.7 Benefit cards** (from 2.5 outcomes, written with 4.3 verbs): Schedule Compression · Capital Preservation ·
Documented Compliance · Global Logistics · Inventory Breadth · Inspection Before Transport.

**5.8 Pricing placement:** Comparative anchors only (40–60% below new, up to 70% capital cut) in the intro
and in a dedicated cost section. **No per-unit prices** — IPP publishes none, so inventing them is forbidden.

**5.9 Commercialization rhythm:** Hero → trust bar → inventory tabs → cost section → CTA → material guide →
benefits → process → CTA → FAQ. A CTA, stat block, or selector appears at least every 2–3 sections.

---

## MODEL CONFLICT — flagged for the reviewer

The operator specified **B2C e-commerce**, which normally requires visible prices in the intro and on every
card. **IPP publishes no prices at all** — every IMS listing reads "Price: Not listed."

Resolution applied: the *intent word and CTA register* stay purchase-flavored ("Buy," "Buying," "Buy This
Reactor"), which is correct for the query and matches IPP's own "Buy Used" navigation. The *price mechanics*
fall back to the guided-pricing model from Framework Part 13 — comparative anchors that IPP genuinely
publishes, plus per-unit "Request Quote on #stock" CTAs. Nothing was invented to satisfy the B2C pattern.

Functionally this page is a **quote-based hybrid**. If the reviewer wants true B2C mechanics, IPP must
supply per-unit asking prices.

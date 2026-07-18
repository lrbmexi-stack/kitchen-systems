# A Working R&D Cycle

**Generalized methodology. No live menu development appears in this document.**

Dish development in a working restaurant is not inspiration management. It is a process with steps, timeboxes, and a kill switch. The version below is the cycle I run. It borrows from the kitchens that formalized culinary R&D and compresses their practice to fit a restaurant that has to run service every night while it develops.

## The Lineage

- **Ferran Adria / elBulli:** ran six months closed, six months open. The closed half was pure R&D at the Taller in Barcelona, cataloguing technique in a structured library. The principle that matters: creativity is a process, not a moment.
- **Rene Redzepi / Noma:** a dedicated fermentation lab inside the restaurant. The structural insight: an R&D lab is a kitchen station that does not run service.
- **Thomas Keller / The French Laundry:** recipe development by tasting and re-tasting against a fixed target. Iteration against an explicit benchmark, not toward a vague better.
- **Daniel Humm, Grant Achatz:** formal weekly creativity meetings with the senior team. The Alinea pipeline is documented: concept, sketch, component R&D, plating mockup, tasting panel, menu trial, refinement.

Most restaurants cannot close for six months or staff a lab. The cycle below is what that discipline looks like scaled to a kitchen that cooks for guests seven services a week.

## The Seven Steps

### 1. Brief (1 hour)
What problem is this dish solving? One sentence. A gap in the menu mix, a price point, a season, a station that needs a faster item. If the brief cannot be stated in one sentence, the dish is a hobby, not a project.

### 2. Reference scan (1 to 2 hours)
What do peer restaurants do with this ingredient or technique? Not to copy. To know where the field is, what reads as familiar, and where the open space sits.

### 3. Component prep
Each component developed independently, each with its own cost and yield card from day one. Costing is not a step that happens after the food is good. A component that cannot be costed cannot be judged.

### 4. Plate-up tasting
Fixed panel: chef, sous, one line cook from the station that will run the dish, and a front of house lead. Score three things separately: components, integration, and the only question that predicts sales: would I order it again. The line cook's vote matters because they will cook it two hundred times.

### 5. Cost and spec sheet
Final recipe card with quantities in grams, plate diagram, allergen flags, mise list, food cost, target price, contribution margin. The dish does not exist until this document exists.

### 6. Soft launch
Run it as a feature for one to two weeks before it touches the printed menu. The feature run answers what no tasting can: execution speed under fire, ticket time impact, guest reorder behavior, and whether the dish survives the sixth consecutive service.

### 7. Post-mortem
After 30 days on menu, re-run the menu engineering numbers (Kasavana and Smith, see `../costing-framework/methodology.md`). Three verdicts, stated out loud: keep, re-engineer, or kill. No zombie dishes. A dish nobody will kill and nobody will fix is paying rent with your margin.

## Technique Reference

The food science that backs development decisions. All of it public science with public sources; the value is having it compressed and operational.

### Maillard and browning
Non enzymatic browning between amino acids and reducing sugars, initiating rapidly between 140 and 165 C (Maillard 1912; McGee, *On Food and Cooking*). Surface moisture is the enemy: until surface water evaporates, surface temperature caps at 100 C, below Maillard initiation. Operational rules: dry the surface; salt well ahead or immediately before searing, avoiding the middle window where moisture is drawn but not reabsorbed; sear above 232 C. Maillard needs protein plus reducing sugar; caramelization is sugar alone, and different sugars caramelize at different temperatures, which is why a honey glaze and a cane sugar glaze brown differently.

### Reverse sear
For thick cuts, 38 mm and up: cook low (120 to 135 C) until internal temperature sits well below target, then finish on screaming hot cast iron or live fire. Edge to edge doneness, drier surface, reliable pull temperatures. Not appropriate for thin cuts.

### Resting meat
The lock in the juices story is a myth. Resting matters because carryover finishes the center and relaxing muscle fibers reabsorb expelled liquid. Rule of thumb: about 5 minutes per inch of thickness, tented loosely. A tight cover steams the crust you just built.

### Dry aging versus wet aging
Peer reviewed consensus: roughly three weeks of dry aging captures the tenderness gain; flavor keeps developing for months after tenderness plateaus. Yield losses are real and must be costed: shrink plus trim. Wet aging delivers comparable tenderness without flavor concentration or yield loss, which is why most aged claims at the mid market are wet aged unless stated otherwise. Know which one you are buying before you write menu copy.

### Acid curing (ceviche)
Acid denatures protein the way heat does: texture firms, flesh turns opaque. Cure speed scales with acid strength, dice size, and the fish itself. Lean delicate species cure fast and overshoot into chalky; the cure window is a spec, not a suggestion. This is the operative science in the worked example in `../dish-documentation/`.

### Fermentation, the four pillars
Working parameters from the published canon (Redzepi and Zilber, *Noma Guide to Fermentation*; Katz, *The Art of Fermentation*):
- **Lacto fermentation:** 2% salt by total weight, 18 to 24 C, 4 to 14 days. Clean bright acidity. Fruit and vegetable applications scale to any region's pantry.
- **Koji:** grain inoculated with *Aspergillus oryzae*, 30 to 32 C at high humidity, 42 to 48 hours. Shio koji as a brine or cure delivers real tenderization through proteolytic enzymes plus glutamate depth.
- **Miso family:** koji plus cooked legume plus salt, six months minimum at room temperature. Non soy variants (pea, hazelnut, fava) let a kitchen build house flavors.
- **Garum:** fermented protein, 12% salt, koji, warm held for weeks or room temperature for months. Extends far beyond fish.
- **Vinegar:** wine or cider plus mother plus oxygen, 4 to 6 weeks. House vinegars deliver acid profiles you cannot buy.
- Quick pickles (vinegar brine, 24 hours) preserve crunch and color; lacto pickles (7 to 21 days) develop sour complexity. They are different tools, not competing versions of one.

### Sauce and emulsion science
- **Stocks:** collagen converts to gelatin from about 70 C, accelerating through 82 C. Full extraction needs sustained time in that band.
- **Beurre blanc:** the emulsion breaks at 58 C because the milk fat globule membranes that stabilize butter fail above it. Working window 45 to 50 C. Clarified butter does not work; the emulsifiers live in the non fat fraction. Recovery from a break: cool to about 43 C and whisk in cold water. For volume service, beurre monte (butter into hot water) holds far hotter because the water phase dominates.
- **Vinaigrette:** 3:1 oil to acid, mustard as the workhorse emulsifier. Lecithin and a trace of xanthan when a plated viscosity has to hold.
- **Modern thickeners, operational doses:** xanthan 0.1% light body, 0.2 to 0.5% sauce body, past 0.5% turns ropy. Agar fluid gels 0.5 to 2.0%. Soy lecithin airs 0.3 to 0.8%. Methylcellulose gels on heating, which makes it the vegetarian binder. Doses are percentages of liquid weight; weigh, never eyeball.

### Reference library
- Harold McGee, *On Food and Cooking* (2004). The standing food science reference.
- J. Kenji Lopez-Alt, *The Food Lab* (2015). Applied food science.
- Rene Redzepi and David Zilber, *Noma Guide to Fermentation* (2018).
- Sandor Katz, *The Art of Fermentation* (2012).
- Myhrvold et al., *Modernist Cuisine* (2011). The exhaustive technical reference.

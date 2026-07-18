# Kitchen Costing Framework

**DRAFT. All numeric examples in this document are illustrative.**

None of this is proprietary and none of it is new. This is standard food and beverage cost control practice, refined across a century of hotel and restaurant accounting, taught in every serious hospitality program, and codified in the classic cost control texts. What follows is the working version: the parts a chef actually uses week to week, written the way they get used.

## 1. AP versus EP

The foundation of every honest food cost number.

- **AP (As Purchased):** what the invoice says. The whole fish, the case of tomatoes, the untrimmed strip loin.
- **EP (Edible Portion):** what actually reaches the plate after fabrication. Skinned, trimmed, peeled, portioned.
- **Yield %:** EP weight / AP weight.
- **EP cost = AP cost / yield %.**

A fish that costs $20.00 per kg AP at 50% yield costs $40.00 per kg EP. Illustrative numbers, real math. Kitchens that cost recipes at AP prices are lying to themselves by exactly their yield loss, and yield loss on proteins routinely runs 20 to 50 percent.

## 2. Yield Testing

Yield percentages come from tests, not from tables. Butcher yield test procedure:

1. Weigh the item AP, exactly as invoiced.
2. Fabricate it the way your kitchen actually fabricates it. Same knife work, same specs.
3. Weigh every output stream: usable portions, usable trim (grind, stock, staff meal), waste.
4. Yield % = primary usable weight / AP weight. Credit usable trim at its own value if you actually use it. If it goes in the trash, it is waste no matter what you tell yourself.
5. Repeat across at least three deliveries before trusting the number. Suppliers vary, seasons vary, the same species varies.

Re-test when the supplier changes, the spec changes, or the person fabricating changes.

## 3. Recipe Costing Rollup

Every menu item is costed from a sheet with this structure:

Ingredient | Prep | EP quantity | Unit | AP cost | Yield % | EP cost | Extension

- Extension = EP cost x EP quantity.
- Recipe cost = sum of extensions.
- Portion cost = recipe cost / portions per batch.
- Sub recipes (sauces, pickles, compound butters, stocks) get their own sheets and enter parent sheets as a single EP cost per unit. One level of truth per sheet. A costing sheet that inlines a sub recipe's ingredients will drift from the sub recipe's own sheet within a month.
- Zero cost lines (byproducts, brines) stay on the sheet at zero. The sheet documents decisions, not just prices.
- A Q factor (an allowance for salt, pepper, oil, and the incidentals no one weighs) keeps small stuff honest. A flat few percent or a fixed cents allowance per plate both work. Pick one and apply it everywhere.

See `../dish-documentation/costing.md` for the full worked example and `../templates/costing-template.md` for the blank.

## 4. Food Cost Percentage

- **Food cost % = portion cost / menu price.**
- **Price at target = portion cost / target %.**
- Targets vary by category and concept. Common working ranges: high volume casual runs tighter, premium protein categories run looser because the contribution margin in dollars is what pays rent. A 40% food cost steak that contributes $22 beats a 25% food cost pasta that contributes $9.
- The percentage is a screening tool. Contribution margin (price minus portion cost) is the number that survives contact with the P&L.
- Cost every candidate price point on the sheet. Pricing conversations go better against a table than against feelings.

## 5. Menu Engineering

The Kasavana and Smith matrix (1982). Plot every item on two axes: popularity (menu mix share against expected share) and contribution margin (against the menu average).

| | High popularity | Low popularity |
|---|---|---|
| **High margin** | **Stars.** Protect them. Never touch what makes them work. Feature placement. | **Puzzles.** The money is there, the sales are not. Reposition, rename, have servers sell them, move them on the page. |
| **Low margin** | **Plowhorses.** People love them, they barely pay. Re-engineer the cost, nudge the price, or shrink the plate cost without shrinking the experience. | **Dogs.** Kill them, or keep one deliberately for a reason you can state out loud. |

Run the matrix on real sales mix data at a regular cadence, and 30 days after any menu change. Every new dish gets a scheduled re-run as part of its post launch review (see `../rd-cycle/methodology.md`).

## 6. Inventory Cadence

Costing sheets are half the control loop. Inventory closes it.

- **Par levels:** for every stocked item, the quantity that covers the order cycle plus a safety buffer. Pars are written down, reviewed seasonally, and adjusted for menu changes. A par in someone's head is not a par.
- **Order guides:** ordering happens against a standing guide (item, unit, par, on hand, order quantity), not from memory walking the walk in. The guide is also the receiving checklist: weight and spec verified against invoice at the door.
- **Physical counts:** full count at period end, high value items weekly or better. Same counting order every time, sheet to shelf, so misses are systematic and findable.
- **Cost of goods sold:** beginning inventory + purchases − ending inventory = usage. Usage / sales = actual food cost %.
- **Variance:** actual food cost % versus theoretical (what the costing sheets say the sales mix should have consumed). The gap is waste, portioning drift, theft, or stale costing sheets. The variance number does not tell you which. It tells you where to go look.

## 7. The Loop

Yield tests feed costing sheets. Costing sheets feed menu prices. Sales mix feeds menu engineering. Inventory variance audits the whole chain. Any document in the loop that goes stale poisons the ones downstream. That is why this is a documentation system and not a stack of spreadsheets someone made once.

## Lineage

Standard references for the practice, for anyone who wants the long form: the classic food and beverage cost control texts (Dittmer and Keefe; Miller, Hayes, and Dopson), the CIA's professional chef curriculum on costing and yield, and Kasavana and Smith, *Menu Engineering* (1982). This document is a practitioner's compression of that body of work, not a replacement for it.

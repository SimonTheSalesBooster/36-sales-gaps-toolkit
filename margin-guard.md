---
name: margin-guard
description: "Quick calculator and checklist: can this deal be won at an acceptable margin, or does scope need to change, or should we walk. Addresses the Contract Gap: the business can be won, but we cannot achieve an acceptable margin."
user-invocable: true
---

# /margin-guard: Margin Viability Checklist

## Why This Skill Exists

Contract Gap #2 (the business can be won, but we cannot achieve an acceptable margin) is the gap that turns a "win" into a loss. The canonical mitigation is blunt: walk away, or change scope until the math works. Never win a deal that loses money. This skill runs the calculation and forces the explicit call.

## Step 1: Get the Numbers

Ask for whatever is known (if not already given): proposed price, estimated delivery cost (time x rate for everyone involved, plus any hard costs), and any other out-of-pocket exposure required to deliver (Contract Gap #7).

## Step 2: Run the Calculation

```
Proposed price: $[X]
Estimated delivery cost: $[Y]
  - People time: [breakdown]
  - Hard costs: [breakdown]
  - Out-of-pocket exposure (Contract Gap #7, if any): [amount]
Gross margin: $[X - Y]
Margin %: [(X-Y)/X x 100]%
```

Compare against a stated acceptable margin threshold if the user has one; if not, ask what the minimum acceptable margin is for this type of deal before rendering a verdict: do not invent a threshold.

## Step 3: Render the Explicit Call

One of three outcomes, stated plainly, no hedging:

- **PROCEED**: margin clears the threshold as-is.
- **RESCOPE**: margin doesn't clear, but there's a specific scope change (name it) that would bring it into range. Show the math both ways: current scope margin vs. rescoped margin.
- **WALK**: margin doesn't clear and no realistic rescope fixes it. State this directly: never win a deal that loses money.

## Step 4: If Rescoping, Write the Reframe

If RESCOPE is the call, write the exact language for repositioning the smaller scope to the client: framed around what they actually get, not an apology for doing less. Tie it back to the Deliverables (Step 5) already agreed, adjusted honestly.

## Step 5: Check for Related Contract Gaps

While running this, flag if any of these related Contract Gaps are also present, since they compound margin risk:
- Gap #7 (out-of-pocket investments required in advance): quantify and get partial payment upfront.
- Gap #8 (questionable client payment history/stability): ask for upfront or milestone payment terms.
- Gap #9 (client demands guarantees/warranties/penalties): know your walk-away terms before negotiating any of these into the margin.

## Integration

- Direct mitigation for Contract Gap #2: run `/contract-gap-scanner` or `/gap-scan` first if margin risk hasn't been isolated yet.
- If RESCOPE is the call, loop back through `/deliverables-extractor` to re-lock what's actually being delivered at the new scope.
- This is a hard stop gap: a WALK verdict from this skill overrides enthusiasm from any other part of the deal.

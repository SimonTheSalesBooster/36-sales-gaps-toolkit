---
name: stakeholder-map
description: "Builds a multi-level stakeholder map (names, individual wins, champion pre-sell script) for a deal. Addresses Client Gaps: many people are involved in their decision, and we do not have multi-level client relationships."
user-invocable: true
---

# /stakeholder-map: Multi-Level Stakeholder Map

## Why This Skill Exists

Two of the 20 Client Gaps are structurally the same problem seen from two angles: Gap #2 (many people are involved in the decision) and Gap #4 (we do not have multi-level client relationships). The mitigation for both is the same move: map every stakeholder by name and individual win, then get the champion to pre-sell internally before you present. This skill builds that map for a real deal.

## Step 1: Get Deal Context

Ask (if not already given): "Who do you know is involved in this decision: names, titles, and anything you know about what each of them personally cares about? Who's your champion?"

## Step 2: Build the Map

For every named stakeholder, capture:

```
Name / Title:
Level: [above main contact / main contact / below main contact]
Role in decision: [economic buyer / champion / influencer / user / blocker / unknown]
Individual win: [what THIS PERSON personally gains if the deal happens: not the company-level win]
Current relationship status: [never met / met once / regular contact / champion]
Gap: [is this person a level we have NO relationship with yet?]
```

Explicitly flag: is there at least one person mapped ABOVE the main contact, and at least one BELOW? If either is missing, that is Gap #4 present: name it.

## Step 3: Write the Champion Pre-Sell Script

If a champion is identified, write a short script for the champion to use internally, before the seller presents. It should equip the champion to sell on the seller's behalf using the individual wins mapped in Step 2: not a generic "hey take a look at this."

Format:
```
To [champion name], for use with [specific stakeholder they're pre-selling to]:
"[2-3 sentences the champion can say or send, framed around that specific stakeholder's individual win from Step 2, not a generic pitch]"
```

## Step 4: The Introduction Ask

Write the exact ask the seller should make of the champion to get introduced to the missing level(s) identified in Step 2. Direct, specific, no hedging: name the person, name the reason for the introduction tied to their individual win.

## Integration

- Direct mitigation for Client Gap #2 and Gap #4: run `/client-gap-check` or `/gap-scan` first to confirm these gaps are actually present before building the map.
- Once the map is built, `/decision-criteria-extractor` surfaces what each stakeholder actually weighs in the decision (Gap #7).
- Reference: Step 1 (Visualize) of the 8 Steps: building trust with each stakeholder individually starts the same way it does with the main contact.

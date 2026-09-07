---
name: decision-criteria-extractor
description: "Generates the question set to surface a buyer's FULL decision criteria beyond price. Addresses the Client Gap: not all of the client's decision-making criteria have been identified."
user-invocable: true
---

# /decision-criteria-extractor -- Full Decision Criteria Surfacer

## Why This Skill Exists

Client Gap #7 (all of the client's decision-making criteria have not been identified) is what causes a proposal to nail the price and lose the deal anyway -- because price was never the whole picture. The canonical mitigation is a direct question: "Besides price, what else matters in this decision?" This skill builds the full question set to surface everything that matters, not just that one line.

## Step 1 -- Get Deal Context

Ask (if not already given): "What's the deal, and what do you already know the client cares about beyond price -- even if it's incomplete?"

## Step 2 -- Build the Question Set

Write a sequence of 4-6 questions that surface criteria across categories a buyer often doesn't volunteer unprompted:

```
Price (confirm it's on the table, then move past it): "Besides price, what else matters in this decision?"
Risk: "What would make this decision feel safe versus risky to you?"
Timeline: "Is speed of delivery part of how you're evaluating this, or is getting it right more important than getting it fast?"
Internal politics: "Who else's approval or opinion matters here, and what do they care about?"
Past experience: "Has anything gone wrong with a similar decision before? What are you trying to avoid this time?"
Personal stake: "What does a good outcome here mean for you specifically, not just the company?"
```

Tailor the wording to what's already known about the deal -- don't hand back a generic list untouched.

## Step 3 -- Map the Answers to Weight

Once answers are gathered (or if the user supplies notes from a call where these were already asked), rank the criteria by how much weight the client is placing on each, based on their language, tone, and what they elaborated on versus answered briefly.

```
Criterion: [name]
Weight: High / Medium / Low
Evidence: [what in their answer signals this weight]
```

## Step 4 -- Flag What's Still Missing

If any of the standard categories above (risk, timeline, internal politics, past experience, personal stake) were never asked or answered, flag it explicitly as still unknown -- do not let the list look complete when it isn't.

## Integration

- Direct mitigation for Client Gap #7 -- run `/client-gap-check` or `/gap-scan` first to confirm.
- Pairs with `/stakeholder-map` -- different stakeholders often weight criteria differently; map both together for a full picture.
- Feeds directly into how `/investment-conversation` (Step 6) should be framed -- lead with whichever criteria scored highest weight, not just time/people/money in the abstract.

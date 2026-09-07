---
name: investment-conversation
description: "Generates a Step 6 (Investment) script sequencing Time, then People, then Money: never leading with price."
user-invocable: true
---

# /investment-conversation: Step 6 Investment Script

## Why This Skill Exists

Step 6 of the 8 Steps of the Repeatable Sale is Investment: Time, People, Money: always in that order, never leading with price. Sellers who lead with the number lose the framing that makes the number make sense. This skill builds the specific sequence for a real deal.

## Step 1: Get Deal Context

Ask (if not already given): "What's the deal, and what do you already know about the deliverables agreed to (Step 5)? What's the actual time, people, and money investment this will require?"

If Step 5 deliverables haven't been locked yet, recommend running `/deliverables-extractor` first: the investment conversation only lands once the client knows what they're investing in.

## Step 2: Build the Three-Part Sequence

### Part 1: Time
Frame first: how long this takes, from the client's side and the delivery side. Anchor it to the deliverables already agreed. Never open with a number here either: open with what the time investment buys them.

```
"[X weeks/months] to get to [the specific deliverable from Step 5]. Here's what that time actually includes: [brief breakdown]."
```

### Part 2: People
Second: whose time is required, on both sides. Name roles, not generic "resources." This is where the client starts to feel the real weight of commitment: before any dollar figure has been said.

```
"On our side: [roles/people]. On yours: [who needs to be involved, and how much of their time]."
```

### Part 3: Money
Only now, the number. Frame it against the deliverables and the cost of inaction already established (Steps 4 and 5), not against a generic price list.

```
"[Price], structured as [payment terms]. Given [reference back to their stated Cost of Inaction / Deliverables], here's what that buys you: [tie back explicitly]."
```

## Step 3: Flag If Deliverables or Cost of Inaction Are Missing

If either Step 4 (Cost of Inaction) or Step 5 (Deliverables) hasn't been done yet, say so explicitly: the Investment conversation is weak without them, because there's nothing concrete to anchor the price against.

## Integration

- Reference: Step 6 (Investment) of the 8 Steps of the Repeatable Sale: Time, People, Money, in that order, never lead with price.
- Run after `/deliverables-extractor` (Step 5) and ideally after `/cost-of-inaction` (Step 4).
- Feeds into `/starting-date-closer` (Step 7) once investment is agreed.

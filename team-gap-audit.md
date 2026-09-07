---
name: team-gap-audit
description: "Internal readiness check using ONLY the 7 Team Gaps from the 36 Sales Gaps framework. Run this BEFORE proposing to a client, to check whether your own team is actually ready to deliver and win."
user-invocable: true
---

# /team-gap-audit -- Internal Readiness Check

## Why This Skill Exists

Deals don't only die on the client side. Some die because the team pitching wasn't honestly ready: no technical stakeholder in the room, no delivery capacity confirmed, a solution that doesn't fully solve the stated problem. This audit is meant to run BEFORE a proposal goes out, not after -- it's a pre-flight check, not a postmortem.

## Step 1 -- Get Context

Ask (if not already given): "What's the deal, what would we be delivering, and what do you know about our team's capacity, experience, and fit for this specific scope?"

## Step 2 -- Score All 7 Team Gaps

For each, mark PRESENT / RISK / CLEAR:

1. We're not sure why working with us now is vital to them -- Go back to Step 4 - Cost of Inaction: "What happens if you do nothing?" - and get their real answer.
2. Unique technology issues create problems -- Get a technical stakeholder into the conversation before you commit to a timeline.
3. Our solution does not completely solve the problem -- Say so. Either scope down what you promise or bring in a partner to cover the gap.
4. We have never delivered this type of service or product in the past -- Be transparent about it and pair the deal with your strongest resource. Don't oversell experience you don't have.
5. We do not understand the personal pains of the buyer(s) -- Ask the buyer what THEY personally are on the hook for, not just what the company needs.
6. We do not have the resources to support the client -- Confirm delivery capacity before you promise a start date.
7. We do not know the competition; the need came from an RFP -- Get out of the RFP paper process and get a direct conversation with the buyer before responding.

## Step 3 -- Return Ranked Output

```
PRESENT gaps (fix before you propose):
- Gap #[N] -- [name]
  Mitigation: [verbatim]

RISK gaps (confirm before you propose):
- Gap #[N] -- [name]
  Mitigation: [verbatim]

CLEAR gaps: [list numbers only]
```

## Step 4 -- Go / No-Go Call

Close with an explicit call: "Ready to propose" if all 7 are CLEAR or RISK-with-a-plan, or "Not ready to propose yet -- fix [Gap #N] first" if any PRESENT gap would materially undercut the pitch or the delivery.

## Integration

- This is the internal mirror of `/client-gap-check` -- run both before a proposal stage deal review.
- Gap 1 (unclear urgency) pairs with `/cost-of-inaction`.
- Gap 7 (RFP with no direct buyer conversation) is the same root issue as Client Gap #9 (incumbent vendors) -- if both are PRESENT, use `/incumbent-displacer` next.
- For all 36 at once, use `/gap-scan`.

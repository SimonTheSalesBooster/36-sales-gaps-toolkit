---
name: gap-scan
description: "The 36 Sales Gaps full diagnostic. Score any live or described B2B deal against all 36 gaps (20 Client, 7 Team, 9 Contract), rank by severity and likelihood-to-kill-the-deal, and return each present gap with its canonical mitigation."
user-invocable: true
model: opus
---

# /gap-scan: The 36 Sales Gaps Full Diagnostic

## Why This Skill Exists

Deals don't die from one big mistake. They die from an accumulation of small, nameable gaps that nobody flagged out loud. The 36 Sales Gaps framework names every one of them across three categories: what you don't know about the client, what your team isn't ready for, and what isn't nailed down in the contract. This skill runs the full diagnostic against a real deal and returns a ranked, actionable output, not generic advice.

This is the flagship skill in this toolkit. Run it first on any deal that feels stuck, slow, or uncertain.

## Step 1: Get Deal Context

If the user has not already given deal context, ask ONE question: "Give me what you've got, who's the client, what stage is it at, what do you already know about their decision process, their budget, their timeline, and anything about our team's readiness or the contract terms so far." Do not ask a checklist of 36 questions up front, work with whatever is given and flag what's unknown.

## Step 2: Score All 36 Gaps

Work through all three categories below. For each gap, mark one of:
- **PRESENT**: clear evidence this gap is real in this deal
- **RISK**: unclear, could be a gap, not yet confirmed either way
- **CLEAR**: evidence this is handled / not a gap here

### 🔥 Client Gaps (20)

1. We don't know their current pain: Do not write a proposal until you can state their pain back to them in their own words (Step 2 - Frustration).
2. Many people are involved in their decision to buy: Map every stakeholder by name and their individual win, then get your champion to pre-sell internally before you present.
3. The budget process is part of a larger organizational initiative: Find out where this budget actually sits and who else is competing for the same pool of money.
4. We do not have multi-level client relationships: Get introduced to at least one other person above and below your main contact before the proposal stage.
5. The client has a negative view of us or a positive view of a competitor: Address it directly: "What would need to be true for you to reconsider?"
6. The deal's ROI and success criteria have not been established: Define what winning looks like in writing before you price anything (Step 5 - Deliverables).
7. All of the client's decision-making criteria have not been identified: Ask directly: "Besides price, what else matters in this decision?"
8. We have not worked with the client previously: Offer a small paid pilot or diagnostic before proposing the full engagement.
9. The client uses multiple vendors delivering services similar to ours: Find out what isn't working with the incumbent and position specifically around that gap, not around features.
10. The client's timing and/or schedule is unreasonable: Push back on the timeline in the meeting. A realistic no beats an unrealistic yes.
11. Buyer is in decision paralysis: Ask directly: "What happens if you do nothing?" and let the silence do the work (Step 4 - Cost of Inaction).
12. Reputational risk is too high for them to buy: Give them a reference list and let them talk to 2-3 past clients directly, unscripted.
13. There is no clear client commitment to follow-on business: Set the next step and the next date before you leave the room (Step 7 - Starting Date).
14. Working with the client organization is difficult: Name the friction directly with your champion and agree on a single point of contact before signing.
15. The client is not a cultural fit with us: Name it out loud early with your team and decide honestly whether this is a deal worth pursuing at all.
16. Financial risk is too high for them to buy: Offer a guarantee or milestone-based payment tied to measurable results, so risk is shared rather than front-loaded onto the buyer.
17. Buyer is afraid of making the wrong decision: Show 3-5 proof points (case studies, testimonials) and structure a small, reversible first step instead of asking for the full commitment up front.
18. Failure in this deal will derail other key business we have with the client: Separate the new scope from the existing relationship contractually so one deal can't put both at risk.
19. The client is unwilling to communicate clearly and frequently: Set a fixed weekly touchpoint as a condition of moving forward, not a nice-to-have.
20. The client does not have executive buy-in for the deal: Ask to present directly to the economic buyer before writing the proposal.

### 🎫 Team Gaps (7)

1. We're not sure why working with us now is vital to them: Go back to Step 4 - Cost of Inaction: "What happens if you do nothing?" - and get their real answer.
2. Unique technology issues create problems: Get a technical stakeholder into the conversation before you commit to a timeline.
3. Our solution does not completely solve the problem: Say so. Either scope down what you promise or bring in a partner to cover the gap.
4. We have never delivered this type of service or product in the past: Be transparent about it and pair the deal with your strongest resource. Don't oversell experience you don't have.
5. We do not understand the personal pains of the buyer(s): Ask the buyer what THEY personally are on the hook for, not just what the company needs.
6. We do not have the resources to support the client: Confirm delivery capacity before you promise a start date.
7. We do not know the competition; the need came from an RFP: Get out of the RFP paper process and get a direct conversation with the buyer before responding.

### 📄 Contract Gaps (9)

1. Agreements have not been formalized in writing: No verbal deal is a deal. Send the SOW ready to sign before the next meeting (Step 8 - Statement of Work).
2. The business can be won, but we cannot achieve an acceptable margin: Walk away, or change scope until the math works. Never win a deal that loses money.
3. We will be asked to use the client's contract or agree to non-standard terms: Get legal eyes on non-standard terms early, not in the final week of the deal.
4. Outside of the finances, we cannot state the value of the deal: If you can't say why this deal matters beyond the invoice, it's not worth the resourcing.
5. Funding has not been secured: Confirm exactly whose signature releases the budget before you invest more time.
6. Funding is not available now but will be in the future: Get a specific date attached to when funding clears, not "sometime next quarter."
7. We will be required to make out-of-pocket investments in advance: Quantify the exposure and get partial payment upfront to offset it before starting.
8. The client's payment history and/or financial stability is questionable: Ask for upfront or milestone payment terms and let their answer tell you what you need to know.
9. The client demands contractual guarantees, warranties or penalties: Know your walk-away terms before you negotiate. Offer a guarantee you can actually stand behind.

## Step 3: Rank and Return

Take every gap scored PRESENT or RISK. Rank them by severity x likelihood-to-kill-the-deal (your judgment, based on what was shared). Return:

```
Rank 1: [Category] Gap #[N]: [gap name]
Status: PRESENT / RISK
Why it's here: [one sentence tied to the actual deal facts given]
Mitigation: [the canonical mitigation, verbatim]

Rank 2: ...
Rank 3: ...
```

List every PRESENT/RISK gap, not just the top 3: this is a full scan, not a highlight reel. Group the rest (below the top ranked) by category so the output stays scannable.

## Step 4: Close With the One Move

End with: "If you fix ONE thing before your next touchpoint with this client, fix [Rank 1's mitigation]." That is the single highest-leverage action.

## Integration

- Closed-lost already? Use `/deal-autopsy` instead: this skill is for live/open deals.
- Want just the client-facing half? Use `/client-gap-check`.
- Want just internal readiness? Use `/team-gap-audit`.
- Want just the paper? Use `/contract-gap-scanner`.
- Any gap tied to a Step of the Repeatable Sale (Frustration, Deliverables, Cost of Inaction, Starting Date, Statement of Work): name the step explicitly in the mitigation, don't just cite the gap.

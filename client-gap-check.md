---
name: client-gap-check
description: "Deep-dive scorer using ONLY the 20 Client Gaps from the 36 Sales Gaps framework. Run this during pipeline or deal reviews to check where a deal is exposed on the client-relationship side."
user-invocable: true
---

# /client-gap-check: Client Gaps Deep Dive

## Why This Skill Exists

The 20 Client Gaps are the ones rooted in what you know (or don't know) about the buyer's world: their pain, their politics, their risk tolerance, their decision process. These are the gaps most sales teams sense vaguely but never name specifically enough to act on. This skill isolates just this category for a focused pipeline or deal review, rather than running the full 36-gap scan.

## Step 1: Get Deal Context

If not already provided, ask: "Tell me about this deal: what do you know about their pain, who's involved in the decision, what's their relationship to us and any competitors, and what's their timeline?"

## Step 2: Score All 20 Client Gaps

For each, mark PRESENT / RISK / CLEAR based on what's known about this specific client:

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

## Step 3: Return Ranked Output

```
PRESENT gaps (act now):
- Gap #[N]: [name]
  Mitigation: [verbatim]

RISK gaps (confirm before proposal stage):
- Gap #[N]: [name]
  Mitigation: [verbatim]

CLEAR gaps: [list numbers only, no detail needed]
```

## Step 4: Flag the Single Highest-Risk Gap

Close with: "The client gap most likely to stall or kill this deal is #[N]. Before your next touchpoint: [mitigation, applied specifically to this client]."

## Integration

- For internal team readiness instead, use `/team-gap-audit`.
- For contract/paper risk instead, use `/contract-gap-scanner`.
- For all 36 at once, use `/gap-scan`.
- Gaps 2 and 4 (stakeholder mapping, multi-level relationships) pair directly with `/stakeholder-map`: run that next if either scores PRESENT.
- Gap 6 (no ROI/success criteria) pairs with `/deliverables-extractor`.
- Gap 9 (incumbent vendor) pairs with `/incumbent-displacer`.
- Gap 7 (decision criteria not identified) pairs with `/decision-criteria-extractor`.
- Gap 11 (decision paralysis) pairs with `/cost-of-inaction`.
- Gaps 10 and 13 (unreasonable timing, no follow-on commitment) pair with `/starting-date-closer`.

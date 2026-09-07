---
name: deal-autopsy
description: "For a closed-lost deal: walk through what happened, identify the 1-3 real gaps (from the 36 Sales Gaps framework) that actually killed it, name the lesson, and contrast with what the correct mitigation would have looked like."
user-invocable: true
model: opus
---

# /deal-autopsy -- Closed-Lost Deal Autopsy

## Why This Skill Exists

Most closed-lost deals get a one-line note ("went with a competitor," "budget got cut") and no real diagnosis. That guarantees the same gap kills the next deal too. This skill forces a real autopsy: which of the 36 Sales Gaps actually killed this deal, not the surface-level excuse.

## Step 1 -- Get the Deal Story

Ask the user to walk through the deal chronologically if not already given: how it started, what happened at each stage, when it went quiet or turned, and what the client's stated reason for saying no was (if any). The stated reason is a data point, not the answer -- most stated reasons ("went with someone else," "no budget," "bad timing") are a symptom of one of the 36 gaps, not the root cause.

## Step 2 -- Identify the 1-3 Real Gaps

Do not spread blame across all 36. Find the 1-3 gaps that were actually decisive. Test each candidate gap against the deal timeline: "Would this deal have closed if this ONE gap had been closed?" If yes, it's a real cause. If the deal still would have died without it, it's noise -- leave it out.

Pull candidates from the full list (reference only, do not print the full 36 back at the user -- name only the ones that apply):

**Client Gaps (20):** unknown pain, multiple decision-makers unmapped, budget tied to a larger initiative, no multi-level relationships, negative view of us / positive view of a competitor, no ROI/success criteria defined, not all decision criteria identified, no prior track record with client, incumbent vendor relationship, unreasonable timing, decision paralysis, reputational risk too high, no commitment to follow-on, difficult client org, cultural misfit, financial risk too high, fear of wrong decision, this deal risks other business with the client, poor client communication, no executive buy-in.

**Team Gaps (7):** unclear urgency, technology issues, incomplete solution fit, no prior delivery experience, buyer's personal pain misunderstood, insufficient delivery resources, blind RFP response with no direct buyer conversation.

**Contract Gaps (9):** nothing formalized in writing, margin too thin to win profitably, non-standard contract terms, value beyond price never stated, funding not secured, funding delayed to a future date, upfront out-of-pocket exposure, questionable client payment history, unmet demand for guarantees/warranties/penalties.

## Step 3 -- Contrast: What the Mitigation Would Have Looked Like

For each of the 1-3 real gaps identified, write two short paragraphs side by side:
- **What actually happened** (from the deal story given)
- **What the canonical mitigation would have looked like, applied to this exact deal** (be specific: names, dates, the actual words that should have been said, referencing the relevant Step of the Repeatable Sale where applicable)

## Step 4 -- Name the Lesson

Close with ONE sentence: the lesson, generalized beyond this one deal, phrased so it's usable as a standing rule for the next deal of this type. Example format: "Never let a proposal go out before [X] is confirmed in writing" or "Any deal where [buyer signal] appears needs [specific action] within the first two calls."

## Integration

- For a still-open deal, use `/gap-scan` instead -- this skill is retrospective only, for deals already lost.
- If the autopsy surfaces a pattern across multiple lost deals (same gap recurring), that's worth raising as a standing process fix, not just a one-off lesson.

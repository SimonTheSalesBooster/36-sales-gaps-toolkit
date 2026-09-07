---
name: starting-date-closer
description: "Converts a vague 'soon' or 'next quarter' into a committed starting date. Addresses the Client Gaps: timing/schedule is unreasonable, and no clear commitment to follow-on business."
user-invocable: true
---

# /starting-date-closer: Step 7 Starting Date Closer

## Why This Skill Exists

Step 7 of the 8 Steps of the Repeatable Sale is Starting Date: "To which starting date are we committing?" A specific date, not "soon" or "next week." Commitment is the close. Two Client Gaps live directly downstream of a vague answer here: Gap #10 (the client's timing/schedule is unreasonable) and Gap #13 (no clear client commitment to follow-on business). This skill converts vagueness into a real, committed date.

## Step 1: Get Deal Context

Ask (if not already given): "What's the deal, and what has the client said about timing so far: verbatim if possible?"

## Step 2: Diagnose the Vagueness

Identify exactly what kind of vague answer this is:
- No date at all ("let's connect again soon")
- A date with no commitment attached ("probably next quarter")
- A date that is unreasonable given the scope (Gap #10: push back on this directly, a realistic no beats an unrealistic yes)

## Step 3: Build the Closing Question Sequence

```
Direct: "To which starting date are we committing?"
If they hedge: "What has to happen between now and then for that date to actually work?"
If the date given is unreasonable for the scope: "Given [scope from Deliverables/Investment], [their date] isn't realistic: here's what actually fits: [alternative date]. Does that work, or should we talk about what changes to hit their date?"
Close: "So we're locking [specific date]: what do you need from us before then?"
```

Never leave the conversation with "soon," "next week," "next quarter," or any non-calendar-specific answer standing as the final word.

## Step 4: If This Also Signals Gap #13 (No Follow-On Commitment)

If the client is vague not just on the start date but on whether there's a next step at all, treat this as Gap #13: surface it directly: "Before we end here, what's the next step and the next date?" Never leave a meeting without both set.

## Integration

- Direct mitigation for Client Gaps #10 and #13: run `/client-gap-check` or `/gap-scan` first to confirm.
- Reference: Step 7 (Starting Date) of the 8 Steps of the Repeatable Sale.
- Once a date is locked, this becomes the SOW's start date: run `/contract-gap-scanner` on the resulting document (Step 8).

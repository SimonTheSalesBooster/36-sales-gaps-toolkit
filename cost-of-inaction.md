---
name: cost-of-inaction
description: "Generates a Step 4 (Cost of Inaction) question sequence tailored to a specific deal -- 'what happens if you do nothing?' Ties directly to the Client Gap: buyer is in decision paralysis."
user-invocable: true
---

# /cost-of-inaction -- Step 4 Question Builder

## Why This Skill Exists

Client Gap #11 (Buyer is in decision paralysis) has one canonical mitigation: ask directly what happens if they do nothing, then let the silence do the work. That's Step 4 of the 8 Steps of the Repeatable Sale -- Cost of Inaction. This skill builds the specific question sequence for a real deal, so the seller isn't reaching for a generic line in the moment.

## Step 1 -- Get Deal Context

Ask (if not already given): "What's the deal, what's the client stuck on, and what do you already know about what's at stake for them if this drags on?"

## Step 2 -- Build the Question Sequence

Write 3-5 questions, ordered from broad to specific, all built around the same core: "What happens if you do nothing?" Never answer the question for the buyer -- every question in the sequence should end in silence, waiting for them to say the consequence out loud.

Format:
```
Opening (broad): "If this stays exactly where it is six months from now, what does that cost you?"
Follow-up (specific to their stated pain): [tailored to what's known about the deal]
Follow-up (personal stakes): "What does that mean for you personally, not just the company?"
Follow-up (timing): "Is there a point where this becomes too late to fix?"
Closing (silence-forcing): "What happens if you do nothing?" -- then stop talking.
```

Do not pre-write the buyer's answer. Do not soften the final question with a qualifier ("just curious," "no pressure"). The directness is the point.

## Step 3 -- Note the Delivery Instruction

Remind the user: after asking the closing question, do not fill the silence. Let the buyer sit with it. The Cost of Inaction step works because the buyer says the consequence in their own words -- if the seller says it first, the persuasive weight is lost.

## Integration

- This is the direct mitigation for Client Gap #11 (decision paralysis) and Team Gap #1 (unclear why working with us now is vital) -- run `/gap-scan` or `/client-gap-check` first if you haven't already confirmed this gap is actually present.
- Once the buyer answers, the next step is Step 5 (Deliverables) -- use `/deliverables-extractor` to turn their answer into SOW-ready language.
- Reference: Step 4 of the 8 Steps of the Repeatable Sale -- "What happens if you do nothing?"

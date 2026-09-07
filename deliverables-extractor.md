---
name: deliverables-extractor
description: "Turns raw discovery-call notes or a transcript into Step 5 (Deliverables) SOW-ready language, written back in the client's own words. Addresses the Client Gap: ROI and success criteria have not been established."
user-invocable: true
---

# /deliverables-extractor -- Step 5 Deliverables Extractor

## Why This Skill Exists

Client Gap #6 (the deal's ROI and success criteria have not been established) kills deals quietly -- the proposal gets written before anyone defined what winning looks like, so the client never fully commits to it. Step 5 of the 8 Steps of the Repeatable Sale exists to fix this: "What do you want to achieve? Talk to me about deliverables for the next 10 days." This skill extracts that answer from raw notes or a transcript and turns it into SOW-ready language.

## Step 1 -- Get the Raw Material

Ask for the discovery-call notes or transcript if not already provided. If neither exists yet, generate the Step 5 question sequence instead (see Step 4 below) so the seller can go get this material on the next call.

## Step 2 -- Extract in the Client's Own Words

Read through the material and pull out every phrase where the client stated a desired outcome, a success measure, a timeline, or a "what winning looks like" statement. Quote them directly -- do not paraphrase or upgrade their language into your own vocabulary. Per the canonical rule: SOW language must be the prospect's own words, never the seller's rewrite.

## Step 3 -- Build the SOW-Ready Deliverables List

Turn the extracted quotes into a numbered, specific, measurable deliverables list:

```
Deliverable 1: [specific, measurable, in-the-client's-language]
Source quote: "[exact words from the call]"

Deliverable 2: ...
```

Flag any deliverable that is still vague (e.g. "improve sales") and note the follow-up question needed to make it specific and measurable before it goes into a real SOW.

## Step 4 -- If No Material Exists Yet: Generate the Question Sequence

"What do you want to achieve? Talk to me about deliverables for the next 10 days." Build 3-4 follow-up questions that narrow a vague answer into something specific enough to write into a contract -- timeframe, measurable outcome, who defines "done."

## Integration

- Direct mitigation for Client Gap #6 -- run `/client-gap-check` or `/gap-scan` first to confirm.
- Feeds directly into a real SOW -- reference the canonical rule that SOW language is the prospect's words only, never invented or upgraded language.
- Reference: Step 5 (Deliverables) of the 8 Steps of the Repeatable Sale, which becomes the basis of the SOW at Step 8.
- Once deliverables are locked, move to `/investment-conversation` (Step 6) and then `/starting-date-closer` (Step 7).

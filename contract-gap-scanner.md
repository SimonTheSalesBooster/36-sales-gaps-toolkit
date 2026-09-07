---
name: contract-gap-scanner
description: "Reviews a draft SOW or contract clause by clause against the 9 Contract Gaps from the 36 Sales Gaps framework. Catches paper risk before it becomes deal risk."
user-invocable: true
---

# /contract-gap-scanner -- Contract Gap Review

## Why This Skill Exists

A deal can survive the client relationship and the team readiness check and still die (or quietly bleed margin) on the paper: no written agreement, thin margins, non-standard terms nobody flagged, funding that was never confirmed. This skill reads a draft SOW or contract against the 9 Contract Gaps, clause by clause.

## Step 1 -- Get the Document

Ask for the draft SOW/contract text if not already provided, or a description of its terms (price, scope, payment schedule, guarantees, funding source) if no document exists yet.

## Step 2 -- Score All 9 Contract Gaps

For each, mark PRESENT / RISK / CLEAR, and where possible cite the specific clause (or its absence):

1. Agreements have not been formalized in writing -- No verbal deal is a deal. Send the SOW ready to sign before the next meeting (Step 8 - Statement of Work).
2. The business can be won, but we cannot achieve an acceptable margin -- Walk away, or change scope until the math works. Never win a deal that loses money.
3. We will be asked to use the client's contract or agree to non-standard terms -- Get legal eyes on non-standard terms early, not in the final week of the deal.
4. Outside of the finances, we cannot state the value of the deal -- If you can't say why this deal matters beyond the invoice, it's not worth the resourcing.
5. Funding has not been secured -- Confirm exactly whose signature releases the budget before you invest more time.
6. Funding is not available now but will be in the future -- Get a specific date attached to when funding clears, not "sometime next quarter."
7. We will be required to make out-of-pocket investments in advance -- Quantify the exposure and get partial payment upfront to offset it before starting.
8. The client's payment history and/or financial stability is questionable -- Ask for upfront or milestone payment terms and let their answer tell you what you need to know.
9. The client demands contractual guarantees, warranties or penalties -- Know your walk-away terms before you negotiate. Offer a guarantee you can actually stand behind.

## Step 3 -- Return Clause-by-Clause Output

```
PRESENT gaps (fix before this goes out / gets signed):
- Gap #[N] -- [name]
  Where: [clause cited, or "absent from the document"]
  Mitigation: [verbatim]

RISK gaps (confirm before signing):
- Gap #[N] -- [name]
  Mitigation: [verbatim]

CLEAR gaps: [list numbers only]
```

## Step 4 -- Sign / Don't Sign Call

Close with an explicit call: "Ready to send/sign" or "Hold -- fix [Gap #N] first, here's the exact language to add or change." If Gap #2 (margin) is PRESENT, this is a hard stop regardless of any other gap's status -- state that explicitly, never win a deal that loses money.

## Integration

- Never DocuSign -- SOWs are sent via PandaDoc, ready to sign, not a draft (Step 8 - Statement of Work).
- Gap #1 pairs directly with the SOW-readiness requirement of Step 8 -- if this scan runs on a document that isn't yet "ready to sign," it isn't done.
- For client-relationship risk instead, use `/client-gap-check`. For internal readiness, use `/team-gap-audit`. For all 36 at once, use `/gap-scan`.
- If margin is the flagged issue, run `/margin-guard` for the full walk-away-or-rescope calculation.

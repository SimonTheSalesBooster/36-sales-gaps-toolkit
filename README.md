# 36 Sales Gaps Toolkit: 13 Free Claude Code Skills

Most B2B deals don't die from one bad meeting. They die from an accumulation of small, unnamed gaps: a stakeholder nobody mapped, a "soon" that never became a date, a margin nobody checked before signing. The 36 Sales Gaps framework names every one of them, in three categories, each with an exact mitigation. This toolkit turns that framework into 13 ready-to-run Claude Code skills.

---

## What this is

Every deal review, discovery call debrief, or contract check has a right question to ask. Most sales teams ask a generic one ("how's this deal looking?") and get a generic answer. These skills ask the specific, calibrated question the 36 Sales Gaps framework says to ask, run it against your actual deal, and return a named gap with its exact mitigation, not general advice.

`/gap-scan` is the flagship: it scores a live deal against all 36 gaps and returns a ranked, actionable output. The other 12 skills either isolate one category (client, team, or contract) or go deep on a single high-frequency gap with the tools to fix it (a stakeholder map, a Cost-of-Inaction question sequence, a margin calculator).

---

## Why this is different from generic AI sales advice

A prompt tells Claude to "review my deal" and returns advice that could apply to any business. This toolkit doesn't. Every skill is grounded in a named, tested framework: 36 specific gaps, each with a specific mitigation, several tied directly to the 8 Steps of the Repeatable Sale methodology used with 2,400+ B2B founders. There is no invented terminology and no generic checklist standing in for a real diagnostic: you get the exact gap name, the exact question or move that closes it, and nothing else.

---

## The 13 Skills

### Diagnose

| Skill | What It Does |
|---|---|
| `/gap-scan` | **Flagship.** Score any live deal against all 36 gaps (Client, Team, Contract), rank by severity, return each with its mitigation. |
| `/deal-autopsy` | For a closed-lost deal: identify the 1-3 real gaps that actually killed it, contrast with what the mitigation would have looked like. |
| `/client-gap-check` | Deep-dive scorer using only the 20 Client Gaps (for pipeline and deal reviews). |
| `/team-gap-audit` | Internal readiness check using only the 7 Team Gaps (run before you propose). |
| `/contract-gap-scanner` | Reviews a draft SOW or contract clause by clause against the 9 Contract Gaps. |

### Prevent (build the missing piece before it becomes a gap)

| Skill | What It Does |
|---|---|
| `/stakeholder-map` | Builds a multi-level stakeholder map: names, individual wins, champion pre-sell script. |
| `/deliverables-extractor` | Turns discovery-call notes into Step 5 SOW-ready deliverables, in the client's own words. |
| `/decision-criteria-extractor` | Generates the question set to surface a buyer's full decision criteria beyond price. |
| `/incumbent-displacer` | Diagnoses what isn't working with the client's current vendor, positions around that specific gap. |

### Close the gap (in the moment, on a live deal)

| Skill | What It Does |
|---|---|
| `/cost-of-inaction` | Generates a Step 4 "what happens if you do nothing?" question sequence for a specific deal. |
| `/investment-conversation` | Generates a Step 6 script sequencing Time, then People, then Money (never leading with price). |
| `/starting-date-closer` | Converts a vague "soon" into a committed date. |
| `/margin-guard` | Calculator and checklist: can this deal be won at an acceptable margin, or does scope need to change, or should you walk. |

---

## The 36 Sales Gaps

**🔥 Client Gaps (20)**: everything you don't yet know about the buyer's world: their pain, their politics, their risk, their decision process.

**🎫 Team Gaps (7)**: everything about your own readiness to actually win and deliver: urgency clarity, technical fit, experience, capacity.

**📄 Contract Gaps (9)**: everything on the paper: what's written down, what margin survives, what funding is confirmed.

Every gap has a name and an exact mitigation. Several tie directly to a specific step of the 8 Steps of the Repeatable Sale (Frustration, Cost of Inaction, Deliverables, Investment, Starting Date, Statement of Work): the skills name the step explicitly wherever it applies.

---

## Install

```bash
# Install all 13 skills
for skill in gap-scan deal-autopsy client-gap-check team-gap-audit contract-gap-scanner cost-of-inaction stakeholder-map deliverables-extractor investment-conversation starting-date-closer incumbent-displacer decision-criteria-extractor margin-guard; do
  cp $skill.md ~/.claude/commands/$skill.md
done
```

Then in Claude Code:

```
/gap-scan
/deal-autopsy
/margin-guard
```

Start with `/gap-scan` on any deal that feels stuck, slow, or uncertain. Use `/deal-autopsy` on anything already closed-lost, to make sure the next deal doesn't die from the same unnamed gap.

---

## About the 36 Sales Gaps framework

The 36 Sales Gaps is Strategy Sprints' own diagnostic framework, built to sit alongside the 8 Steps of the Repeatable Sale: the 8 Steps tell you what to do in the conversation, the 36 Gaps tell you what's missing when the deal stalls anyway. It is proprietary Strategy Sprints methodology, not adapted from a third-party source.

---

## Work with Strategy Sprints directly

**Sprint Club**: the paid community where these skills, and the rest of the Strategy Sprints skills library, live and get used every day.

[**www.strategysprints.com**](https://www.strategysprints.com)

---

## License

MIT. Use it, fork it, improve it.

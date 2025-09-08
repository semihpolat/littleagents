# Contributing Guide

We curate practical, free (or partly free) AI tools that actually help people ship. Your real-world tests and notes are what make this list valuable. Even a tiny contribution can save someone hours.

## How to Contribute (Quickstart)
1. Fork the repo and clone locally.
2. Create a new branch: `git checkout -b feature/tool-<short-name>` or `docs/update-<category>`.
3. Run a very small task with the tool (≤2 minutes). See the "Quick Test" guide below.
4. Copy the "Tool Card Template" and fill it out.
5. Add it to the correct category in `README.md`. No need to edit the table of contents.
6. Open a PR with a clear title and a short description. Use the checklist.

## Acceptance Criteria (TL;DR)
- Real usage evidence: at least one mini task and a one-line test note.
- Standard format: follow the template.
- Clarity: focus on practical value and limits, not marketing.
- Scope: describe the free/partly free usage boundary.

## Quick Test (≤2 minutes) Guide
- Pick a small, concrete task: e.g., "Summarize a 100-row CSV" or "Fix a README typo".
- Time it: use a stopwatch (mm:ss), not a guess.
- Note friction: sign-up, credit card, limits, setup hurdles.
- Rate output quality 1–5 (see scale below).
- Write a one-line test note: what you did and how it went.

### Quality Scale (1–5)
- 1: Not usable / clearly wrong
- 2: Barely works, lots of noise/gaps
- 3: Works but needs manual fixes
- 4: Good in most cases, minor tweaks
- 5: Excellent out of the box

### Latency and Friction Tags
- `latency`: `S` (fast), `M` (medium), `L` (slow)
- `friction`: `low` (instant), `med` (a few steps), `high` (sign-up/CC/complex setup)

## Tool Card Template (Copy-Paste)
Add this block under the relevant category. Remove lines you don’t need, but keep the order and tags.

```md
Tool Name — One concise value promise
[status: VERIFIED|UNVERIFIED — YYYY-MM-DD] [agent: API=yes|no webhooks=yes|no] [latency=S|M|L] [friction=low|med|high]
What it does: What it does (1–2 sentences).
Why it matters: Why it’s practically useful (1–2 sentences).
Free-tier ceiling: What are the free plan limits?
Agent-readiness: API/webhook/integration situation.
How to use (Recipe):
1. Step 1
2. Step 2
3. Step 3
Where it breaks: Where it struggles or fails.
Alternatives: 2–3 reasonable alternatives.
Keep / Skip: Who should keep it, who can skip.
Quick Benchmark (≤2 min):
Task: The mini task you tried
Time: mm:ss
Quality: 1–5
Sample output: Short example output (1–2 lines)
One-liner test note: One-line summary of your test (what + result)
```

## Choosing a Category
- Pick the best fit among existing categories. If unsure, say so in your PR.
- Proposing a new category? Add 2+ tools and a short rationale.

## Style and Formatting
- Be short, concrete, and measurable.
- Use `[Title](https://...)` markdown links, not bare URLs.
- Avoid marketing fluff; favor real experience and limits.
- Keep product names/buttons in their original language; write notes in English.

## PR Process and Checklist
- Branch naming: `feature/...`, `docs/...`, `fix/...`
- Commit messages: imperative mood, concise subject line.
- PR title: "Add: <Tool Name> to <Category>" or "Update: <Tool> details".
- PR description checklist:
  - [ ] Correct category
  - [ ] Template complete
  - [ ] Quick test (task, time, quality) included
  - [ ] One-line test note present
  - [ ] Links work

Merge policy: Clear, reproducible, and valuable for others. Maintainers may do minor edits for consistency.

## Code of Conduct
Be respectful and inclusive. When debating, bring data or examples. The goal is to help the community learn faster.

Thanks! Your small note might save someone a big afternoon. 
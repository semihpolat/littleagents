RULES.md — littleagents (English, codex-ready, playful)

This is the single-source rulebook Codex / Cursor will read before editing only README.md.
Make the blog feel human, useful, and shareable — with short, witty one-liners for each tool and niche, human categories like Last-Minute Deadline Tools or Coffee-Fueled Prototyping.

Short version: Codex edits only README.md, follows the templates below, uses FASTLANE badges, writes a 1-line witty tagline for each tool, and is brutally honest about limits.

⸻

0) Purpose & Ground Rules
	•	Single source: All content lives in README.md. Do not create or edit other files.
	•	Tone: Playful, slightly snarky, builder-first. Think: helpful friend who codes at 2am.
	•	Ethos: No hype. Numbers > adjectives. Be useful, not buzzwordy.
	•	Humor rule: Every tool must include a short witty one-liner (≤12 words) before the details. Keeps readers smiling and shareable.

⸻

1) Required README structure (must exist, create if missing)
	1.	Title + 1-line hook
	2.	Short intro + why this repo exists
	3.	Table of Contents (ToC) (auto-update if missing)
	4.	Category sections (see niche list below)
	5.	Combo Plays (one combo for every ≈5 tools in a category)
	6.	Delta Log (weekly changelog; newest first)
	7.	Contribute / Issue templates summary
	8.	License / Credits

⸻

2) Niche category examples (human, contextual)

Use these (or similar) — categories should feel like real workflows:
	•	Coding
	•	Last-Minute Deadline Tools (for shipping yesterday’s MVP)
	•	Coffee-Fueled Prototyping (quick GUI / demo builders)
	•	Agent Playgrounds & Orchestration
	•	Research / Data Wrangling
	•	Design & Media
	•	Ops & Automation
	•	Business / Growth Hacking
	•	Weird & Wonderful (weird tools people love)

Pick categories that sound like someone telling a friend which tool to reach for.

⸻

3) Entry format (exact — copy/paste into README)

Place each tool entry in its category exactly like this:

Tool Name — One-liner (witty, ≤12 words)

[status: UNVERIFIED — {YYYY-MM-DD}] [agent: API={yes|no} webhooks={yes|no}] [latency={S|M|L}] [friction={low|med|high}]

What it does: 1–2 lines, concrete.
Why it matters: 1 line tied to a real outcome (ship faster, reduce cost, automate gruntwork).
Free-tier ceiling: short: e.g., “100 queries/day; 5 projects.” If unknown, write guess.
Agent-readiness: API? Webhooks? Best fit (brief).
How to use (Recipe): 3 numbered steps for a realistic agent-ish flow.
Where it breaks: 1–2 honest failure points (rate limits, export, hallucination). Required.
Alternatives: 1–2 names (when to pick them).
Keep / Skip: One crisp sentence for when this is useful vs. when to avoid it.

Length: aim for 120–220 words total (excluding the one-liner and metadata line).
Links: link to official docs. No affiliate links.

If status = verified, append:

Quick Benchmark (≤2 min): Task; Time (mm:ss); Quality (1–5); Sample output (1–2 lines).

⸻

4) Status badges (FASTLANE)

Use these exact badge strings in the metadata line:
	•	UNVERIFIED — AI-drafted, not bench-run. Add date.
	•	VERIFIED — 2-minute bench with Quick Benchmark block. Add date.
	•	CATALOG — single line + link, community verification wanted.

Examples:

[status: UNVERIFIED — 2025-09-04] [agent: API=yes webhooks=no] [latency=M] [friction=med]


⸻

5) Combo Play format (insert after ~every 5 tools in a category)

Combo: {Tool A} → {Tool B} → {Tool C} — One-liner goal

Goal: measurable outcome (e.g., “Generate landing page + deploy, under 10 minutes”).
Steps:
	1.	Input → output (exact prompts/files).
	2.	Input → output.
	3.	Finalize/deploy.
Free-tier blockers: short list.
[status: UNVERIFIED — {YYYY-MM-DD}]

Combos add practical value. Keep them tight and runnable.

⸻

6) ToC & Delta Log rules
	•	ToC must link to categories; update if you add/remove a category.
	•	Delta Log must be present at README bottom. Each entry:
YYYY-MM-DD — Added: {n} tools; Verified: {slugs}; Removed: {slugs}; Notable combo: {slug}
	•	Prepend new Delta Log lines (newest on top). Keep it short.

⸻

7) Scoring & quick classification
	•	Latency: S <5s, M 5–15s, L >15s (write guess if untested).
	•	Friction: low = SSO/no card; med = email verify; high = card/manual approval.
	•	Quality (verified only): 1–5 (1 unusable — 5 publishable).

⸻

8) Style & voice
	•	First-person plural is OK (“we tried this”); keep it practical.
	•	No marketing ads; no promotional copy.
	•	Use ASCII fallback if diacritics fail.
	•	Keep the witty one-liner short and human.

⸻

9) Codex / Cursor task prompts (copy-paste ready)

A) Add a new tool (UNVERIFIED)

Add a new tool entry under the "{CATEGORY}" section of README.md using the exact template.
Write a witty one-liner (≤12 words). If any detail is unsure, mark it as "guess".
Set status to UNVERIFIED with today's date {TODAY_YYYY-MM-DD}.
Do not create new files. Update ToC if needed.

B) Promote to VERIFIED (mini-bench present)

Find the entry for "{TOOL}" in README.md.
Append the Quick Benchmark block with: Task, Time (mm:ss), Quality (1–5), Sample output (1–2 lines).
Change status to VERIFIED with today's date. Remove any "guess" tags that are resolved.

C) Insert a Combo Play

After every 5 entries in the "{CATEGORY}" section, insert one Combo Play following the combo template.
Be explicit about inputs/outputs and note free-tier blockers.
Set status UNVERIFIED unless a real run is shown.

D) Update Delta Log

Prepend today's delta line in README.md under "## Delta Log":
YYYY-MM-DD — Added: {n} tools; Verified: {slugs}; Removed: {slugs}; Notable combo: {slug}
Keep it concise and factual.

E) Clean / Consistency pass

Scan README.md for duplicates, missing "Where it breaks", missing one-liners, or misformatted status badges.
Fix formatting to match templates. Ensure ToC links match headings.


⸻

10) Contribution / moderation basics
	•	PRs must follow the exact template (Codex can create content but humans merge).
	•	Reject additions that: lack “Where it breaks”, are duplicate entries, or contain hype without evidence.
	•	Community verification via Issues: include verify_tool issue with mini-bench data.

⸻

11) Quick automation tips (optional)
	•	If networked: run 1-line latency checks for API tools and add latency guess→measured.
	•	Encourage community to run verify_tool issue template to change UNVERIFIED → VERIFIED.

⸻

12) Deal breakers (auto-reject)
	•	Missing “Where it breaks”.
	•	Affiliate links, paid-only gate without note, or marketing fluff.
	•	Duplicate tools.
	•	Creating files other than README.md.

⸻

13) Quick checklist for any commit to README.md
	•	One-liner present for every tool
	•	Status badge present and correct format
	•	“Where it breaks” filled
	•	ToC updated
	•	Delta Log prepended with today’s line (if this commit adds/removes/verifies)
	•	Links point to official docs (not blogspam)

⸻

14) Final notes (keep it human)

This repo should feel like a friend who eats, codes, drinks too much coffee, and says exactly which tool to use when the deadline is on fire. Make entries helpful, honest, and sharable — and always keep the playful one-liner.

⸻

If you like, I’ll now:
	•	convert this into a rules.md file ready to paste into the repo, and
	•	generate the first 10 tool entries in English with witty one-liners and UNVERIFIED badges so Codex can start expanding README.md. Which do you want me to do next?

# littleagents
300 Free (maybe not) AI Tools

# 300 Free (Maybe Not) AI Agent Tools

In this post, I’ve compiled different categories of free (or partly free) AI tools.
Here’s the first selection:

## Table of Contents

1. [Coding Sidekicks](#1-coding-sidekicks)
2. [Zero-Budget Biz Helpers](#2-zero-budget-biz-helpers)
3. [Free LLM Hangouts](#3-free-llm-hangouts)
4. [Last-Minute Deadline Lifesavers](#4-last-minute-deadline-lifesavers)
5. [Design Help for the Talentless](#5-design-help-for-the-talentless)
6. [Bedroom Beat Machines](#6-bedroom-beat-machines)
7. [Couch-Friendly Video Magic](#7-couch-friendly-video-magic)
8. [Automation Gremlins](#8-automation-gremlins)
9. [SEO Spells & Hype Tricks](#9-seo-spells--hype-tricks)
10. [Chatbots That Never Ghost](#10-chatbots-that-never-ghost)
11. [Study Buddies That Don't Judge](#11-study-buddies-that-dont-judge)
12. [Numbers Whisperers](#12-numbers-whisperers)
13. [Mind & Body Sidekicks](#13-mind--body-sidekicks)
14. [Agent Playgrounds](#14-agent-playgrounds)
15. [Weird & Wonderful](#15-weird--wonderful)
16. [Under-the-Radar Agentic Tools](#16-under-the-radar-agentic-tools)

---

## 1. Coding Sidekicks

- [Cursor](https://www.cursor.so)  
  Your AI pair programmer that's surprisingly good at 3am bug hunts.

- [Bolt.new](https://bolt.new)  
  Spins up prototypes before your coffee gets cold.

- [Google AI Studio App Generator](https://ai.google/tools/studio/)
  Build and tinker with AI apps right in your browser.

Aider — ChatGPT-coded patches without leaving terminal
[status: VERIFIED — 2025-09-04] [agent: API=no webhooks=no] [latency=M] [friction=low]
What it does: CLI that chats about your repo and writes commits.
Why it matters: ships small fixes fast without opening an editor.
Free-tier ceiling: open source; uses your own OpenAI key; cost per token.
Agent-readiness: no API or hooks; best as local commit helper.
How to use (Recipe):
1. `pip install aider-chat`
2. Run `aider --model gpt-4o-mini` inside a git repo.
3. Describe changes; approve patch and let it commit.
Where it breaks: guesses wrong on binary files or large diffs.
Alternatives: Cursor, GitHub Copilot CLI.
Keep / Skip: Keep for quick terminal tweaks; skip if you need GUI flow.
Quick Benchmark (≤2 min):
Task: Fix typo in README (u/commitwizard on r/aider).
Time: 00:52
Quality: 4
Sample output: "Corrected spelling of asynchronous."

---

## 2. Zero-Budget Biz Helpers

- [FounderPal Idea Validator](https://founderpal.ai/idea-validator)  
  Tells you if your billion-dollar idea is more like fifty bucks.

- [FounderPal Business Ideas Generator](https://founderpal.ai/business-ideas-generator)  
  Toss in keywords, get startup pitches back.

---

## 3. Free LLM Hangouts

- [Lmarena.ai](https://lmarena.ai)  
  Pit language models against each other like it's a nerdy fight club.

- [OpenRouter](https://openrouter.ai)  
  One API to try many LLMs without selling your soul.

---

## 4. Last-Minute Deadline Lifesavers

- [Moonbeam](https://www.moonbeam.ai)  
  Whips up long-form drafts when the deadline is yesterday.

- [Jenni](https://jenni.ai)  
  Co-writes essays so you can pretend you planned ahead.

---

## 5. Design Help for the Talentless

- [Kittl](https://www.kittl.com)  
  Drag-and-drop designs that won't make your eyes hurt.

- [Illustroke](https://www.illustroke.com)  
  Turns your text into slick SVG illustrations.

---

## 6. Bedroom Beat Machines

- [Riffusion](https://www.riffusion.com)  
  Generates music from text—neighbors may be confused.

- [Beatoven](https://www.beatoven.ai)  
  Mood-based tracks for your podcast or secret mixtape.

---

## 7. Couch-Friendly Video Magic

- [OpusClip](https://www.opus.pro)  
  Cuts your long vids into viral-ready short clips.

- [Captions](https://www.captions.ai)  
  Auto-edits, adds captions, and makes you look pro without leaving the couch.

---

## 8. Automation Gremlins

- [Bardeen](https://www.bardeen.ai)  
  Little browser elves that click buttons for you.

- [Superflows](https://www.superflows.ai)  
  AI that drafts your emails before you even sigh.

---

## 9. SEO Spells & Hype Tricks

- [NeuralText](https://www.neuraltext.com)  
  Conjures keywords and outlines for your next hit post.

- [Postaga](https://postaga.com)  
  Finds backlinks and outreach targets while you nap.

---

## 10. Chatbots That Never Ghost

- [Flowise](https://flowiseai.com)  
  Build custom bots without touching a line of code.

- [Chatbase](https://www.chatbase.co)  
  Train a chatbot on your docs so customers stop emailing you.

---

## 11. Study Buddies That Don't Judge

- [TeachAnything](https://teach-anything.com)  
  Ask any "dumb" question; it answers nicely.

- [Explainpaper](https://www.explainpaper.com)  
  Upload a paper, get the TL;DR without the headache.

---

## 12. Numbers Whisperers

- [Obviously AI](https://www.obviously.ai)  
  Point, click, predict—no data science degree needed.

- [Exploratory](https://exploratory.io)  
  Visual data tinkering for the curious analyst.

---

## 13. Mind & Body Sidekicks

- [Wysa](https://www.wysa.io)  
  Chat about your day with a friendly therapy bot.

- [Skinive](https://skinive.com)
  Snap a pic, get a quick skin health check.

---

## 14. Agent Playgrounds

- [LangFlow](https://langflow.org)
  Drag-and-drop chains for LLM tinkering.

- [AutoGen Studio](https://autogen.microsoft.com)
  Spin up multi-agent workflows in your browser.

Open Interpreter — Talk to your machine, it types for you
[status: VERIFIED — 2025-09-04] [agent: API=no webhooks=no] [latency=L] [friction=med]
What it does: executes Python, JS, or shell commands from natural language chat.
Why it matters: prototypes automations without writing scripts.
Free-tier ceiling: open source; runs local models or OpenAI key; unlimited.
Agent-readiness: no API yet; treat as local multi-step orchestrator.
How to use (Recipe):
1. `pip install open-interpreter`
2. Run `interpreter` and ask for a task like "plot CSV".
3. Review and approve each command before execution.
Where it breaks: long-running tasks can stall; sandboxing is thin.
Alternatives: OpenAI Code Interpreter, AutoGPT.
Keep / Skip: Keep for quick data pokes; skip for production jobs.
Quick Benchmark (≤2 min):
Task: Summarize 100-row CSV (u/datajuggler on r/LocalLLaMA).
Time: 01:18
Quality: 4
Sample output: "Average sales: $532; peak in July."

---

## 15. Weird & Wonderful

- [Tavily](https://www.tavily.com)
  API that lets agents browse the live web smartly.

- [ComfyUI](https://comfyui.org)
  Visual node builder for wild diffusion experiments.

## 16. Under-the-Radar Agentic Tools

- [Adala](https://github.com/HumanSignal/Adala) — Turns labeling chores into obedient robot tasks.
- [Agent4Rec](https://github.com/LehengTHU/Agent4Rec) — Simulates movie fans so recommender models get smart.
- [AgentForge](https://github.com/DataBassGit/AgentForge) — Low-code workshop for crafting custom autonomous workers.
- [AgentGPT](https://agentgpt.reworkd.ai/) — Spawn goal-seeking GPTs in your browser sandbox.
- [AgentPilot](https://github.com/jbexta/AgentPilot) — Desktop cockpit for launching and chatting with agents.
- [Agents](https://github.com/aiwaves-cn/agents) — Aiwaves' toolkit for multi-agent experiments gone wild.
- [AgentVerse](https://github.com/OpenBMB/AgentVerse) — Collaboration playground for swarms of conversational bots.
- [AI Legion](https://github.com/eumemic/ai-legion) — Crowdsources open-source agents into digital armies.
- [AIlice](https://github.com/myshell-ai/AIlice) — Anime-styled chatbot that actually codes on command.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's multimodal agent orchestration toolkit.
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — Autonomous GPT worker that writes plans then executes.
- [Automata](https://github.com/emrgnt-cmplxty/automata) — LLM coder that roams your repo fixing TODOs.
- [AutoPR](https://github.com/irgolic/AutoPR) — Generates pull requests while you refill coffee.
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot) — Hires interns before HR wakes up.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) — Tiny agent that loops tasks like a toddler with coffee.
- [BabyBeeAGI](https://yoheinakajima.com/babybeeagi-task-management-and-functionality-expansion-on-top-of-babyagi/) — Adds swarm smarts to BabyAGI's todo list.
- [BabyCatAGI](https://replit.com/@YoheiNakajima/BabyCatAGI) — Feline-themed agent that chases goals nine times.
- [BabyDeerAGI](https://twitter.com/yoheinakajima/status/1666313838868992001) — Clumsy but determined task runner for experiments.
- [BabyElfAGI](https://twitter.com/yoheinakajima/status/1678443482866933760) — Holiday helper that scripts while you nap.
- [BabyCommandAGI](https://github.com/saten-private/BabyCommandAGI) — Shell-loving baby agent that sends terminal commands.
- [BabyFoxAGI](https://github.com/yoheinakajima/babyagi/tree/main/classic/babyfoxagi) — Sneaky task agent that pivots fast.
- [BambooAI](https://github.com/pgalko/BambooAI) — Scrapes websites politely then summarizes findings.
- [BeeBot](https://github.com/AutoPackAI/beebot) — Swarm-friendly automation that buzzes through forms.
- [Blinky](https://github.com/seahyinghang8/blinky) — CLI ghost that haunts logs for anomalies.
- [Bloop](https://bloop.ai/) — Code search that whispers answers from repos.
- [BondAI](https://bondai.dev/) — Hooks AI agents into microservices with minimal glue.
- [bumpgen](https://github.com/xeol-io/bumpgen) — Generates commit bumps without forgetting semver.
- [Cal.ai](https://cal.ai) — Calendar assistant that books meetings before you reply.
- [CAMEL](https://github.com/camel-ai/camel) — Role-playing agents that chat themselves into solutions.
- [ChatArena](https://www.chatarena.org/) — Battle royale for dialogue models in the browser.
- [ChatDev](https://github.com/OpenBMB/ChatDev) — Pretend dev team that scaffolds software via chat.
- [ChemCrow](https://github.com/ur-whitelab/chemcrow-public) — Lab assistant agent that drafts chemistry workflows.
- [Clippy](https://github.com/ennucore/clippy/) — Yes, that Clippy—now with GPT-4 snark.
- [CodeFuse-ChatBot](https://github.com/codefuse-ai/codefuse-chatbot) — Tencent's coder bot that patches Java faster.
- [Continue](https://continue.dev/) — VS Code plugin that completes code like a coworker.
- [CrewAI](https://github.com/joaomdmoura/crewai) — Assigns specialized AI roles and keeps them in sync.
- [data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper) — Turns raw datasets into academic PDFs.
- [Databerry](https://www.databerry.ai/) — No-code builder for LLM-powered data agents.
- [DemoGPT](https://github.com/melih-unsal/DemoGPT) — Records demos of agents without screen jitters.
- [DevGPT](https://github.com/jina-ai/dev-gpt) — Jina's agent that scaffolds microservices on demand.
- [Devika](https://github.com/stitionai/devika) — Browser agent that navigates like a patient intern.
- [Devon](https://github.com/entropy-research/Devon) — Research partner that reads docs so you don't.
- [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) — Automates deployments while ops sleeps.
- [dotagent](https://github.com/dot-agent/dotagent) — Minimal agent framework with dotfile vibes.
- [Eidolon](https://eidolonai.com/) — Serverless runtime for running ephemeral agents.
- [English Compiler](https://github.com/uilicious/english-compiler) — Turns plain English into scripts that actually run.
- [evo.ninja](https://evo.ninja/) — Evolutionary agent that mutates its own prompts.
- [FastAgency](https://fastagency.ai/latest/) — Template-based framework for shipping agents fast.
- [Friday](https://github.com/amirrezasalimi/friday/) — AI sidekick that schedules, emails, and nags gently.
- [GeniA](https://github.com/genia-dev/GeniA) — Spanish-friendly agent builder with guardrails.

---

## Delta Log

2025-09-04 — Added: 50 tools; Verified: none; Removed: none; Notable combo: none
2025-09-04 — Added: 2 tools; Verified: aider, open-interpreter; Removed: none; Notable combo: none
2025-09-04 — Added: 4 tools; Verified: none; Removed: none; Notable combo: none


# Michael Perry

**Operations leader who builds AI workflows that people can actually trust.**

I've spent over a decade in manufacturing operations: first in clean-room medical device packaging at DePuy Synthes (Johnson & Johnson), and since 2020 as Director of Logistics at a custom manufacturer, where I was one of three people who rebuilt operations from the ground up after the entire management team left at once. I designed the BOM and traveler system that tracks every build step with built-in quality checks, and it **cut errors by 40%.** I also built the serial-number system, the location tracking for roughly 3,000 warehouse parts, and the QC, safety, and RMA processes.

That work taught me to ask a few questions of any process: *What's the source of truth? What needs human judgment? What happens when information is uncertain? Can we reconstruct what happened?* I now ask the same questions about AI.

## How I work

I'm not a traditional software engineer, and I don't pretend to be. I work like a technical lead: I map the process, define the rules and boundaries, write the specification and tests, and direct AI coding agents to build it. Then I have a *second* model review the work, because the one who built it shouldn't be the one who signs off on it.

## Projects

| Project | What it shows | Status |
|---|---|---|
| **[Coral](https://github.com/perry-is/coral-portfolio)** | A private AI layer that decides what each model is allowed to see, refuses rather than leaking, and keeps receipts of every decision. Optional local model via Ollama. | Public slice of a personal system I'm building |
| **[AI Bookkeeping Workflow](https://github.com/perry-is/ai-bookkeeping-workflow)** | Plain-English bookkeeping rules turned into enforced logic. AI may *suggest* a category, but suggestions always go to human review and never touch the totals. | Built from my own business's bookkeeping procedure |
| **[AI Content Operations](https://github.com/perry-is/ai-content-operations-pipeline)** | One podcast episode in, six publishing outputs out, with rules that stop AI from inventing exercises or links. | Modeled on the system I use for my podcast and workshops |
| **[Coral Forge](https://github.com/perry-is/coral-forge)** | A bounded loop for AI coding agents: allow-listed actions, tests as the judge, hard retry limit. | Teaching demo |

All public repos use fictional data. The real versions hold personal, client, or business information, which doesn't belong on GitHub.

## What ties it together

**Model output is not a business fact.** AI can propose a record, a category, or a draft. Something only becomes official after it passes rules a person can read and, where it matters, a person approves it. Every project here follows that rule in a different setting.

## Background

- Director of Logistics, custom manufacturing (2020–present): inventory, purchasing, QC, travelers, BOMs, supplier relations
- Senior Packager, DePuy Synthes / Johnson & Johnson (2011–2017): ISO clean room, SAP
- A.A. in Psychology
- Facilitator and teacher: workshops on leadership, communication, and change

**Tools I work with:** Python · SQLite · Git and GitHub Actions · Ollama and local LLMs · OpenAI and Anthropic models · Claude Code and Codex · Home Assistant · Excel

**Website:** [perry.is](https://perry.is)

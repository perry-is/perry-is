# Michael Perry

**Operations leader who builds AI workflows that people can actually trust.**

I've spent over a decade in manufacturing operations: first in clean-room medical device packaging at DePuy Synthes (Johnson & Johnson), and since 2020 as Director of Logistics at a custom manufacturer, where I was one of three people who rebuilt operations from the ground up after the entire management team left at once. I designed the BOM and traveler system that tracks every build step with built-in quality checks, and it **cut errors by 40%.** I also built the serial-number system, the location tracking for roughly 3,000 warehouse parts, and the QC, safety, and RMA processes.

That work taught me to ask a few questions of any process: *What's the source of truth? What needs human judgment? What happens when information is uncertain? Can we reconstruct what happened?* I now ask the same questions about AI.

## How I work

I'm not a traditional software engineer, and I don't pretend to be. I work like a technical lead: I map the process, define the rules and boundaries, write the specification and tests, and direct AI coding agents to build it. Then I have a *second* model review the work, because the one who built it shouldn't be the one who signs off on it.

## Apps

| | |
|---|---|
| **[CampaignKit](https://github.com/perry-is/campaign-kit)** · Mac app<br>Paste an event and get checked facts, posts for every platform, and three AI-designed flyers in the client's own style, learned from their past flyers. Every flyer is fact-checked, and nothing publishes until a person approves it. One app serves many businesses: a client's logo re-themes the whole interface.<br>*Electron · React · TypeScript · OpenAI image and text models.* Desktop rebuild of my [AI Event Marketing Platform](https://github.com/perry-is/ai-event-marketing-platform) (FastAPI · PostgreSQL · React). | <a href="https://github.com/perry-is/campaign-kit"><img src="https://github.com/perry-is/campaign-kit/raw/main/docs/ai-flyers/copper-kettle-croissant-3.jpg" width="220" alt="AI-designed flyer from CampaignKit"></a> |
| **[Show Stand](https://github.com/perry-is/show-stand)** · iPhone and iPad<br>Turns a device into a branded booth display for vendors at markets and pop-ups, with offline lead capture. Zero network calls, no accounts, and the lead list locks behind Face ID.<br>*SwiftUI · SwiftData.* | <a href="https://github.com/perry-is/show-stand"><img src="https://github.com/perry-is/show-stand/raw/main/docs/images/cover.png" width="220" alt="Show Stand"></a> |
| **[Meridian: Three Fronts](https://github.com/perry-is/Meridian)** · iPhone and Mac game<br>An original isometric sci-fi strategy game: three asymmetric factions, a computer opponent that scouts, expands and counters, and an art pipeline that turns AI-made 3D models into animated sprites. About 20,000 lines of Swift with a tested, deterministic simulation core.<br>*Swift · SpriteKit · Blender Python · Tripo.* | <a href="https://github.com/perry-is/Meridian"><img src="https://github.com/perry-is/Meridian/raw/main/docs/showcase/battle_lattice_brood.jpg" width="220" alt="Meridian battle"></a> |
| **[Voice Studio](https://github.com/perry-is/voice-studio)** · Mac app<br>Design custom AI voices, test them by talking and chatting with local models, and serve both speech and chat through an OpenAI-compatible API my other projects call, all running privately on my Mac. Speak to it and local Whisper transcribes you; pick any Ollama model, give it its own personality and settings, and hear replies in a custom voice with response times shown. Works from my phone over a private Tailscale network.<br>*Python · MLX on Apple Silicon · Whisper · Ollama · FastAPI · SwiftUI.* | <a href="https://github.com/perry-is/voice-studio"><img src="https://github.com/perry-is/voice-studio/raw/main/docs/screenshots/04-models-chat.png" width="220" alt="Voice Studio test chat"></a> |

## AI workflow projects

| Project | What it shows | Status |
|---|---|---|
| **[Operations Forecasting](https://github.com/perry-is/operations-forecasting-system)** | Excel in, planning workbook out: inventory forecasts and reorder recommendations. It withholds numbers when the data is bad, and old forecasts can't be rewritten after the fact. | Rebuilt from a tool I built and used in my logistics job |
| **[Coral](https://github.com/perry-is/coral-portfolio)** | A private AI layer that decides what each model is allowed to see, refuses rather than leaking, and keeps receipts of every decision. Optional local model via Ollama. | Public slice of a personal system I'm building |
| **[AI Bookkeeping Workflow](https://github.com/perry-is/ai-bookkeeping-workflow)** | Plain-English bookkeeping rules turned into enforced logic. AI may *suggest* a category, but suggestions always go to human review and never touch the totals. | Built from my own business's bookkeeping procedure |
| **[AI Content Operations](https://github.com/perry-is/ai-content-operations-pipeline)** | One podcast episode in, six publishing outputs out, with rules that stop AI from inventing exercises or links. | Modeled on the system I use for my podcast and workshops |
| **[Coral Forge](https://github.com/perry-is/coral-forge)** | A bounded loop for AI coding agents: allow-listed actions, tests as the judge, hard retry limit. | Experimental demonstration |

All public repos use fictional data. The real versions hold personal, client, or business information, which doesn't belong on GitHub.

## What ties it together

**Model output is not a business fact.** AI can propose a record, a category, or a draft. In every project here, that proposal either has to pass rules a person can read or waits in a queue for a person, and none of it becomes official on its own.

## Background

- Director of Logistics, custom manufacturing (2020–present): inventory, purchasing, QC, travelers, BOMs, supplier relations
- Senior Packager, DePuy Synthes / Johnson & Johnson (2011–2017): ISO clean room, SAP
- A.A. in Psychology
- Facilitator and teacher: workshops on leadership, communication, and change

**Tools I work with:** Python · Swift and SwiftUI · TypeScript, React and Electron · SQLite · Git and GitHub Actions · Ollama and local LLMs · OpenAI and Anthropic models · Claude Code and Codex · Excel and openpyxl · Home Assistant

**Website:** [perry.is](https://perry.is)

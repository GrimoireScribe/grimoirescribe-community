# GrimoireScribe

**A local-first writing app for novelists who take their craft seriously.**

> **Status: Closed beta / pre-release** — Windows version is in active development. Public release coming soon. [Watch this repo](../../watchers) or visit [grimoirescribe.com](https://grimoirescribe.com) to be notified at launch.

---

## What is GrimoireScribe?

GrimoireScribe is a desktop writing application built for long-form fiction authors. Think of it as a modern alternative to Scrivener — built around a clean, distraction-free editor with deep AI writing assistance baked in.

Your books live on **your machine**. No cloud, no accounts, no subscriptions. AI features use your own API keys (Anthropic, OpenAI, or xAI) so you're always in control of your data and costs.

---

## Features

### Writing & Structure
- **Acts, chapters, and scenes** — organise your manuscript your way
- **Rich text prose editor** — bold, italic, alignment, focus mode
- **Drag-and-drop reordering** — chapters and acts, cross-structure
- **Two writing modes** — Scenes mode (full scene management) or Chapters mode (chapter = writing unit)
- **Scene status tracking** — draft / in-progress / complete
- **Author notes** — per-scene private notes, never sent to AI
- **Soft delete with Trash** — restore deleted chapters and scenes

### AI Writing Assistance
| Mode | What it does |
|------|-------------|
| **Write** | Generate new prose for a scene |
| **Edit** | Improve or rewrite existing prose |
| **Discuss** | Open-ended conversation about your book |
| **Chapter** | Draft a full multi-scene chapter |
| **New Scene** | Generate a single new scene |

- Works with **Anthropic (Claude), OpenAI, or xAI (Grok)** — your keys, your costs
- Injects writing style, characters, world notes, and the previous scene for continuity
- Persistent chat history in Discuss mode
- AI auto-detects and adds character names from accepted prose

### Characters & World Building
- Character profiles: name, role, description, aliases, arc
- Scan Characters — AI detects characters from your prose automatically
- Character appearances — see which scenes each character is in
- World Notes — per-book rich text editor (bold, italic, headings, lists)
- World Documents — upload .pdf, .docx, .txt, .rtf, .md reference files
- Optional Voyage AI RAG — semantic retrieval from world docs at prompt time

### Import & Export
- **Scrivener** — import and export .scriv zip files; resync from linked project
- **DOCX / TXT import** — paste an existing manuscript and split into chapters/scenes automatically
- **Compile to EPUB** — Kindle-ready EPUB 3 with TOC, cover, and typography settings
- **Compile to DOCX** — standard manuscript format for agents/editors
- **Compile to PDF** — 6×9 trade paperback layout via Puppeteer
- **Plain text / Markdown export** — simple chapter-by-scene text dump
- **Book backup** — zip your entire book folder with one click

### Tools & Productivity
- **Full-text search** — search across all books or within one
- **Find & Replace** — scene / chapter / book scope, case-insensitive option
- **Word count targets** — per-book goal with progress bar
- **Auto-backup** — scheduled zip backups on a configurable interval
- **Keyboard shortcuts** — Ctrl+S, Ctrl+F, Esc, and more (press `?` for overlay)
- **Usage tracking** — token counts and cost estimates per AI call
- **Appearance** — dark/light theme, custom fonts, font size S/M/L/XL
- **Series grouping** — multi-book series with aggregate stats and series-wide AI discussion

---

## Platform Support

| Platform | Status |
|----------|--------|
| **Windows 10 / 11** | In development — releasing soon |
| **Mac (macOS)** | Planned after Windows v1.0 |
| **iPad** | Planned after Mac v1.0 |

---

## Pricing

GrimoireScribe will be a **one-time purchase — no subscription, ever.** Buy it once, own it. Future major versions included for v1 buyers.

Pricing will be announced at launch. Visit [grimoirescribe.com](https://grimoirescribe.com) to sign up for early access.

---

## This Repository

This is the **public community hub** for GrimoireScribe. The source code is closed and lives in a private repository.

**What this repo is for:**
- Bug reports
- Feature requests
- Questions and discussion

**What this repo is not:**
- The source code (closed source — not available here)
- A place to request open-sourcing the project

---

## Filing a Bug Report

1. Click **Issues** → **New Issue**
2. Choose the **Bug Report** template
3. Include: what you were doing, what you expected, what happened instead
4. Attach a screenshot if relevant

Please check existing issues before filing — your bug may already be tracked.

---

## Requesting a Feature

1. Click **Issues** → **New Issue**
2. Choose the **Feature Request** template
3. Describe the problem you're trying to solve, not just the solution
4. If a similar request exists, add a thumbs-up reaction rather than filing a duplicate

Popular requests get prioritised. The more context you give, the better.

---

## Roadmap (High Level)

### Now — Windows v1.0
- Windows packager (Electron / Tauri — decision pending)
- Code-signed installer (.exe) — no SmartScreen warnings
- Auto-updater
- License key system (one-time purchase via LemonSqueezy)
- Closed beta with real writers

### After Windows Launch
- Mac support — signed .dmg installer
- First-run onboarding experience
- Scene version history / snapshots
- Typewriter mode
- Daily writing goals

### V2 and Beyond
- Local LLM support (Ollama / LM Studio)
- Hybrid AI mode — local for discussion, cloud for generation
- Full privacy mode — no cloud calls at all
- Writing statistics and streak tracking
- SQLite backend for large manuscript performance
- iPad app (Capacitor)

---

## Stay in Touch

- **Website:** [grimoirescribe.com](https://grimoirescribe.com)
- **Issues / feedback:** right here on GitHub

---

_GrimoireScribe is closed source. © 2026 GrimoireScribe. All rights reserved._

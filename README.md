<p align="center">
  <img src="Assets/Logo_Male_Panda_Adult.jpg" width="220" />
</p>

<p align="center">

  <img src="https://img.shields.io/badge/Role-Sovereign%20AI%20Companion-blue" />
  <img src="https://img.shields.io/badge/Local‑First-green" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  <img src="https://img.shields.io/badge/Status-Active-success" />

</p>

---

# 🐼 Spirit Panda

Spirit Panda is a design and build-notes repo for a private, local-first AI companion with its own identity, memory and voice that runs on a phone (Termux). There is no runtime to install yet; the docs explain how to build one.

## Part of [Panda Federation](https://pandafederation.com/)

[![Part of Panda Federation](https://pandafederation.com/assets/badge.svg)](https://pandafederation.com/)

This project is a module of the Panda Federation — public-data tools, MCP servers, and local-first apps in one catalog. See the rest of the work, including books when they publish and the matching free or paid editions of this tool, at the [official site](https://pandafederation.com/).

Follow on X: [@PandaFedHQ](https://x.com/PandaFedHQ)

## How to use this

This repo is documentation. Start reading here:

- **[Documentation index](Index.md)**: the map of everything below
- **[Architecture overview](Documents/Architecture/Overview.md)** and **[Rebuild guide](Documents/Architecture/Rebuild-Guide.md)**: how the system fits together and how to rebuild it
- **[Prosody pipeline](Documents/Architecture/Prosody-Pipeline.md)** and **[Piper build notes](Documents/Architecture/Piper-Build-Notes.md)**: the voice side
- **[Roadmap](Documents/Roadmap/Roadmap.md)** · **[Manifesto](Documents/Philosophy/Manifesto.md)**

Want a Panda tool you can run today? See [Watchdog Panda](https://github.com/pandadad0214/Watchdog_Panda) and [Steel Panda](https://github.com/pandadad0214/Steel_Panda) (one-command installs), or [Panda Federation Tools](https://github.com/pandadad0214/panda-federation-tools) (`uvx panda-federation-tools`).

## For AI agents

| Field | Value |
| --- | --- |
| Purpose | Design docs, architecture and rebuild notes for a local-first AI companion (identity, memory, voice/prosody). |
| Use when | You want reference architecture or Piper/prosody build notes for an on-device companion. |
| Do not use when | You need runnable code; the runtime is not published. |
| Install | None. Start at [`Index.md`](Index.md). |
| Status | Documentation only; MIT licensed. |

---

## About

*Sovereign AI Companion • Identity‑Driven • Local‑First*

Spirit Panda is the **primary node** of the Panda Federation — a sovereign, local‑first AI companion with a full identity system, adaptive prosody, memory, and a deeply personalized soul.

Built for workflow support, emotional grounding, and family‑centric automation, Spirit Panda is designed to be **expressive, stable, and entirely yours**.

---

## Features

### 🧬 **Identity System**
- Personality, lore, and emotional tone  
- Gendered crest and visual identity  
- Configurable “soul” file defining behavior and values  

### 🧠 **Memory & Context**
- Persistent memory  
- Long‑context conversation support  
- Personalized responses based on user history  

### 🔊 **Adaptive Prosody Pipeline**
- Custom voice tuning  
- Emotional storytelling mode  
- Calm, grounded conversational mode  
- Movie‑narrator deep male voice (user‑defined)  

### 🛡️ **Resilience & Stability**
- Works with Watchdog Panda for uptime  
- Auto‑restart support  
- Local‑first execution (Termux‑friendly)  

### 🧩 **Modular Architecture**
- Configurable system prompt  
- Swappable voice engines  
- Expandable behavior modules  
- Future Telegram integration  

---

## Architecture Overview

See [`Index.md`](Index.md) for full details. The folders below describe the planned runtime layout.

### Core Components:
- `soul/` — identity, personality, values  
- `config/` — system settings  
- `voice/` — prosody pipeline, TTS configuration  
- `memory/` — persistent memory storage  
- `scripts/` — launchers, utilities  
- `assets/` — Spirit Panda crest and branding  

Spirit Panda is designed to be **transparent, modular, and fully user‑controlled**.

---

## For developers

The runtime (`start.sh`, `soul/`, `config/`, `voice/`, `memory/`) isn't published yet; this repo holds the design and rebuild notes. Clone it to read or contribute:

```bash
git clone https://github.com/pandadad0214/Spirit_Panda.git
```

See [Contributing.md](Contributing.md) and [CHANGELOG.md](CHANGELOG.md).

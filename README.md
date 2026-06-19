# Link AI — Autonomous Desktop Agent

> Put your desktop on autopilot. Type a goal, Link AI does it.

![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Version](https://img.shields.io/badge/version-1.0.0-blueviolet)
![License](https://img.shields.io/badge/license-MIT-green)

---

## What is Link AI?

Link AI is a Windows desktop app that watches your screen and executes tasks from plain English instructions — or your voice.

Tell it *"open Spotify and play my liked songs"*, *"find the cheapest flight to Berlin and screenshot the result"*, or *"send that email draft"* — and it handles the clicks, typing, app switching, and browsing for you.

No scripting. No macros. Just talk to your computer.

---

## Features

- **Autonomous control** — clicks, typing, scrolling, app launching, hotkeys
- **Voice control** — say *"link, open YouTube"* hands-free with wake-word detection
- **Background launching** — open apps like Spotify while gaming, no focus stolen from your game
- **Smart AI routing** — Gemini primary with Groq fallback for near-zero downtime
- **Multi-model support** — switch between Gemini, Claude Sonnet, Fable 5, and Opus from inside the app
- **Plan tiers** — Free (Gemini Auto), Pro (Claude Sonnet), Max (Fable 5 + Opus)
- **GitHub & Google login** — sign in with your existing accounts

---

## Download

Head to the [Releases page](https://github.com/cisl28/Link-AI/releases/latest) and download **LinkAI-Setup.exe**.

- No admin required — installs per-user
- Adds a Start Menu and optional Desktop shortcut
- Uninstall anytime from Windows Settings → Apps

**Requirements:** Windows 10 / 11 (64-bit) · Internet connection

---

## How it works

1. Launch Link AI and sign in
2. Type a goal in the chat box — or press the mic and say *"link, \<your goal\>"*
3. Watch it take over — the agent sees your screen, decides what to click/type, and executes step by step
4. Hit **Ctrl+Shift+F12** anytime to stop it immediately

---

## Models

| Plan | Models available |
|------|-----------------|
| **Free** | Gemini (Auto) — Gemini primary with Groq fallback |
| **Pro** | + Claude Sonnet 4.6, Claude Haiku 4.5, Gemini 2.5 Pro |
| **Max** | + Fable 5 (flagship), Claude Opus 4.8, GPT-5.1 |

Switch models anytime from the **Model** pill in the top-right corner of the dashboard.

---

## Privacy

Link AI takes screenshots of your screen to understand what's happening and decide what to do. Screenshots are sent to the AI model you have selected and are not stored. Your API keys stay on your machine.

---

## License

MIT

